# Weekly Review

Friday reviews appended here.

Template for each entry:

## Week ending YYYY-MM-DD

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $X |
| Ending portfolio | $X |
| Week return | ±$X (±X%) |
| S&P 500 week | ±X% |
| Bot vs S&P | ±X% |
| Trades | N (W:X / L:Y / open:Z) |
| Win rate | X% |
| Best trade | SYM +X% |
| Worst trade | SYM -X% |
| Profit factor | X.XX |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|

### What Worked
- ...

### What Didn't Work
- ...

### Key Lessons
- ...

### Adjustments for Next Week
- ...

### Overall Grade: X

---

## Week ending 2026-05-01

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $100,000.00 (Apr 27 open) |
| Ending portfolio | $99,141.49 |
| Week return | -$858.51 (-0.86%) |
| S&P 500 week | ~+1.0% (7,243.95 close; 6th consecutive weekly gain) |
| Bot vs S&P | -1.86% |
| Trades | 1 (W:0 / L:0 / open:1) |
| Win rate | N/A (no closed trades) |
| Best trade | NVDA (only trade; -4.32% unrealized) |
| Worst trade | NVDA -4.32% unrealized |
| Profit factor | N/A |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| — | — | — | — | No closed trades this week |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| NVDA | $207.15 (96 sh) | $198.21 | -$858.51 (-4.32%) | GTC trail 10%, HWM $206.99, stop $186.29 |

### What Worked
- Patience discipline: avoided chasing NVDA at ATH $216 on Apr 28 and GOOGL post-10% gap
- Candidate scoring system (≥7/10 gate) correctly filtered out GOOGL (extended), MSFT/META (negative catalysts), XOM (R:R <1.5)
- 20% position cap respected: NVDA sized at 19.4% of equity
- GTC trailing stop placed on NVDA immediately — structural protection at $186.29
- Adapted to API outages (Apr 27 Run 3: Alpaca, Tavily, Telegram all 403) using WebSearch fallback rather than abandoning research

### What Didn't Work
- Massively underdeployed all week: 19% invested vs 75–85% target — single biggest failure
- NVDA entry timing poor: bought ~$207 near ATH, then Apr 30 OpenAI revenue miss drove NVDA down; entered into binary risk (FOMC + Mag 7 week)
- Zero entries on Apr 27–28 when the market ran to records (+1%+ on strong earnings momentum) — opportunity cost significant
- No Apr 29/30 research log entries committed to git — gaps in record-keeping
- Infrastructure reliability: Day 1 APIs all blocked (403); no fallback execution path

### Key Lessons
- Underdeployment is as costly as a bad trade: sitting 100% cash while S&P gains 1%+ is a guaranteed loss to benchmark
- Entry timing relative to binary events matters: FOMC/Mag7 caution was right in principle but created a tunnel that kept us in 0% equity position too long
- Once the binary clears, act fast — the Apr 30 +800 Dow session showed the risk-on signal; should have moved on GOOGL/NVDA confirmation that day
- API outage contingency needed: if Alpaca is blocked, the market-open routine cannot execute; need a retry/alert workflow
- Records discipline: all trade entries and EOD snapshots must be committed same-day

### Adjustments for Next Week
- **Deploy aggressively by Tuesday May 6**: Target 2–3 new positions (GOOGL pullback to $355–365, AAPL stabilization, one sector diversifier); hit 60–80% deployed
- **NVDA**: Hold through May 20 earnings; if closes below $192 (near stop), reassess thesis; do NOT tighten stop below HWM $206.99
- **GOOGL**: Initiate if pulls back to $355–365 — Cloud +63%, $460B backlog = top candidate; stop $320, target $430, R:R 2.3:1
- **NFP May 8**: Next major macro gate — plan entry timing around print; if strong, add risk immediately after release
- **Research continuity**: Ensure daily-summary commits EOD snapshots every day — no more gaps

### Overall Grade: C-
