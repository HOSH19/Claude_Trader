# Setup Walkthrough

The repo scaffolding is done. The remaining steps all happen in external dashboards (GitHub, Claude Code, Alpaca, Tavily, Telegram). Follow these in order.

## 0. Push the repo to GitHub

```bash
# from the repo root
gh repo create trading-bot --private --source . --remote origin --push
# OR, if you don't have gh:
#   create the empty repo at https://github.com/new (private, no README/license)
#   then:
git remote add origin git@github.com:<your-username>/trading-bot.git
git push -u origin main
```

## 1. Sign up for the data providers (skip any you already have)

| Service | Where | What you need |
|---|---|---|
| Alpaca | https://alpaca.markets/ | Open a **paper** account first; copy API Key + Secret from the dashboard. Live account too if you plan to flip later. |
| Tavily | https://app.tavily.com/ | Sign up (no credit card), generate an API key from the dashboard. Free tier = 1000 searches/month, plenty for this bot's ~170/month. |
| Telegram | t.me/BotFather | Create a bot via `/newbot`, save the bot token. Then message your bot once and grab your chat ID from `https://api.telegram.org/bot<TOKEN>/getUpdates` (the `chat.id` field). |

## 2. Connect the repo to Claude Code

1. Open [claude.ai/code](https://claude.ai/code) and go to your project settings.
2. Under **GitHub integration**, click **Connect repository**.
3. On GitHub, choose **Only select repositories** → select your `trading-bot` repo → grant **Read & write** access.
4. Back in Claude Code, confirm the repo appears in the connected repos list.

Without this, remote agents can't clone your repo and can't push memory updates back to `main`.

## 3. Add environment variables in Claude Code project settings

Go to your Claude Code project settings → **Environment Variables**. Add each of the following. Never commit these values to the repo — they must only live in the dashboard.

| Variable name | Example / Notes |
|---|---|
| `ALPACA_API_KEY` | from Alpaca dashboard |
| `ALPACA_SECRET_KEY` | from Alpaca dashboard |
| `ALPACA_ENDPOINT` | `https://paper-api.alpaca.markets/v2` (start here; flip to `https://api.alpaca.markets/v2` after a successful paper week) |
| `ALPACA_DATA_ENDPOINT` | `https://data.alpaca.markets/v2` |
| `TAVILY_API_KEY` | from app.tavily.com (free 1000 searches/month) |
| `TAVILY_SEARCH_DEPTH` | `basic` (recommended) or `advanced` |
| `TELEGRAM_BOT_TOKEN` | bot token from @BotFather, format `1234567890:AAEhBP9...` |
| `TELEGRAM_CHAT_ID` | numeric chat ID — your user ID, group ID, or channel ID |

These are injected as process env vars into every scheduled agent run. The wrapper scripts read them directly from the process environment — no `.env` file is sourced or needed.

## 4. Register the five scheduled routines

In a Claude Code session with this repo open, use `/schedule` to register each routine. For each one:

- Pass the **entire** file contents as the prompt (verbatim — don't paraphrase; the env-check block and commit-and-push step are load-bearing)
- Use `durable: true` so the schedule persists across sessions
- Use the cron expressions below (in your local timezone — shift hours if you are not in PT)

| # | Name | Cron (PT) | Equivalent ET | Prompt source |
|---|---|---|---|---|
| 1 | Trading bot - pre-market | `0 4 * * 1-5` | 7:00 AM ET (2.5h before open) | paste contents of [`routines/pre-market.md`](routines/pre-market.md) |
| 2 | Trading bot - market-open | `30 6 * * 1-5` | 9:30 AM ET (open) | paste contents of [`routines/market-open.md`](routines/market-open.md) |
| 3 | Trading bot - midday | `0 10 * * 1-5` | 1:00 PM ET | paste contents of [`routines/midday.md`](routines/midday.md) |
| 4 | Trading bot - daily-summary | `0 13 * * 1-5` | 4:00 PM ET (close) | paste contents of [`routines/daily-summary.md`](routines/daily-summary.md) |
| 5 | Trading bot - weekly-review | `0 14 * * 5` | 5:00 PM ET Friday | paste contents of [`routines/weekly-review.md`](routines/weekly-review.md) |

**Timezone offsets** (if not on PT):
- ET = PT + 3
- CT = PT + 2
- UTC = PT + 7 (winter) / +8 (summer)

**Note on expiry:** Claude Code CronCreate schedules auto-expire after 7 days unless `durable: true` is set. If routines stop running after a week, re-register them via `/schedule`.

The remote agents push directly to `main` as instructed by the routine prompts — no pull request setting to configure.

## 5. Smoke-test the pre-market routine

Before enabling all five schedules, manually trigger the **pre-market** routine only (via `/schedule` → run now). Watch the run logs and verify:

- [ ] `.claude/settings.json` is present — without it bash calls will block for approval
- [ ] Env-var preflight prints all six required vars as `set` (none `MISSING`)
- [ ] `bash scripts/alpaca.sh account` returns valid JSON (paper account equity)
- [ ] Tavily calls succeed, or gracefully fall back to native WebSearch
- [ ] `memory/RESEARCH-LOG.md` gains a new dated entry
- [ ] No `.env` file was created (the prompt forbids this)
- [ ] Run ends with `git push origin main` succeeding (check `git log` on GitHub)

If any of these fail, see the troubleshooting table below before re-running.

If all green, enable the schedules on the other four routines.

## 6. Run a paper week, then go live

1. Let the bot run on the paper endpoint for **at least 5 trading days**.
2. Each evening, read the day's commits on GitHub: `memory/RESEARCH-LOG.md`, `memory/TRADE-LOG.md` deltas.
3. Watch Telegram for daily summaries. Make sure the format and tone are reasonable.
4. After a successful paper week, swap `ALPACA_ENDPOINT` in the Claude Code project environment variables to `https://api.alpaca.markets/v2`. **No code changes needed.** The next scheduled run picks up the live endpoint.

## Troubleshooting

| Symptom | Likely cause | Fix |
|---|---|---|
| "Repository not accessible" / clone fails | Claude Code GitHub integration not connected | Connect per Step 2 |
| `git push` fails with permission error | App lacks write access, or branch protection on `main` | Re-grant write access; turn off branch protection on `main` for this repo |
| `ALPACA_API_KEY not set in environment` | Variable missing or misnamed in project settings | Add it in Step 3 dashboard, not in any `.env` file |
| Agent creates a `.env` file anyway | Prompt was paraphrased and lost the "DO NOT create .env" block | Re-paste the prompt from `routines/*.md` exactly |
| Yesterday's trades missing from today's run | Previous run didn't commit+push | Verify `git log origin/main`; re-check STEP N of that routine |
| Push fails "fetch first" / non-fast-forward | Two runs raced | Prompt handles this with `git pull --rebase`. If looping, look for a real merge conflict |
| Telegram message didn't arrive | `TELEGRAM_BOT_TOKEN` or `TELEGRAM_CHAT_ID` missing, OR you never messaged the bot first (Telegram requires you to start the chat before a bot can DM you) | Script falls back to a local file silently; add the missing var or send `/start` to the bot |
| Tavily calls didn't happen | `TAVILY_API_KEY` missing | Script exits 3, agent falls back to WebSearch. Add the key or accept fallback |
| Alpaca rejects stop with PDT error | Same-day stop on same-day buy | Prompt's fallback ladder (trailing → fixed → queue tomorrow) handles it. If not cascading, re-paste STEP 5 verbatim |
| Scheduled routine stops running after a week | CronCreate 7-day auto-expiry | Re-register via `/schedule` in Claude Code, or verify `durable: true` was used |
| `git commit` fails with "Please tell me who you are" | No git identity on remote VM | `CLAUDE.md` instructs the agent to run `git config user.email/name` before commits; verify it is present at repo root |
| Bash calls block waiting for approval | `.claude/settings.json` missing or permissions allowlist not set | Verify `.claude/settings.json` exists with the `allow` array from Step 2 of this repo's setup |

## Reference docs

- Claude Code docs: https://docs.anthropic.com/en/docs/claude-code
- Claude Code scheduled agents: https://docs.anthropic.com/en/docs/claude-code/scheduled-tasks
- Alpaca trading API: https://docs.alpaca.markets/
- Tavily API: https://docs.tavily.com/
