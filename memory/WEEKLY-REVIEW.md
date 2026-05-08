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

---

## Week ending 2026-05-08

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $99,164.92 (May 4 open) |
| Ending portfolio | $101,181.31 |
| Week return | +$2,016.39 (+2.03%) |
| S&P 500 week | ~+2.02% (7,243.95 → 7,390.13) |
| Bot vs S&P | +0.01% (tied) |
| Phase P&L | +$1,181.31 (+1.18%) vs S&P phase +2.81% → -1.63% vs benchmark |
| Trades | 2 (W:0 / L:0 / open:2; NVDA carried from wk 1) |
| Win rate | N/A (no closed trades) |
| Best trade | AAPL +6.00% unrealized |
| Worst trade | MSFT -0.44% unrealized |
| Profit factor | N/A |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| — | — | — | — | No closed trades this week |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| AAPL | $276.38 (28 sh, May 4) | $292.96 | +$464.30 (+6.00%) | Trail 10%, HWM $292.96, stop ~$263.67 |
| NVDA | $207.15 (96 sh, Apr 28) | $214.98 | +$751.66 (+3.78%) | Trail 10%, HWM $214.20, stop $192.78 |
| MSFT | $416.87 (19 sh, May 8) | $415.05 | -$34.65 (-0.44%) | Trail 10%, HWM $416.48, stop $374.83 |

Deployed: $36,726.97 (36.3%) | Cash: $64,454.34

### What Worked
- AAPL entry timing: May 4 entry at $276.38 into post-earnings pullback zone was clean; +6.00% in 4 trading days
- NVDA recovery: survived the -5.28% scare on May 5 without triggering -7% cut; recovered to +3.78% by week end
- Candidate scoring: MSFT correctly scored 9/10 (highest of the week) — Azure +40%, Q3 beat, Goldman top pick; thesis validated
- Sector discipline: All 3 positions in XLK (top-tier YTD); avoided financials (XLF -8.27% YTD) and healthcare (XLV worst)
- Stop hygiene: All 3 positions have active GTC trailing stops; no manual overrides or lapses

### What Didn't Work
- Deployment remains critically low: 36.3% deployed vs 80% target — 2nd consecutive week of massive underdeployment
- NVDA position oversizes the 8% max rule (~19.7% of equity, $19,886 cost basis) — this was a rule violation from week 1 never corrected
- MSFT initiated on NFP Friday end-of-week instead of earlier — higher gap risk, weaker conviction timing
- META (scored 8/10) not initiated despite passing all checks — left a high-conviction setup on the table
- Still no closed trades in 2 weeks — no realized P&L; all performance is paper unrealized gains

### Key Lessons
- Underdeployment is now the #1 structural drag: being 63.7% in cash while the market grinds higher costs 1%+ per week in opportunity cost vs benchmark
- NVDA position sizing violates the 8% rule (19.7% of equity) — oversized position from inception; the rule must be respected going forward; cannot add more until NVDA trims to below 8%
- End-of-week entries (MSFT on Friday) carry inherent weekend gap risk — prefer Mon-Wed entries for new positions
- META at 8/10 was actionable and was skipped due to FOMC uncertainty; FOMC hold was priced in — that hesitation cost potential alpha
- "3 new trades per week" budget used this week (AAPL + MSFT = 2; but NVDA was week 1); next week all 3 slots available

### Adjustments for Next Week
- **Deployment push**: Must reach ≥60% by Wed May 13; scout 2 quality entries Mon AM pre-market; no more sitting on 64% cash
- **Primary candidates**: META (still 8/10, $619 zone), GOOGL (pullback candidate if market softens on CPI May 12), AMZN (cloud backlog story)
- **NVDA**: Hold through May 20 earnings; stop $192.78 intact; do NOT add (rule violation to add when already at 19.7%)
- **MSFT**: Early in position (-0.44%); thesis intact (Azure +40%); hold unless thesis breaks; stop $374.83
- **AAPL**: At +6%; tighten trail to 7% when it reaches +15% (~$317.84); stop now ~$263.67
- **FOMC May 10 (Wed)**: Rate decision — no new buys Mon-Tue; initiate after FOMC holds confirmed
- **CPI May 12**: Secondary macro gate; tech-heavy portfolio sensitive to inflation prints

### Overall Grade: B-
