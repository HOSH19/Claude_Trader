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

## Week ending 2026-05-15

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | ~$101,500 (est. May 11 AM; EOD snapshots May 08–11 missing) |
| Ending portfolio | $102,600 |
| Week return | +$1,100 (+1.1%) |
| S&P 500 week | +0.6% (7,398.94 → 7,445.11) |
| Bot vs S&P | +0.5% outperformance |
| Phase P&L | +$2,600 (+2.60% from $100K) |
| Trades | 1 (W:0 / L:0 / open:4) |
| Win rate | N/A (no closed trades) |
| Best trade | NVDA +8.62% unrealized |
| Worst trade | MSFT +0.76% unrealized |
| Profit factor | N/A |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| — | — | — | — | No closed trades this week |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| AAPL | $276.38 (28 sh) | $300.23 | +$667.80 (+8.63%) | GTC trail 10%, HWM $300.92, stop $272.88 |
| META | $598.88 (13 sh) | $612.03 | +$170.90 (+2.20%) | GTC trail 10%, HWM $623.73, stop $561.36 |
| MSFT | $416.87 (19 sh) | $420.30 | +$65.10 (+0.82%) | GTC trail 10%, HWM $418.63, stop $376.77 |
| NVDA | $207.15 (96 sh) | $224.85 | +$1,699.18 (+8.54%) | GTC trail 10%, HWM $236.54, stop $212.89 |

### What Worked
- All 4 positions profitable at week end: NVDA +8.54%, AAPL +8.63%, META +2.20%, MSFT +0.82%
- MSFT entry thesis validated: post-earnings capex fear was overdone; recovered from -2.58% mid-week to green
- META entry (May 12) disciplined: bought into the dip on hot CPI day; position already +2.20%
- NFP-driven MSFT entry on May 08 (+115K vs +65K est.) worked exactly as planned — strong jobs = tech rally
- Slight S&P 500 outperformance (+0.5%) for the week despite selling today (NVDA -4.62%, META -1.03%)

### What Didn't Work
- Portfolio still badly underdeployed: 44.8% vs 80% target — third consecutive week below 60%; massive opportunity cost
- Only 1 of 3 weekly trade slots used (META May 12); AVGO and GOOGL (both 8/10) held back by bars API null for 3rd consecutive week
- No closed trades in 3 weeks running — zero realized P&L; trailing stops at risk if NVDA May 20 earnings disappoint
- NVDA earnings binary (May 20) creates outsized risk: $1,699 unrealized gain exposed on single catalyst event
- EOD snapshot discipline still failing — May 08–14 snapshots missing from trade log

### Key Lessons
- Bars API null is a systemic operational blocker, not a one-off: three consecutive weeks of failed pre-market technical validation cannot be accepted as normal; need explicit fallback rule
- Consistently missing deployment target (20% → 27% → 44% deployed) means the strategy's "80% deployed" rule is being systematically violated; opportunity cost is material
- All current positions are beating or near entry — the entry criteria (score ≥7, catalyst, sector) is working; the failure is in execution volume, not selection quality
- NVDA May 20 earnings risk: holding 96 shares into a binary event with $1,699 unrealized gain and stop at $212.89 (-5.3% below current) is acceptable risk given thesis strength, but must be monitored closely

### Adjustments for Next Week
- **Bars API fallback (new rule — see TRADING-STRATEGY.md)**: When bars null, use WebSearch for technical validation; do not block entry on API failure alone
- **NVDA May 20**: Hold through earnings; if opens down >10% post-earnings, evaluate close vs wait; stop $212.89 provides structural floor; if +15% triggers ($238.22), tighten trail to 7% immediately
- **AVGO, GOOGL (primary targets Mon May 18)**: Both scored 8/10 this week but blocked by bars null; execute Monday AM if WebSearch/bars confirm setup; do not let 3rd consecutive week pass without filling 2–3 positions
- **Deployment target**: Must reach 70–80% deployed by end of May 18 week; use all 3 trade slots if 3 candidates pass the gate
- **Record-keeping**: Commit EOD snapshots every day this week — no gaps; set this as first commit of daily-summary routine

### Overall Grade: B-
