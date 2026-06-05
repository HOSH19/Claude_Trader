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

## Week ending 2026-05-22

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $102,603.24 (May 15 close) |
| Ending portfolio | $101,707.94 |
| Week return | -$895.30 (-0.87%) |
| S&P 500 week | ~+1.13% (7,408→7,492) |
| Bot vs S&P | -2.00% |
| Trades | 1 (W:0 / L:0 / open:1) |
| Win rate | N/A (no closed trades) |
| Best trade | AAPL +11.70% unrealized |
| Worst trade | GOOGL -1.67% unrealized |
| Profit factor | N/A |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| — | — | — | — | No closed trades this week |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| AAPL | $276.38 (28 sh) | $308.72 | +$905.52 (+11.70%) | $280.25 (HWM ~$309) |
| GOOGL | $389.84 (20 sh) | $383.34 | -$129.90 (-1.67%) | $353.25 |
| META | $598.88 (13 sh) | $609.83 | +$142.30 (+1.83%) | $561.36 |
| MSFT | $416.87 (19 sh) | $418.64 | +$33.56 (+0.42%) | $389.43 |
| NVDA | $207.15 (96 sh) | $215.03 | +$756.46 (+3.80%) | $212.89 (⚠️ 1.0% above stop) |

### What Worked
- Deployment progress: 52% deployed vs 44% prior week — gap closing
- AAPL is standout at +11.70%; approaching +15% tighten threshold ($317.84)
- GOOGL entry May 20 added diversification; AI/cloud thesis intact long-term
- META and MSFT stable with intact structural stops
- XLK tech sector concentration remains strategically correct (top tier YTD)

### What Didn't Work
- Negative absolute returns (-0.87%) vs S&P +1.13% = -2.00% relative — worst weekly performance yet
- NVDA dangerously close to stop: $215.03 vs $212.89 (1.0% gap) — one bad day stops it out at only +3.80% after 4 weeks
- GOOGL immediately below entry (-1.67%); first position opened in the red
- Still 52% deployed vs 80% target — persistent underdeployment for 4th consecutive week
- Used only 1/3 trade slots again; not acting with enough conviction on valid setups

### Key Lessons
- NVDA stop ($212.89) now a near-term binary risk — HWM $236.54 is old; position has drifted down while stop hasn't moved; at 1% above stop after 4 weeks this is a poor return on held capital
- AAPL tighten window is close — prepare to update the stop to 7% trail when it clears $317.84
- All 5 positions are tech (XLK) — single-sector concentration; need one energy or defensive name
- GOOGL entry slightly premature vs prior research which identified $380 as the ideal entry zone
- The pattern of 1 trade/week when 3 slots are available means setups are either too rare or the entry bar is too high; be more decisive on ≥7/10 scoring candidates

### Adjustments for Next Week
- **NVDA**: Watch closely at Monday open; if it gaps down toward $212.89, evaluate thesis vs locking +3.80%; do NOT manually cut unless -7% or thesis breaks — let the stop work
- **AAPL**: Tighten trailing stop to 7% when price exceeds $317.84; current $308.72 is close
- **New positions**: Target 2 new entries next week — scout XOM or CVX (energy diversifier, oil ~$100+) plus one high-conviction tech; get to 65-70% deployed
- **Sector diversification**: All 5 in tech — must add non-tech name to reduce XLK concentration risk
- **Execution discipline**: If a candidate scores ≥7/10 AND bars confirm, pull the trigger — stop over-waiting

### Overall Grade: C-

---

## Week ending 2026-05-29

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $101,707.94 (May 22 close) |
| Ending portfolio | $102,893.31 |
| Week return | +$1,185.37 (+1.17%) |
| S&P 500 week | +1.67% (7,464→7,599) |
| Bot vs S&P | -0.50% |
| Trades | 2 (W:1 / L:0 / open:5) |
| Win rate | 100% (1/1 closed) |
| Best trade | MSFT +7.17% (week) |
| Worst trade | GOOGL -2.39% unrealized |
| Profit factor | N/A (no losses) |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| NVDA | $207.15 (96 sh) | $212.71 | +$533.76 (+2.68%) | GTC trailing stop auto-triggered May 26; HWM $236.54, stop $212.89 |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| AAPL | $276.38 (28 sh) | $311.25 | +$976.36 (+12.62%) | $283.46 (HWM $314.96) |
| AVGO | $416.89 (19 sh) | $445.02 | +$534.47 (+6.75%) | $403.99 (HWM $448.88) |
| GOOGL | $389.84 (20 sh) | $380.51 | -$186.50 (-2.39%) | $354.49 (HWM $393.88) |
| META | $598.88 (13 sh) | $632.15 | +$432.46 (+5.55%) | $578.70 (HWM $643.00) |
| MSFT | $416.87 (19 sh) | $448.60 | +$602.80 (+7.61%) | $405.30 (HWM $450.33) |

### What Worked
- NVDA trailing stop executed perfectly — auto-triggered at $212.71 protecting +2.68% realized gain with zero manual intervention
- AVGO entry (May 28) immediately strong: +6.75% in 2 days on AI infrastructure / hyperscaler demand thesis
- MSFT surged +7.17% this week on Azure AI momentum — now highest unrealized gain by $; stop tightened to $405.30
- AAPL compounds steadily: +12.62% unrealized, approaching +15% tighten threshold ($317.84)
- META holding +5.55%; stop and HWM structure intact

### What Didn't Work
- Persistent deployment failure (5th consecutive week): 40.1% deployed vs 80% target; $61K+ cash idle all week
- Bot vs S&P: -0.50% underperformance despite positive absolute return; cumulative drag building
- GOOGL continues to weaken — 3rd consecutive week negative to flat; -2.39% unrealized, approaching -7% cut ($362.55)
- Only 1 new position (AVGO) this week with 3 slots available; TSM and JPM candidates identified but not executed
- All 5 positions remain in XLK tech — zero sector diversification for 5+ weeks

### Key Lessons
- GTC trailing stops are the single most reliable mechanism in the system — trust them; NVDA executed exactly as designed
- GOOGL (-2.39%, 3 weeks negative) is dead weight; if it doesn't recover to entry by Tuesday, re-evaluate thesis vs deploying capital elsewhere
- Deployment paralysis is now the #1 structural risk to beating S&P — idle cash guarantees underperformance in a bull market
- AAPL tighten window imminent ($317.84); must update stop to 7% trail on break above
- MSFT $405.30 stop reflects major intraday HWM; protect this gain — do NOT let it give back to $389 stop

### Adjustments for Next Week
- **Deploy aggressively**: Must open 2–3 positions — JPM (XLF sector #1), TSM (AI foundry), or XOM/CVX (energy diversifier); target 65–75% deployed by EOW
- **GOOGL**: Cut immediately at $362.55 (-7%); if no positive catalyst by Tuesday, consider proactive exit above stop and reallocate
- **AAPL**: Tighten trailing stop to 7% when price exceeds $317.84; current $311.25 is close
- **MSFT**: Monitor against new HWM; stop at $405.30 is healthy; no changes unless new HWM prints
- **Sector diversification**: All tech portfolio = concentration risk; one JPM or XOM entry reduces single-sector exposure

### Overall Grade: C+

---

## Week ending 2026-06-05

### Stats

| Metric | Value |
|--------|-------|
| Starting portfolio | $102,915.38 (May 29 close) |
| Ending portfolio | $100,330.81 |
| Week return | -$2,584.57 (-2.51%) |
| S&P 500 week | -1.82% (7,599→7,461) |
| Bot vs S&P | -0.69% |
| Trades | 4 (W:1 / L:2 / open:3) |
| Win rate | 33% (1/3 closed) |
| Best trade | MSFT +$53.58 (+0.68%) |
| Worst trade | GOOGL -$558.60 (-7.16%) |
| Profit factor | 0.08 |

### Closed Trades

| Ticker | Entry | Exit | P&L | Notes |
|--------|-------|------|-----|-------|
| GOOGL | $389.84 (20 sh) | ~$361.91 | -$558.60 (-7.16%) | Trailing stop auto-triggered Jun 02; 3 weeks persistent weakness |
| AVGO | $416.89 (19 sh) | ~$409.95 | ~-$132.00 (-1.66%) | Earnings gap-down Jun 04 AH (-13.97%); 7% trail limited vs entry price breach |
| MSFT | $416.87 (19 sh) | ~$419.69 | ~+$53.58 (+0.68%) | Trailing stop triggered Jun 05 on NASDAQ selloff; tiny gain |

### Open Positions at Week End

| Ticker | Entry | Close | Unrealized | Stop |
|--------|-------|-------|------------|------|
| AAPL | $276.38 (28 sh) | $307.22 | +$863.52 (+11.16%) | $285.24 (HWM $316.93) |
| META | $598.88 (13 sh) | $590.90 | -$103.79 (-1.33%) | $578.70 (HWM $643.00) |
| NVDA | $213.59 (37 sh) | $204.94 | -$320.11 (-4.05%) | $192.59 (HWM $213.98) |

### What Worked
- GTC trailing stops executed correctly on all 3 closes — automated system protected capital without manual intervention
- 7% tightened stop on AVGO (from +15.61%) — while earnings gap broke through entry price anyway, the tighten reflected correct discipline
- NVDA re-entry thesis well-reasoned: AVGO-spend redirect, analyst upgrades, NFP gate (+85K passed ≥+80K threshold)
- NFP-gated NVDA entry (waited for print + 10am conditions) avoided pre-NFP whipsaw
- S&P 500 also sold off -1.82% this week; relative underperformance contained to only -0.69%

### What Didn't Work
- Three stop-outs in two trading sessions (Jun 02–05): GOOGL, AVGO, MSFT all exited; phase P&L collapsed from +$2,915 to +$331
- AVGO earnings gap risk known in advance (Jun 01 research flagged binary event explicitly); trailing stop cannot protect a +15.61% position against a -14% gap that breaks entry price
- NVDA re-entry on Jun 05 immediately -4.05%: entered on volatile NFP Friday into -1.14% NASDAQ — conditions technically met but intraday trend hostile
- META only 2.0% above stop ($578.70) heading into Monday; 4th potential stop-out risk
- Deployment collapsed back to 23.8% after exits — 6th consecutive week below 80% target

### Key Lessons
- Trailing stops protect against gradual drawdowns but NOT earnings gap risk: AVGO gapped -14%, blew through the 7% tightened stop ($455.91) and the entry price ($416.89), resulting in a loss despite being a +15.61% winner at peak
- Earnings pre-action needed for big winners: a position >+10% unrealized held into earnings should be partially exited (50%) 1 session before the report; trailing stop handles the remaining 50%
- Friday macro-day (NFP/FOMC) entries face immediate adverse price action — NVDA on NFP Friday opened into the selloff; consider avoiding new entries on NFP/FOMC Fridays
- Phase P&L +$330.81 (+0.33%) after 6 weeks is near breakeven; chronic underdeployment (avg ~40% vs 80% target) is the compounding drag that prevents recovery
- Stops working perfectly is necessary but not sufficient — win rate 33%, profit factor 0.08 signals entry/hold quality is the structural problem

### Adjustments for Next Week
- **META**: Stop $578.70 only 2.0% away; do not move stop; let auto-execute if triggered Monday — 4th stop-out is possible but acceptable per rules
- **NVDA**: -4.05% unrealized at $204.94, stop $192.59 (9.5% cushion); thesis intact; -7% manual cut at $198.64 — monitor closely on open
- **AAPL**: +11.16% unrealized, stop $285.24; approaching +15% tighten at $317.84; tighten to 7% on break above
- **Earnings pre-action rule (provisional)**: For positions with unrealized >+10%, exit 50% one session before earnings; keep trailing stop on remainder — evaluate for 2 more earnings events before formalizing
- **New positions**: 3 positions, 23.8% deployed, 3 buy slots — MUST open 2 entries by Wednesday; scout JPM (XLF diversifier), AMZN (AI/cloud), or TSLA (confirmed catalyst required); target 55%+ deployed by EOW
- **No new entries on NFP/FOMC Fridays**: evaluate entries on the following Monday when dust settles

### Overall Grade: D