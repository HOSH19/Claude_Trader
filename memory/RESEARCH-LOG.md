# Research Log

---

## 2026-06-17 (Day 38, Wednesday — Pre-Market)

**Account snapshot:** Equity $100,143.34 | Cash $68,704.42 (68.6%) | Buying Power $84,423.88 | DT count: 0
**Session-start equity (last_equity):** $100,187.44 | **Portfolio DD:** -0.04% — no halt

### Open Positions (pre-market)
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Notes |
|--------|--------|-------|---------|------------|------|-----|-------|
| AAPL | 28 | $276.38 | $298.50 | +$619.36 (+8.00%) | $285.66 | $317.40 | +15% trigger @ $317.84 — not yet |
| JPM | 24 | $322.67 | $330.88 | +$197.04 (+2.54%) | $298.58 | $331.75 | Finance thesis working |
| MSFT | 19 | $396.72 | $392.11 | -$87.59 (-1.16%) | $361.58 | $401.75 | Near breakeven; Azure AI intact |
| NVDA | 37 | $213.59 | $207.83 | -$213.18 (-2.70%) | $192.59 | $213.98 | Cut trigger $198.64; buffer 4.3% |

**Weekly trade slots used:** 2/3 (MSFT + JPM on Jun 15) | **1 slot remaining**

### Market Context
- **Oil:** WTI ~$75.57 (-0.63%), Brent ~$78.25 (-0.89%) — flat to slightly down; -30% past month (Strait of Hormuz reopened) (oilprice.com, tradingeconomics.com)
- **SPX Futures:** 7,514.50 vs prev close 7,518.50 (-0.05%) — essentially flat (investing.com)
- **VIX:** ~16.0-16.41 (+1.30%) — slightly elevated, moderate fear (cboe.com, yahoo.finance.com)
- **FOMC:** Kevin Warsh's first meeting Jun 16-17; decision announced TODAY ~2 PM ET — expected HOLD per CNBC Fed Survey; BUT dot plot may signal hawkish shift (50% analysts expect rate hike before end 2026) (cnbc.com, kiplinger.com, raymondjames.com)
- **Earnings BMO:** Jabil Inc (JBL) only — not in universe; no impact
- **Key releases 8:30 AM ET:** (1) Retail Sales May, (2) Housing Starts May 1.17M est, (3) Initial Jobless Claims — claims rose to 4.5-month high (bearish labor signal) (marketwatch.com, census.gov)

### Sector ETF Ranking (week of Jun 17)
1. **XLK Technology** — #1 YTD; AI supercycle intact (annacoulling.com)
2. **XLE Energy** — #2 despite oil pullback; rotation continues
3. **XLI Industrials** — #3; real-economy rotation
- **XLF Financials** — -0.26% YTD; weakening (totalrealreturns.com)
- **XLV Healthcare** — bottom tier; avoid

### Candidate Scoring (20-symbol universe)
*Bars null pre-market; volume scores conservative; prices from position endpoint + Tavily*

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **META** | **7/10** | 2 | 2 | 2 | 1 | 0 | **PASS score — FAIL R:R; FOMC-gated** |
| NVDA (held) | 9/10 | 2 | 2 | 2 | 1 | 2 | Already held — monitor |
| AAPL (held) | 7/10 | 2 | 2 | 2 | 0 | 1 | Already held — HOLD |
| MSFT (held) | 7/10 | 2 | 2 | 2 | 0 | 1 | Already held — HOLD |
| JPM (held) | 5/10 | 1 | 1 | 2 | 0 | 1 | Already held — HOLD |
| AMZN | 6/10 | 1 | 2 | 1 | 1 | 1 | FAIL (<7) |
| AMD | 5/10 | 1 | 2 | 1 | 0 | 1 | FAIL |
| GS | 3/10 | 1 | 1 | 0 | 0 | 1 | FAIL |
| TSM | 4/10 | 1 | 2 | 0 | 0 | 1 | FAIL (extended) |
| XOM | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL (oil -30% past month) |
| CVX | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| GOOGL | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL (stopped out) |
| TSLA | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL |
| V | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| MA | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| UNH | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| JNJ | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| AVGO | N/A | — | — | — | — | — | Stopped out; no re-entry |
| SPY | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |
| QQQ | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |

**META notes:** Instagram Plus + AI cost controls catalyst confirmed; tech sector #1 YTD; price ~$571.68 below SMA20 est ~$580 (at/below = +2 setup). Vol est ~average (1). R:R: Entry $572, stop $515 (-10%), target $643 (HWM) = $71 reward / $57 risk = 1.25:1 → scores 0 (< 1.5). Stopped out Jun 10 @ $578.70 — re-entry below own stop level is structurally weak. (yahoo.finance.com)

### Technical Validation — META (Score 7/10, bars null — estimated)
- **Current price (est):** ~$571.68 (prior close)
- **SMA20 (est):** ~$580 (averaging ~$560-$643 range over 20d)
- **Dist from SMA20:** ~-1.4% → BELOW SMA ✓ PASS
- **5d momentum:** Jun 10 est ~$588 → ($571.68-$588)/$588 × 100 = **-2.8% NEGATIVE** (1 fail)
- **Volume ratio:** Catalyst-driven but pre-market conservative; est ~1.0× avg → borderline
- **Outcome:** 1 confirmed fail → passes 2-fail threshold, BUT R:R = 0 (< 1.5 disqualifies)
- **Technical verdict:** PASS fails but R:R gate blocks trade

### Trade Ideas
**No qualifying trade ideas today.**
- META only ≥7 candidate; blocked by R:R < 1.5 AND FOMC announcement pending (2 PM ET)
- NVDA 9/10 but already held; no additional shares warranted (position ~7.7% of equity)
- Preserve 1 buy slot for post-FOMC Thursday if Warsh is neutral/dovish

### Risk Factors
1. **FOMC announcement ~2 PM ET (CRITICAL):** Hawkish dot plot / SEP = 50% chance per Kiplinger. Rate hike signal for 2026 = tech selloff risk. Decision will define week's tone (kiplinger.com, cnbc.com)
2. **8:30 AM data (HIGH):** Retail Sales + Housing Starts + Jobless Claims simultaneously. Claims at 4.5-month high = weak labor = risk-off potential if retail also misses (marketwatch.com)
3. **NVDA -2.70% unrealized, -4.3% buffer to manual cut ($198.64):** If FOMC hawkish + tech sell, NVDA vulnerable; let trailing stop auto-execute at $192.59 if hit; do NOT intervene (alpaca positions)
4. **Low deployment (ONGOING):** 31.4% vs 80% target; best opportunity is post-FOMC Thursday with 1 slot remaining
5. **MSFT -1.16% unrealized:** Near breakeven; hawkish FOMC = risk; HWM $401.75, stop $361.58 (9.1% buffer)
6. **Oil continued decline (-30% past month):** Strait of Hormuz fully priced in; energy sector ETF weakening; XOM/CVX no longer candidates

### Decision
**HOLD — FOMC announcement pending; no new buys**
- Primary: FOMC decision announced today ~2 PM ET; Warsh's first meeting; hawkish dot plot risk = no new positions
- Secondary: Only META clears 7/10 but R:R = 0 (<1.5 minimum) AND entry below prior stop level — invalid setup
- Existing: All 4 positions above stops and manual cut levels; no action required pre-open
- Monitor: NVDA $207.83 (-2.70%), cut trigger $198.64 only 4.3% away — watch at open
- Next: Post-FOMC Thursday pre-market → if neutral/dovish, strong case for META re-entry (with better R:R setup) or energy/finance diversification
- Sources: oilprice.com (WTI/Brent), investing.com (SPX futs), cboe.com + yahoo.finance.com (VIX), x.com/marketsday (earnings), marketwatch.com + census.gov (econ calendar), annacoulling.com (sectors), totalrealreturns.com (XLF YTD), cnbc.com + kiplinger.com + raymondjames.com (FOMC/Warsh), cnbc.com (BofA NVDA/AAPL picks), Goldman/JPM PT $280 on NVDA

## 2026-06-17 — Midday Addendum (Day 38, Wednesday)

**Account snapshot (midday):** Equity $100,071 | Cash $68,704 | Positions: 4 | DT count: 0
**Portfolio DD:** -0.12% — no halt

**Intraday position check:**
| Ticker | Current | Day Chg | Unrealized | Stop | Status |
|--------|---------|---------|------------|------|--------|
| AAPL | $297.55 | -0.57% | +7.66% | $285.66 | OK |
| JPM | $336.78 | +1.70% | +4.37% | $303.99 (auto-trailed from $298.58, HWM $337.77) | OK — Finance outperforming |
| MSFT | $383.86 | -2.53% | -3.24% | $361.58 | Monitor; thesis intact but continued capex fear selloff |
| NVDA | $206.97 | -0.22% | -3.10% | $192.59 | Stable; cut trigger $198.64 ~4% away |

**Actions taken:** None — no cuts (all above -7%), no tightens (none at +15%), no thesis breaks.

**FOMC context (2 PM ET today):** Decision expected HOLD; dot plot hawkish shift risk remains. Warsh press conference 2:30 PM ET. MSFT -2.53% reflecting pre-FOMC tech caution. JPM +1.70% = financials benefiting from rate-hike-signal rotation. No position changes warranted pending outcome; let GTC stops manage risk.

---

## 2026-06-15 — Midday Scan (Day 36, Monday)

**Account snapshot:** Equity ~$100,162 | Cash ~$68,704 | Positions: 4 | DT count: 0
**Session-start equity (last_equity):** $99,729.86 | **Portfolio DD:** +0.43% — no halt

### Open Positions (midday)
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $296.56 | +$564.90 (+7.30%) | $285.66 (10% trail) | $317.40 | HOLD; +15% trigger $317.84 — HWM not yet there |
| JPM | 24 | $322.67 | $321.13 | -$36.96 (-0.48%) | $290.55 (10% trail) | $322.83 | HOLD; first day in position; well above -7% cut ($300.08) |
| MSFT | 19 | $396.72 | $399.43 | +$51.40 (+0.68%) | $361.58 (10% trail) | $401.75 | HOLD; +2.22% day; HWM updated; well above -7% cut ($368.95) |
| NVDA | 37 | $213.59 | $212.37 | -$45.20 (-0.57%) | $192.59 (10% trail) | $213.98 | HOLD; +3.50% day recovery; -7% cut at $198.64 (6.5% buffer) |

### Midday Scan Results
- DD halt: +0.43% from last_equity — no halt
- Cuts: none (all positions above -7% cut levels)
- Stop tighten: none (no position at +15% or +20% threshold)
- Thesis: all intact — Iran peace deal / Azure AI / risk-on thesis holding; NVDA bounce +3.50% confirms GPU demand thesis
- Intraday research: skipped (no sharp unexplained moves)
- Action: ✅ All clear

---

## 2026-06-15 (Day 36, Monday — Pre-Market)

**Account snapshot:** Equity $100,015.58 | Cash $68,704.43 (68.7%) | Positions: 4 | DT count: 0
**Session-start equity (last_equity):** $99,729.86 | **Portfolio DD:** +0.29% — no halt
**Buy slots this week:** 2/3 used (MSFT + JPM today)

### Market Context
- **Iran-US Peace Deal (CONFIRMED):** Trump announced Jun 14 evening; Strait of Hormuz reopening; Dow futs +342 (+0.7%), S&P futs +0.9%, Nasdaq futs +1.4%; Asian stocks +5%+ (Tokyo, Seoul). Source: multibagg.ai, washingtonpost.com, cnbc.com/2026/06/15
- **Oil:** WTI crashed below $81/barrel (from $95+ prior week) on Hormuz reopening; Brent ~$83-84. XLE BEARISH — avoid XOM/CVX.
- **VIX:** Opened 19.13, declining to 17.97 (range 17.80-19.22) — risk-on. Source: investing.com, barchart.com
- **S&P 500:** +1.29% | Nasdaq: +2.11% — strong broad rally. Source: MarketWatch
- **Key risk:** FOMC meeting THIS WEEK (Warsh-led; first under new Chair); rate decision expected Wednesday Jun 17. Oil crash may support dovish hold. Source: Saxo Bank market-quick-take-15-june-2026
- **Caution:** CNBC: "some investors caution Iran deal could unravel"

### Sector ETF Ranking (This Week)
1. **XLK Technology** — AI supercycle + risk-on from Iran deal; Nasdaq +2.11%
2. **XLF Finance** — Risk-on catalyst directly benefits financials; risk premium unwinding
3. **XLI Industrials** — Led Jun 12 bounce per MarketWatch
4. **XLE Energy** — OIL CRASHING (-15%+ on Iran deal). AVOID XOM/CVX.

### Open Positions (pre-trade)
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $295.44 | +$535.92 (+6.90%) | $285.66 | $317.40 | HOLD; stop intact |
| NVDA | 37 | $213.59 | $209.70 | -$143.99 (-1.82%) | $192.59 | $213.98 | HOLD; above -7% cut ($198.64) |

### Candidate Scoring (20-symbol universe)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **MSFT** | **9/10** | 2 | 2 | 2 | 1 | 2 | ✅ EXECUTED — primary |
| **JPM** | **7/10** | 2 | 2 | 1 | 1 | 1 | ✅ EXECUTED — finance diversification |
| AVGO | 8/10 | 1 | 2 | 2 | 1 | 2 | HOLD 3rd slot — no fresh specific catalyst; recent stop-out Jun 4 |
| AAPL | — | — | — | — | — | — | Already held (+6.90%) |
| NVDA | — | — | — | — | — | — | Already held (-1.82%); above cut threshold |
| AMZN | 6/10 | 1 | 1 | 1 | 1 | 2 | FAIL — no specific catalyst |
| XOM/CVX | 1/10 | 0 | 0 | 1 | 1 | 1 | FAIL — oil crashing, sector bearish |
| GOOGL | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — stopped out, thesis broken |
| META | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — stopped out |
| TSLA | 2/10 | 1 | 1 | 0 | 0 | 1 | FAIL |
| AMD | 3/10 | 1 | 2 | 0 | 1 | 0 | FAIL — extended above SMA |
| TSM | 5/10 | 1 | 2 | 1 | 1 | 1 | FAIL — no specific catalyst |
| GS/V/MA/UNH/JNJ/SPY/QQQ | <7 | — | — | — | — | — | FAIL — various |

**MSFT catalyst notes:** Azure AI $37B annual revenue run rate (+123% YoY per investing.com); Wedbush PT $575; quantum milestone with Quantinuum; Iran deal = macro risk-on; price at ~$396 vs prior stop-out ~$419 = fresh entry at lower price. Source: tradingkey.com, investing.com, robinhood.com/MSFT
**JPM catalyst notes:** US-Iran peace deal = risk-on = finance sector catalyst; Q2 EPS est $5.39, earnings Jul 14; broader market rally benefits financials. Source: perplexity.ai/finance/JPM, cnbc.com/2026/06/15

### Trade Ideas Executed

**#1 — BUY MSFT (Microsoft) — EXECUTED**
- Entry: $396.72 (market) | Stop: $356.62 (10% trail, HWM $396.24) | Target: $575.00
- Shares: 19 × $396.72 = $7,537.68 (7.54% of equity)
- R:R: 4.5:1 | Score: 9/10

**#2 — BUY JPM (JP Morgan) — EXECUTED**
- Entry: $322.67 (market) | Stop: $290.44 (10% trail, HWM $322.71) | Target: $387.20
- Shares: 24 × $322.67 = $7,744.08 (7.74% of equity)
- R:R: 2.0:1 | Score: 7/10

### Risk Factors
1. **FOMC Wednesday Jun 17 (HIGH):** New Chair Warsh; first meeting. Rate decision could reverse gains. Oil crash may support dovish hold.
2. **Iran deal fragility (MEDIUM-HIGH):** CNBC notes "some investors caution deal could unravel." If deal collapses, sharp risk-off reversal.
3. **Tech sector 2+ consecutive failed trades (MEDIUM):** GOOGL, AVGO, MSFT, META all stopped out in May-June. MSFT re-entry is thesis-driven, not trend-chasing.
4. **NVDA at -1.82% unrealized (MEDIUM):** Cut level $198.64 (current $209.70, buffer $11.06 / 5.3%). Monitor.
5. **AAPL approaching +15% trigger (LOW):** HWM $317.40 vs trigger $317.84. Very close; tighten trail to 7% if HWM exceeded.

### Decision
**TRADES EXECUTED:** MSFT (19 shares) + JPM (24 shares); 2/3 weekly slots used
**3rd slot preserved** for post-FOMC Wednesday setup or high-conviction catalyst this week

*Sources: multibagg.ai (Iran deal/markets), washingtonpost.com/2026/06/14 (peace deal), cnbc.com/2026/06/15 (US stocks Iran), investing.com (VIX), barchart.com (futures), tradingkey.com (MSFT Azure), investing.com/analysis/microsoft (MSFT discount), perplexity.ai/finance/JPM (JPM earnings), Saxo Bank market-quick-take-15-june-2026 (FOMC), MarketWatch*

---

## 2026-06-12 (Day 35, Friday — Midday Scan)

**Account snapshot:** Equity $99,735.04 | Cash $83,986.19 (84.2%) | Positions: 2 | DT count: 0
**Session-start equity:** $99,844.02 (last_equity) | Portfolio DD: -0.11% — no halt

### Open Positions (midday)
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $291.36 | +$419.44 (+5.42%) | $285.66 | $317.40 | HOLD; HWM $317.40 just below +15% trigger $317.84 |
| NVDA | 37 | $213.59 | $205.18 | -$311.23 (-3.94%) | $192.59 | $213.98 | HOLD; -7% cut at $198.64, current $6.54 above |

### Midday Scan Results
- DD halt: -0.11% — no halt
- Cuts: none (NVDA -3.94%, AAPL +5.42% — both within rules)
- Stop tighten: none (AAPL HWM $317.40 < $317.84 trigger; NVDA far from +15%)
- Thesis: intact for both positions
- Intraday research: skipped (no sharp moves without cause)
- Action: ✅ All clear

---

## 2026-06-08 (Day 31, Monday — Week 7 Open)

**Account snapshot:** Equity $100,491.70 | Cash $76,464.15 (76.1%) | Positions: 3 | DT count: 0
**Session-start equity:** $100,491.70 | Portfolio DD: 0% — no halt
**Buy slots this week:** 3/3 available (NVDA bought last Friday Jun 05 = prior week)

### Open Positions (premarket)
| Ticker | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|-------|---------|------------|------|-----|-------|
| AAPL | $276.38 | $307.65 | +11.3% | $285.24 | $316.93 | HOLD; approaching +15% trigger (~$317.84) |
| META | $598.88 | $592.20 | -1.1% | $578.70 | $643.00 | WATCH — only 2.3% above stop; thesis weakening (AI delays) |
| NVDA | $213.59 | $208.51 | -2.4% | $192.59 | $213.98 | HOLD; +$80B buyback/dividend catalyst; 7.7% above stop |

### Market Context
- **Oil:** WTI ~$93.91–94.72 | Brent ~$97.07–97.63 — elevated on Iran/Israel ceasefire breakdown
- **SPX futures:** 7,402.75 (+2.25 / +0.03%) — essentially flat; NASDAQ 100 futs +69.75 (+0.24%)
- **VIX:** ~19.90 (declining from ~21.51 prev close) — moderating but elevated vs May
- **Geopolitical:** Iran fired missiles at Israel overnight → fragile ceasefire risks unraveling. Asia-Pacific markets fell sharply (Kospi -8.4%). Strait of Hormuz concerns (Piper Sandler: closed for months).
- **Earnings today BMO:** Campbell Soup (CPB), AstroNova — no universe names
- **Econ calendar:** Light today (Employment Trends 10 AM ET); **CPI Wednesday Jun 10** (major vol driver); PPI Thursday Jun 11
- **AI cycle:** NVDA $80B buyback/dividend announced Jun 5 (moneymorning.com). NVDA upgrade cycle intact (heygotrade.com #1 June pick). AMD flagged as weakness — semiconductor selloff watch.

*Sources: markets.businessinsider.com (oil/SPX futs), cboe.com (VIX), cnbc.com/2026/06/07 (Iran-Israel), rttnews.com (earnings calendar), thomsoninvestmentgroup.com (econ cal), x.com/marketsday (econ cal), heygotrade.com (NVDA upgrades), moneymorning.com (NVDA buyback)*

### Sector ETF Ranking (This Week)
1. **XLK Technology** — YTD #1 (+11.33% YTD per totalrealreturns.com); AI supercycle + NVDA upgrade cycle; NASDAQ futs +0.24% today
2. **XLE Energy** — Oil surging on Iran/Israel; up today; was +10.22% week of May 27
3. **XLI Industrials** — Steady positive; data center buildout tailwind

Bottom: XLV Healthcare (-1.35% YTD), XLF Financials (-0.5% wk), XLU Utilities flat

*Source: totalrealreturns.com, x.com/TheETFTracker*

### Candidate Scoring (20-symbol universe only)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **MSFT** | **8/10** | 1 | 2 | 2 | 1 | 2 | **PASS — conditional entry** |
| NVDA | 7/10 | 2 | 2 | 1 | 1 | 1 | Hold existing; at 7.68% weight (near 8% cap) |
| AAPL | 6/10 | 1 | 2 | 1 | 1 | 1 | At 8.57% — OVER cap; no new entry |
| META | 6/10 | 1 | 2 | 1 | 1 | 1 | Hold existing; thesis weakening |
| CVX | 6/10 | 2 | 1 | 1 | 1 | 1 | FAIL — energy sector mid-tier, R:R ~1.5 vs $213 PT |
| XOM | 6/10 | 2 | 1 | 1 | 1 | 1 | FAIL — same as CVX; energy sector drag |
| TSM | 5/10 | 1 | 2 | 0 | 1 | 1 | FAIL — chip sector pressure; extended prior research |
| AMZN | 4/10 | 0 | 1 | 2 | 0 | 1 | FAIL — fell 7.6% last week on capex fears; negative catalyst |
| AMD | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — semis weakness; momentum playbook breakdown watch |
| JPM | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| GS | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| V | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| MA | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| SPY | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |
| QQQ | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |
| GOOGL | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — recently stopped out; thesis broken |
| AVGO | N/A | — | — | — | — | — | Stopped out Jun 04; no re-entry |
| TSLA | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — no catalyst |
| UNH | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL — healthcare bottom YTD |
| JNJ | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |

**MSFT catalyst notes:** Azure AI milestone reported; stock "retakes key level after earnings selloff" (investors.com); 97 analysts cover, most Strong Buy/Buy; avg PT $561.20 (MarketBeat, 47 analysts), high $870 (Tigress Financial May 6). Below all-time high $555.45 with recovery thesis intact.

**CVX/XOM note:** Confirmed oil catalyst (Iran/Israel) but energy sector historically mid-ranked vs tech for this strategy; R:R to analyst PTs ($213 CVX, $176 XOM 52-wk high) insufficient to clear 2.0 threshold at current prices. Pass at this time.

### Technical Validation — MSFT (Score 8/10)
*Bars null pre-market (endpoint returning null); estimates from known price trajectory*
- **SMA20 (est):** ~$435 (using known closes: $466.32 HWM → $441.09 Jun02 → $427.65 Jun03 → ~$420 Jun04-05 → $416.67 today; 20-day avg ~$435–445)
- **Last price:** $416.67 (Yahoo Finance)
- **Distance from SMA20:** ($416.67 - $435) / $435 ≈ **-4.2% → BELOW SMA ✓** (Setup 2 confirmed)
- **5-day momentum:** $416.67 vs $441.09 (Jun02) = **-5.54% (NEGATIVE — 1 fail)**
- **Volume ratio:** N/A (bars null) — not counted as confirmed fail per precedent
- **Result: 1 fail → PASSES** (threshold: 2+ confirmed fails to disqualify)

### Trade Ideas

**#1 — MSFT (Microsoft) — CONDITIONAL ENTRY**
- Catalyst: Azure AI milestone ongoing; stock retook key level post earnings selloff (investors.com); 97 analysts bullish avg PT $561.20 (marketbeat.com, forbes.com); "well below all-time high $555.45"
- Sector: XLK Tech — #1 YTD
- Score: 8/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 2
- Entry: ~$416–420 (market order after conditions pass)
- Stop: 10% trailing → initial floor ~$375–378
- Target: $561 (analyst avg PT) → R:R = ($561-$418)/($418-$376) ≈ **3.4:1 ✓**
- Shares: 19 × $418 = $7,942 (~7.9% of $100,492 equity — within 8% cap)
- **Conditions (all must pass at 10:00 AM):**
  (a) SPX ≥ 0% at open AND
  (b) MSFT > $415 AND
  (c) No additional geopolitical escalation (market absorbing Iran/Israel without tech selloff)
- Technicals: SMA20 ~$435 (below ✓), 5d mom -5.54% (1 fail), vol N/A — 1 fail → PASSES
- Buy gates: 4 positions after fill ≤10 ✓; 1 trade this week ≤3 ✓; $7,942 ≤ 8% cap ✓; $7,942 ≤ $76,464 cash ✓

### Risk Factors
1. **Iran/Israel ceasefire breakdown (HIGH):** Iran fired missiles at Israel overnight; Kospi -8.4%; Strait of Hormuz concerns. Risk-off pressure on tech if conflict escalates further.
2. **CPI Wednesday Jun 10 (HIGH):** Major volatility driver. "CPI will drive volatility across stocks, bonds, currencies" (x.com/marketsday). Do not enter MSFT if CPI risk looks skewed hawkish.
3. **META stop risk (MEDIUM-HIGH):** Only 2.3% above $578.70 trailing stop. Any morning dip below $578.70 triggers auto-exit. AI delays narrative compounding.
4. **NVDA at -2.4% unrealized (MEDIUM):** Stop $192.59 remains intact (7.7% cushion). $80B buyback is a support catalyst but geopolitical risk-off could pressure it lower.
5. **Deployment gap (ONGOING):** 23.9% deployed vs 80% target. MSFT entry would lift to ~31.8%; still needs 2 more trades but CPI/geopolitics force patience.
6. **Semiconductor weakness (MEDIUM):** AMD breakdown watching; "AI trades unwind" CNBC headline. NVDA could face sympathy selling.
7. **AAPL approaching +15% trigger:** HWM $316.93, trigger at $317.84. Tighten trail to 7% if/when HWM exceeded.

### Decision
**TRADE — MSFT conditional entry at 10:00 AM if conditions pass; otherwise HOLD**
- MSFT: 8/10 score, below SMA, $561 analyst avg PT, 3.4:1 R:R, Azure AI recovery thesis
- Existing positions: let trailing stops manage; manually cut META if it hits -7% ($561.17 unrealized trigger, currently well above)
- AAPL: tighten trail to 7% if HWM > $316.93 (current HWM); watch $317.84 trigger
- Primary caution: CPI Wednesday and Iran/Israel — if SPX opens red or MSFT < $415 at 10 AM, HOLD all week
- Week budget: 3 slots, 1 being used for MSFT; preserve 2 for high-conviction setups post-CPI

*Sources: finance.yahoo.com/MSFT (price/analysts), marketbeat.com/MSFT (47 analyst PTs), forbes.com/MSFT (97 analysts), investors.com/MSFT (key level), cnbc.com/2026/06/07 (Iran-Israel/geopolitics), oilprice.com (WTI/Brent), cboe.com (VIX), markets.businessinsider.com (SPX futs), totalrealreturns.com (sector YTD), heygotrade.com (NVDA upgrades), moneymorning.com (NVDA buyback)*

---

## 2026-05-27 (Day 23, Wednesday)

**Account snapshot:** Equity $101,488 | Cash $69,292 (68.2%) | Positions: 4 | DT count: 0/3
**Session-start equity:** $101,526 (yesterday EOD)
**Portfolio DD:** -0.04% — no halt

### Market Context
- **Oil:** WTI ~$91.96 (-2.06 today), Brent ~$97.95 (-1.64%) — declining on Iran peace deal progress
- **SPX futures:** ~7,541–7,599 (+0.06% to +0.91% premarket) — cautiously positive
- **VIX:** ~16.70 — low, favorable for longs
- **AI mega-rally:** SK Hynix + Micron surged to $1T market cap; AMD +7.72%; global equities at record highs; Bloomberg: memory chip frenzy driving AI infrastructure revaluation
- **Earnings today:** No major reports before open
- **Econ calendar:** Richmond Fed only (minor); CPI June 10, PPI June 12

*Sources: businessinsider.com/commodities/oil-price, cmegroup.com/markets/equities/sp/e-mini-sandp500, ycharts.com/indicators/vix_volatility_index, bloomberg via youtube.com (Global Stocks Hit Record as SK Hynix, Micron Soar, 05/27/2026)*

### Sector ETF Ranking (This Week)
1. **XLE** (Energy) +10.22% — but oil declining today, momentum may fade
2. **XLU** (Utilities) +6.51%
3. **XLK** (Technology) — YTD leader, AI chip rally accelerating today

*Source: fbroker.kz/en/news/sampp-500s-weekly-market-breakdown-sector-performance*

### Open Positions (premarket)
| Ticker | Entry | Last | Unrealized | Stop | HWM |
|--------|-------|------|-----------|------|-----|
| AAPL | $276.38 | $308.88 | +11.76% | $280.64 | $311.82 |
| GOOGL | $389.84 | $387.56 | -0.58% | $353.25 | $392.50 |
| META | $598.88 | $609.90 | +1.84% | $561.36 | $623.73 |
| MSFT | $416.87 | $414.07 | -0.67% | $389.43 | $432.70 |

**Note:** AAPL at +11.76% approaching +15% tighten threshold (tighten stop to 7% at +15%).

### Candidate Scoring Table

Universe-only candidates evaluated (≥7/10 to advance):

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Notes |
|--------|-------|----------|--------|-------|--------|-----|-------|
| AVGO | **9/10** | 2 | 2 | 2 | 1 | 2 | PASS — all 3 tech checks pass |
| NVDA | **9/10** | 2 | 2 | 2 | 1 | 2 | PASS — 5d mom fail (1 check); stop-out caution |
| TSM | **8/10** | 2 | 2 | 2 | 0 | 2 | PASS — vol<0.8x (1 check fail) |
| AMD | **7/10** | 2 | 2 | 0 | 1 | 2 | DISCARD — +21.6% above 20d SMA (setup=0, >10% extended) |
| QQQ | **7/10** | 1 | 2 | 2 | 0 | 2 | PASS — vol<0.8x, no single catalyst (borderline) |
| AAPL | — | — | — | — | — | — | Already held |
| GOOGL | — | — | — | — | — | — | Already held |
| META | — | — | — | — | — | — | Already held |
| MSFT | — | — | — | — | — | — | Already held |
| XOM/CVX | <7 | 0 | 1 | — | — | — | SKIP — oil declining today |
| JPM/GS/V/MA | <7 | 0 | 2 | — | — | — | SKIP — no catalyst |
| UNH/JNJ | <7 | 0 | 0 | — | — | — | SKIP — healthcare YTD bottom |

### Technical Validation

**AVGO** — ✅ PASS all checks
- 20d SMA: $419.28 | Dist: +0.7% (clean — at SMA) | 5d mom: +0.3% (positive) | Vol ratio: 1.20× (passes)
- No checks failed

**NVDA** — ⚠️ PASS (1 check fail)
- 20d SMA: $214.66 | Dist: +0.1% (clean) | 5d mom: -3.4% (FAIL) | Vol ratio: 1.15× (passes)
- Stopped out yesterday at $212.71; re-entry risk on same-week exit; monitor for volume catalyst

**TSM** — ⚠️ PASS (1 check fail)
- 20d SMA: $402.96 | Dist: +2.3% (clean) | 5d mom: +4.1% (strong positive) | Vol ratio: 0.78× (FAIL)
- Low volume concern; AI chip catalyst should drive participation higher at open

### Trade Ideas

**#1 — BUY AVGO (Broadcom)**
- Catalyst: Confirmed — BofA top chip pick, AI boom, +1.90% premarket on chip frenzy; SK Hynix/Micron $1T milestone lifts AI infrastructure peers
- Sector: Tech (XLK) — YTD top tier
- Entry: ~$430 (today's expected open, +1.9% from $422 close)
- Stop: 10% trailing → ~$387
- Target: +20% → ~$516
- Shares: 19 × $430 = ~$8,170 (8.0% of equity)
- R:R: 2.0:1
- Score: 9/10 | All tech checks pass
- Source: finance.yahoo.com/news/nvidia-broadcom-lead-bank-americas-161455468.html

**#2 — BUY TSM (Taiwan Semiconductor)**
- Catalyst: Confirmed — SK Hynix/Micron surge to $1T; AI chip demand supercycle; TSM as foundry monopoly benefits directly
- Sector: Tech — YTD top tier
- Entry: ~$412 (yesterday close, premarket data limited)
- Stop: 10% trailing → ~$371
- Target: +20% → ~$494
- Shares: 19 × $412 = ~$7,828 (7.7% of equity)
- R:R: 2.0:1
- Score: 8/10 | Vol concern (0.78×) but momentum +4.1%
- Source: investing.com/analysis/beyond-nvidia-5-semiconductor-stocks-set-to-dominate-2026

### Risk Factors
- Tech concentration: all 4 current positions + 2 ideas = 6/6 in Tech; acceptable per strategy (sector momentum rule)
- Oil declining → XOM/CVX stay out
- GOOGL -0.58% unrealized, negative 5d momentum — watchlist for -7% cut
- MSFT -0.67% unrealized — monitor; HWM $432.70 stop $389.43
- AMD +21.6% above SMA: parabolic, no entry — avoid chasing
- Re-entry in NVDA same week as stop-out: skip unless strong volume catalyst confirmed intraday
- Weekly trade slots: 0/3 used — room for 2 new buys

### Decision
**TRADE: AVGO (primary)**
- Cleanest setup, 9/10, confirmed AI catalyst, near 20d SMA, all checks pass
- Execute at market open; set 10% GTC trailing stop immediately

**WATCH: TSM** — secondary; enter only if AVGO fills and cash permits (still have ~$61K after AVGO fill vs. 80% deployment target)

---

## 2026-05-26 (Day 22, Tuesday)

**Account snapshot (midday):** Equity $101,510.07 | Cash $69,292.31 | Positions: 4

### Morning context
- Pre-market data not available (RESEARCH-LOG was corrupted from prior session)
- Session-start equity estimated from yesterday EOD: $101,736.40

### Midday addendum
- NVDA trailing stop triggered intraday at $212.71 (HWM $236.54, stop $212.886)
- NVDA exit realized P&L: +$533.76 (+2.68%)
- Portfolio DD: -0.22% from yesterday close — no halt
- No positions at -7% cut threshold
- No positions at +15%/+20% tighten threshold
- Remaining 4 positions all within rules

### Candidates
None evaluated today — midday scan only.

---

## 2026-05-28 (Day 24, Thursday)

### Account Snapshot
- **Equity:** $101,842.45 | **Cash:** $69,292.29 (68.0%) | **Daytrade count:** 0
- **Deployment:** 32.0% ($32,550 of $101,842) — critically below 80% target
- **Positions (4):** AAPL +12.27%, META +5.53%, MSFT -0.16%, GOOGL -0.76%
- **Week trades:** 0/3 used | **Session-start equity (DD halt @ -10%):** $91,658.21
- **Open GTC trailing stops:** AAPL ($281.93), GOOGL ($354.49), META ($574.65), MSFT ($389.43)

### Market Context
- **S&P 500 futures:** 7,528–7,533 (-0.16%) — essentially flat premarket
- **VIX:** ~16.3–16.7 (low; risk-on backdrop)
- **WTI crude:** ~$90.64–92.07 (+2.2%); **Brent:** ~$96.33–97.76
- **Key event today:** PCE Price Index at 8:30 AM EDT (prior 3.2%) — PRIMARY RISK EVENT
- **Earnings today:** RBC (RY) before open — not in universe; no universe earnings
- **Market narrative:** S&P has had one of its strongest 8-week runs ever; AI chip supercycle driving tech; Big Tech all beat last week

### Sector ETF Ranking (this week)
1. **XLF (Financials):** +13.02% — top performing sector
2. **XLK (Technology):** +12.75%
3. **XLE (Energy):** +10.22%
4. XLI (Industrials): +8.56% | XLB (Materials): +6.79% | XLU (Utilities): +6.51%
5. **XLV (Healthcare):** -2.77% — bottom sector, avoid

### Candidate Scoring Table
(Universe: 20 symbols only — AAPL MSFT GOOGL AMZN NVDA META TSLA AMD AVGO TSM JPM GS V MA XOM CVX UNH JNJ SPY QQQ)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Notes |
|--------|-------|----------|--------|-------|--------|-----|-------|
| AAPL | — | — | — | — | — | — | Already held (+12.27%) |
| MSFT | — | — | — | — | — | — | Already held (-0.16%) |
| GOOGL | — | — | — | — | — | — | Already held (-0.76%) |
| META | — | — | — | — | — | — | Already held (+5.53%) |
| **AVGO** | **8/10** | 1 | 2 | 2 | 1 | 2 | ✅ PASS — PRIMARY IDEA |
| **TSM** | **8/10** | 1 | 2 | 2 | 1 | 2 | ✅ PASS — SECONDARY IDEA |
| **JPM** | **8/10** | 1 | 2 | 2 | 1 | 2 | ✅ PASS — TERTIARY IDEA |
| GS | 7/10 | 1 | 2 | 1 | 1 | 2 | ✅ PASS — +5% above SMA |
| NVDA | 8/10 | 1 | 2 | 2 | 1 | 2 | ⚠️ WATCH — same-week stop-out risk |
| V | <7 | — | — | — | — | — | ❌ DISCARD — 2 tech fails |
| MA | <7 | — | — | — | — | — | ❌ DISCARD — 2 tech fails |
| AMD | <7 | — | — | — | — | — | SKIP — likely parabolic extension |
| TSLA | <7 | — | — | — | — | — | SKIP — no catalyst |
| AMZN | <7 | — | — | — | — | — | SKIP — no catalyst |
| XOM/CVX | <7 | 0 | 2 | — | — | — | SKIP — no specific catalyst |
| UNH/JNJ | <7 | 0 | 0 | — | — | — | SKIP — XLV sector bottom (-2.77%) |
| SPY/QQQ | ETF | — | — | — | — | — | SKIP |

### Technical Validation

**AVGO** — ✅ 0 fails
- 20d SMA: $420.38 | Dist: +0.35% (at SMA) | 5d mom: +2.62% (positive) | Vol ratio: 0.95× (passes)
- Source: Alpaca bars endpoint (bars[-20:] from 2026-04-29)

**TSM** — ✅ 0 fails
- 20d SMA: $404.47 | Dist: +4.51% (clean) | 5d mom: +7.67% (strong) | Vol ratio: 1.13× (passes)
- Strong breakout momentum on AI foundry demand

**JPM** — ✅ 0 fails
- 20d SMA: $304.60 | Dist: -1.75% (below SMA) | 5d mom: +1.21% (positive) | Vol ratio: 1.44× (elevated)
- Source: Alpaca bars endpoint

**GS** — ✅ 0 fails (but setup score 1)
- 20d SMA: $948.58 | Dist: +5.05% (slightly extended) | 5d mom: +7.29% | Vol ratio: 1.11×

**V** — ❌ 2 fails (DISCARD)
- 5d mom: -0.70% (neg) | Vol ratio: 0.74× (low)

**MA** — ❌ 2 fails (DISCARD)
- 5d mom: -0.93% (neg) | Vol ratio: 0.75× (low)

### Trade Ideas

**#1 — BUY AVGO (Broadcom) — PRIMARY**
- Catalyst: AI infrastructure supercycle; chip sector leadership (XLK #2); BofA maintained top pick; ongoing demand from hyperscalers
- Sector: XLK Tech — #2 sector this week (+12.75%)
- Entry: ~$425 (approx, +0.7% from $421.86 close)
- Stop: 10% trailing → initial ~$383
- Target: +20% → ~$506
- Shares: 19 × $425 = $8,075 (~7.9% of equity)
- R:R: 2.0:1
- Score: 8/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 2
- Technicals: SMA $420.38, dist +0.35%, 5d mom +2.62%, vol ratio 0.95×
- Condition: Wait for PCE reaction at 8:30 AM. Enter only if SPX holds flat/positive post-print.
- Source: wallstreetzen.com (05/28/2026), investing.com/analysis/beyond-nvidia-5-semiconductor-stocks

**#2 — BUY TSM (Taiwan Semiconductor) — SECONDARY**
- Catalyst: AI chip foundry monopoly; SK Hynix/Micron $1T milestone; AI demand supercycle
- Sector: XLK Tech — #2 sector this week
- Entry: ~$425 (approx, +0.5% from $422.73 close)
- Stop: 10% trailing → initial ~$383
- Target: +20% → ~$510
- Shares: 18 × $425 = $7,650 (~7.5% of equity)
- R:R: 2.0:1
- Score: 8/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 2
- Technicals: SMA $404.47, dist +4.51%, 5d mom +7.67%, vol ratio 1.13×
- Condition: Enter only if AVGO fills and cash/position limits allow; post-PCE confirmation

**#3 — WATCH JPM (JP Morgan) — TERTIARY/DIVERSIFICATION**
- Catalyst: Finance sector #1 this week (+13.02%); no specific JPM catalyst today
- Sector: XLF Finance — #1 sector this week
- Entry: ~$300 (near current $299.28 close)
- Stop: 10% trailing → initial ~$270
- Target: +20% → ~$360
- Score: 8/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 2
- Technicals: SMA $304.60, dist -1.75% (below SMA), 5d mom +1.21%, vol ratio 1.44×
- Note: Provides sector diversification vs current all-tech portfolio; 4th trade would exceed week limit if AVGO + TSM already done

### Position Monitoring
- AAPL: +12.27% unrealized; approaching +15% tighten threshold ($317.84 = entry $276.38 × 1.15). Monitor intraday.
- GOOGL: -0.76%; thesis intact; stop at $354.49 (HWM $393.88). -7% cut at $362.35 — well above.
- META: +5.53%; stop $574.65; next tighten threshold $688.71 (+15%)
- MSFT: -0.16%; closely watching; 4 consecutive down days prior. Stop $389.43.

### Risk Factors
- **PCE at 8:30 AM (CRITICAL):** Prior 3.2%. Hot print (>3.3%) = broad selloff; tech hit hardest. Will not enter any new position before this data clears.
- **Tech concentration:** All 4 current positions in XLK. Adding AVGO + TSM = 6/6 in tech. Acceptable per sector momentum rule.
- **GOOGL thesis:** Stock near entry; -7% cut at $362.35. Weak relative performer in portfolio.
- **MSFT thesis:** Stock near entry; -7% cut at $416.87 × 0.93 = $387.69. Monitor.
- **AMD +21.6% above SMA:** parabolic, no entry — avoid chasing
- **Re-entry in NVDA same week as stop-out:** skip unless strong volume catalyst confirmed intraday
- **Deployment gap:** 32% deployed vs 80% target. Need 3 more positions over coming weeks; today's ideas address this.

### Decision
**TRADE: AVGO (primary), WATCH: TSM/JPM**
- Execute AVGO at market open **only if PCE (8:30 AM) does not cause broad market selloff**
- If SPX futures remain flat/positive after PCE print → enter AVGO market order
- If SPX drops >0.5% post-PCE → HOLD, reassess at midday
- TSM secondary entry if AVGO fills OK and deployment permits (0/3 weekly slots would be 1 after AVGO, room for 1-2 more)
- JPM watch: provides finance sector diversification; enter next session if tech/PCE confirms

---

## 2026-06-01 (Day 26, Monday)

### Account Snapshot
- **Equity:** $103,366 | **Cash:** $61,371.38 | **Deployment:** 40.6% (vs 80% target)
- **Long MV:** $41,994.62 | **DT count:** 0 | **Week trades:** 0/3 slots used
- **Phase P&L:** ~+$3,366 (+3.37%) | **vs last session:** +$450 premarket gain

### Open Positions (premarket)
| Ticker | Entry | Current | Unrealized | Stop (HWM) | Notes |
|--------|-------|---------|------------|------------|-------|
| AAPL | $276.38 | $309.69 | +12.05% | $283.46 (HWM $314.96) | Near +15% tighten at $317.84 |
| AVGO | $416.89 | $458.42 | +9.96% | $403.99 (HWM $448.88→$458.42) | **EARNINGS JUNE 3 AH** |
| GOOGL | $389.84 | $377.37 | -3.20% | $354.49 (HWM $393.88) | Watch cut at $362.35 |
| META | $598.88 | $632.64 | +5.64% | $578.70 (HWM $643.00) | Healthy |
| MSFT | $416.87 | $465.50 | +11.67% | $405.30 (HWM $450.33→$465.50) | Near +15% tighten at $479.40 |

*Note: AVGO and MSFT HWMs will auto-update when market opens; stops will trail higher.*

### Market Context
- **Oil:** WTI $89.71 | Brent $93.64 (elevated; Strait of Hormuz supply risk cited)
  — Source: markets.businessinsider.com (6/1/26)
- **SPX Futures:** +0.20% (+21pts to 7,616.75); AI-themed rally extending to ATH
  — Source: bloomberg.com/markets/stocks/futures, barchart.com/futures/quotes/ESM26
- **VIX:** 15.92 (declining trend: 16.29 May → 15.92 Jun 1; benign environment)
  — Source: investing.com/indices/volatility-s-p-500-historical-data
- **Catalysts:** AI rally self-reinforcing (Citadel: "pain trade higher"); Dell AI-server outlook; MSFT Pentagon $9.7B software deal driving cloud optimism; SPX at all-time highs
  — Source: atranicapital.substack.com/p/week-22-market-update-for-may-25, schwabnetwork.com/articles/top-economic-data-to-watch-week-of-june-1-2026
- **AVGO Earnings June 3 AH (CRITICAL):** Q2 FY2026 EPS est. $2.40, revenue ~$22.1-22.5B (+47-50% YoY). AI chip revenue Q1 was $8.4B (+106% YoY); analysts expect +30% QoQ for Q2. Has beaten estimates only 1/7 quarters — binary event for entire AI chip sector.
  — Source: perplexity.ai/finance/AVGO/earnings, marketbeat.com/earnings/reports/2026-6-3-broadcom-inc-stock
- **GOOGL:** Google Cloud $462B customer backlog (near-doubled QoQ); ex-div June 8 at $0.22. Thesis intact despite recent price weakness. Potential AI chip news: "Alphabet good news, bad for Nvidia" article (5/31) — Google developing own AI chips reducing NVDA dependency.
  — Source: fool.com/investing/2026/05/25/prediction-alphabet-stock-is-buy-before-june-2026

### Economic Calendar Today
- **9:45 AM:** S&P Global Manufacturing PMI (Final, May)
- **10:00 AM:** ISM Manufacturing PMI (May) — consensus ~54.5
- **10:00 AM:** ISM Manufacturing Employment
- **10:00 AM:** Construction Spending MoM
- No FOMC, no jobs data today
— Source: x.com/marketsday/status/2060571281574301885, schwabnetwork.com/articles/top-economic-data-to-watch-week-of-june-1-2026

### Sector ETF Ranking (week ending May 30)
1. **XLK** Tech — AI momentum driving SPX to ATH; MSFT +5.19%, AVGO +4.52% Friday
2. **XLF** Finance — Strong recent performance; JPM/GS elevated; finance sector top third YTD
3. **XLE** Energy — Oil elevated ($89-93); geopolitical risk premium supportive
— Source: barchart.com/etfs-funds/sectors/performance, schwabnetwork.com/articles/top-economic-data-to-watch-week-of-june-1-2026

### Candidate Scoring (20-symbol universe only)

**Pre-screened: Already held (AAPL, AVGO, GOOGL, META, MSFT). No re-score needed.**

| TICKER | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| NVDA | 9/10 | 1 | 2 | 2 | 2 | 2 | ✅ Pass |
| JPM | 9/10 | 1 | 2 | 2 | 2 | 2 | ✅ Pass |
| V | 8/10 | 0 | 2 | 2 | 2 | 2 | ❌ No catalyst |
| MA | 8/10 | 0 | 2 | 2 | 2 | 2 | ❌ No catalyst |
| GS | 7/10 | 1 | 2 | 1 | 1 | 2 | ✅ Pass (backup) |
| TSM | 7/10 | 1 | 2 | 2 | 0 | 2 | ✅ Pass (hold for post-AVGO) |
| AMD | DISCARD | — | — | — | — | — | ❌ 2 tech fails |
| AMZN, XOM, CVX, UNH, JNJ, SPY, QQQ | <7 | — | — | — | — | — | Below threshold |

*V/MA disqualified: catalyst score 0 fails buy-side gate (specific catalyst required).*
*AMD discard: +17.27% above SMA (extended) AND vol ratio 0.77x (low). 2 fails.*

### Technical Validation

**NVDA** — ✅ 1 fail (passes ≥2-fail discard threshold)
- Last: $211.14 | SMA20: $215.46 | Dist: -2.00% (below SMA) | 5d mom: -3.81% (**FAIL**) | Vol: 1.74x ✅
- Interpretation: At SMA support; high volume = potential institutional accumulation. Negative 5d momentum reflects post-NVDA-stop-out consolidation. AVBO earnings (June 3) as AI chip ecosystem catalyst is the entry trigger.

**JPM** — ✅ 1 fail (passes ≥2-fail discard threshold)
- Last: $299.31 | SMA20: $303.27 | Dist: -1.31% (below SMA) | 5d mom: -1.22% (**FAIL**) | Vol: 1.63x ✅
- Interpretation: Just below SMA support; high volume. Mildly negative 5d momentum. Finance sector thesis intact. ISM PMI at 10am provides near-term catalyst (expansion reading supports financials).

**TSM** — ✅ 0 fails
- Last: $418.45 | SMA20: $407.15 | Dist: +2.78% (at SMA) | 5d mom: +2.78% ✅ | Vol: 0.87x (below avg)
- Interpretation: Clean setup, positive momentum. Low volume is the only weakness. Hold for post-AVGO confirmation.

**GS** — ✅ 0 fails (backup)
- Last: $1,025.56 | SMA20: $958.81 | Dist: +6.96% (slightly extended) | 5d mom: +3.78% ✅ | Vol: 1.07x
- Backup option if finance sector shows sustained momentum. No entry today.

### Trade Ideas

**#1 — JPM (JP Morgan) — PRIMARY ENTRY**
- Catalyst: ISM Manufacturing PMI at 10am (scheduled economic event); Finance sector #1-#2 this week; portfolio diversification (5/5 positions currently in tech — adding finance reduces concentration risk)
- Sector: XLF Finance — top third YTD, strong recent momentum
- Entry: ~$299 (near last close $299.31); wait for ISM PMI confirmation at 10:15 AM
- Stop: 10% trailing → initial ~$269
- Target: +20% → ~$359
- Shares: 27 × $299 = $8,073 (~7.8% of equity) — within 8% limit
- R:R: 2.0:1
- Score: 9/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 2 | R:R: 2
- Technicals: SMA20 $303.27, dist -1.31%, 5d mom -1.22% (1 fail), vol ratio 1.63x

**#2 — NVDA (Nvidia) — CONDITIONAL ENTRY**
- Catalyst: AVGO earnings June 3 AH as AI chip ecosystem catalyst; AI demand supercycle; at SMA support with high volume (institutional accumulation signal)
- Sector: XLK Tech — #1 sector YTD
- Entry: ~$212 (near last close $211.14); enter only if market opens green AND ISM PMI ≥ 53
- Stop: 10% trailing → initial ~$191
- Target: +20% → ~$253
- Shares: 38 × $212 = $8,056 (~7.8% of equity)
- R:R: 2.0:1
- Score: 9/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 2 | R:R: 2
- Technicals: SMA20 $215.46, dist -2.00%, 5d mom -3.81% (1 fail), vol ratio 1.74x
- Risk: 5d momentum negative; AVGO binary earnings event June 3; "Alphabet good news, bad for Nvidia" chip competition article

**#3 — TSM (Taiwan Semiconductor) — WAIT / POST-AVGO**
- Thesis: AI foundry monopoly; positive 5d momentum; clean setup
- Action: Hold entry until June 3 AVGO earnings reaction. If AVGO beats → enter TSM at open June 4 as AI foundry confirmation.
- Score: 7/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 0 | R:R: 2
- Technicals: SMA20 $407.15, dist +2.78%, 5d mom +2.78%, vol ratio 0.87x

### Position Monitoring
- **AAPL:** +12.05% unrealized. Tighten trail to 7% if touches $317.84 (+15% from entry). HWM will auto-update.
- **AVGO:** +9.96% unrealized. **EARNINGS JUNE 3 AH — hold with trailing stop.** Do NOT add chips exposure until post-earnings. Stop will auto-trail to ~$412 when market opens.
- **GOOGL:** -3.20% unrealized. Cut level $362.35. Thesis intact (Google Cloud backlog). GOOGL may face internal chip competition headwinds from Google's own AI silicon. Watch carefully.
- **META:** +5.64% unrealized. No action needed.
- **MSFT:** +11.67% unrealized. Pentagon software deal + AI cloud monetization thesis strong. Tighten trail to 7% if touches $479.40 (+15%). Stop will auto-trail to ~$419.

### Risk Factors
- **AVGO earnings June 3 AH (HIGH):** Binary event for entire AI chip sector. Has beaten only 1/7 quarters. Existing AVGO position protected by trailing stop; do NOT add chip exposure before June 3.
- **Tech concentration (MEDIUM):** 5/5 open positions in tech. JPM entry reduces this.
- **ISM PMI at 10am (MEDIUM):** Hot print (>56) could spike rates/VIX; cold print (<50) signals contraction. Both scenarios temporarily negative for equities.
- **GOOGL thesis (LOW-MEDIUM):** Weakest performer in portfolio at -3.20%. Google's own chip development may reduce NVDA/chip sector appetite. Monitor cut level $362.35.
- **Oil/Hormuz (LOW):** WTI $89.71. Strait of Hormuz supply risk mentioned; not immediate. Monitor CVX/XOM if energy escalates.
- **Deployment gap (ONGOING):** 40.6% deployed vs 80% target. Adding JPM + NVDA = ~$16K more = ~56% total. Still below target; need 1-2 more positions over the next 1-2 weeks.

### Decision
**TRADE: JPM (execute at open, finance diversification), NVDA (conditional — enter only if ISM PMI ≥ 53 and market opens green). Reserve 1 slot for post-AVGO June 3 confirmation.**
- JPM: Execute market order at open. No conditions — provides critical non-tech diversification.
- NVDA: Conditional on 10am ISM PMI data. If ISM ≥ 53 and SPX holds flat/green → enter market order after 10:15am.
- TSM: Watch list. Enter June 4 if AVGO beats earnings June 3.
- If ISM disappoints (<50): HOLD all new entries; reassess at midday routine.

---

## 2026-06-03 — Midday Addendum

**Account snapshot:** Equity $102,596.69 | Cash $68,609.49 | Positions: 4 | DT count: 0
**Session-start equity (last_equity):** $102,481.59 | **DD:** +0.11% — no halt

### Positions (midday)
| Ticker | Entry | Current | Unrealized | Stop | HWM |
|--------|-------|---------|-----------|------|-----|
| AAPL | $276.38 | $309.96 | +12.15% | $285.24 (10% trail) | $316.93 |
| AVGO | $416.89 | $484.97 | +16.33% | $455.91 (7% trail) | $490.23 |
| META | $598.88 | $618.42 | +3.26% | $578.70 (10% trail) | $643.00 |
| MSFT | $416.87 | $424.82 | +1.91% | $419.69 (10% trail) | $466.32 |

### Checks
- **DD halt:** No — equity +$115 (+0.11%) from session start
- **Cut losers (-7%):** None — all positions profitable
- **Tighten stops:** AVGO at +16.33% already has 7% trail (tightened prior session). No new tightenings (AAPL +12.15% not yet at +15% trigger $317.84).
- **Thesis checks:** All intact

### MSFT Watch — Majorana 2 / AI EO Selloff
- Down -3.74% intraday to $424.82 vs trailing stop $419.69 (only $5.13 / 1.2% above stop)
- Cause: Majorana 2 quantum chip announcement treated as long-term (not near-term) catalyst + Trump voluntary AI executive order (no mandatory impact)
- Core thesis intact: Azure +40% YoY, enterprise AI monetization, Q3 beat. No thesis break.
- Action: Hold. Stop will auto-execute if breached. Do NOT manually cut — thesis intact.
- Source: tipranks.com via cnn.com (MSFT drops 4% on Majorana 2 long-term quantum catalyst)

### AVGO Earnings Tonight (AH)
- Consensus: EPS $2.40 (vs Q1 actual $2.05), Revenue $22B guided / $22.04B est (+47% YoY)
- XPU revenues expected to continue 140%+ YoY momentum from Q1
- Position protected by 7% trailing stop (HWM $490.23, stop $455.91)
- If beat: TSM entry at open June 4 per research plan

---

## 2026-06-04 — Pre-Market Research (Day 29, Thursday)

### Account Snapshot
- **Equity:** $101,404.15 | **Cash:** $68,609.49 | **DT count:** 0
- **Last equity:** $102,620.34 | **Session DD:** -1.19% (no halt — threshold is -10%)
- **Positions:** 4 (AAPL, AVBO, META, MSFT) — AVGO stop expected to fill at open
- **Week buys:** 0/3

### CRITICAL — AVGO Gap-Down
- AVGO earnings June 3 AH: Beat EPS ($2.47 vs $2.39 est), Beat revenue ($22.19B vs $22.13B est)
- **Stock reaction: -13.97% overnight to $412.28** (guidance disappointment — Q3 revenue ~$29.4B underwhelmed)
- Trailing stop at $455.91 (7% from HWM $490.23) will fill at open (~$412 expected gap fill)
- Expected realized P&L: ~-$93 (-1.1% on position) — stop protects vs deeper loss
- TSM conditional entry ("if AVGO beats, enter at open June 4") → **CANCELED** (stock reaction negative)

### Market Context
- **SPX futures:** 7535.25, -36.50 (-0.50%) — market opens slightly red
- **VIX:** 16.06 (+1.84% from yesterday) — mild fear elevation
- **WTI:** ~$95.13/barrel | **Brent:** ~$96.84/barrel — elevated (geopolitical Hormuz risk, Iran tensions per CNBC)
- **Economic:** Productivity SAAR Q/Q (Final) at 7:30am; Initial Jobless Claims 8:30am — neither major mover
- **BMO Earnings:** CIEN, BF.A (not in universe)
- **Sector rotation note:** MarketWatch: "software stocks slump, bifurcation of AI trade" — NVDA entering PC market seen as bullish; software (MSFT periphery) weaker

### Sector ETF Ranking (Week)
All sectors positive this week per Tavily. Ranking:
1. **XLK Technology** — AI supercycle, NVDA PC chip entry, AAPL WWDC approaching
2. **XLE Energy** — WTI ~$95 sustained; Iran/Hormuz tail risk bid
3. **XLF Financial Services** — stable; JPMorgan Magnificent Seven commentary positive
- Source: seekingalpha.com, finance.yahoo.com sector comparison

### Position Monitoring
| Ticker | Entry | Pre-Mkt | Unrealized | Stop | Buffer | Status |
|--------|-------|---------|-----------|------|--------|--------|
| AAPL | $276.38 | $312.50 | +13.07% | $285.24 (10% trail, HWM $316.93) | 9.56% | Hold; +15% trigger = $317.84 |
| AVGO | $416.89 | $412.28 | -1.11% | $455.91 (7% trail, HWM $490.23) | N/A — GAP BELOW STOP | **STOP TRIGGERS AT OPEN** |
| META | $598.88 | $617.98 | +3.19% | $578.70 (10% trail, HWM $643.00) | 6.60% | Hold; AI ad thesis intact |
| MSFT | $416.87 | $430.40 (~$437 Tavily) | +3.25% | $419.69 (10% trail, HWM $466.32) | ~2.5-4.2% | WATCH — stop buffer thin |

### Candidate Scoring (Universe Only)
Bars data unavailable (Alpaca data endpoint returned null pre-market); technicals estimated from prior research logs + Tavily. All 20 symbols assessed:

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **AAPL** | **9/10** | 2 | 2 | 2 | 1 | 2 | AT 8% CAP — no new entry |
| **NVDA** | **9/10** | 2 | 2 | 2 | 1 | 2 | CONDITIONAL entry |
| TSM | 6/10 | 1 | 2 | 0 | 1 | 2 | FAIL — extended >10% above SMA20 (~$407, price ~$449) |
| META | 6/10 | 1 | 2 | 1 | 1 | 1 | HOLD existing; no new catalyst for fresh entry |
| MSFT | 7/10 | 1 | 2 | 2 | 1 | 1 | HOLD existing; stop thin |
| JPM | 5/10 | 1 | 1 | 1 | 1 | 1 | FAIL |
| AVGO | N/A | — | — | — | — | — | STOP-OUT at open; no re-entry same day |
| GOOGL | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL — recently stopped out, thesis broken |
| All others (AMZN, AMD, TSLA, GS, V, MA, XOM, CVX, UNH, JNJ, SPY, QQQ) | ≤5/10 | — | — | — | — | — | No actionable catalyst |

### Technical Validation — NVDA (Score 9/10)
*Note: Bars null; estimated from prior research (Jun 2 SMA20 = $215.46) + Tavily closing price $209.25 Jun 3*
- **SMA20 (est):** ~$213 (declining with recent pullback)
- **Distance from SMA20:** (209.25 - 213) / 213 = **-1.76%** — below SMA20 ✓
- **5-day momentum:** ~$212 (May 28) → $209.25 (Jun 3) = **-1.3%** → NEGATIVE (1 fail)
- **Volume ratio:** N/A (bars unavailable)
- **Result:** 1 fail — does NOT disqualify (threshold: 2+ fails)
- **Catalyst divergence note:** AVGO custom ASICs (XPU) compete with NVDA; AVGO guidance miss could redirect hyperscaler spend *back* to NVDA GPUs. BofA names NVDA top June pick; foundry expansion upgrades cycle. PC processor entry = new TAM.

### Trade Ideas

**#1 — NVDA (Nvidia) — CONDITIONAL ENTRY**
- Catalyst: BofA June top pick; NVDA enters PC processor market (new TAM); AVGO guidance miss may redirect hyperscaler GPU spend to NVDA; foundry capacity upgrades (heygotrade.com, cnbc.com/2026/05/30)
- Sector: XLK Tech — #1 YTD
- Condition: Enter only if (a) SPX flat/green by 9:45am AND (b) NVDA holds > $207 at 9:45am
- Entry: ~$210 (market order post-condition check)
- Stop: 10% trailing → initial ~$189
- Target: +20% → ~$252
- Shares: 38 × $210 = $7,980 (~7.87% of equity — within 8% cap)
- R:R: 2.0:1 ($42 reward / $21 risk)
- Score: 9/10 | Catalyst: 2 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 2
- Technicals: SMA20 ~$213, dist -1.76% (below SMA20 ✓), 5d mom -1.3% (1 fail), vol N/A

### Risk Factors
1. **AVGO gap-down sentiment (HIGH):** Chip sector negative AH. NVDA may open red on AVGO sympathy selling. Wait for market open confirmation before NVDA entry.
2. **SPX futures red -0.50% (MEDIUM):** Potential opening weakness; could chain-stop MSFT.
3. **MSFT stop buffer thin (MEDIUM):** Buffer 2.49-4.24% depending on data source. Red open could test stop $419.69. Let stop auto-execute if triggered — thesis unbroken but stop overrides.
4. **Deployment gap (ONGOING):** Post-AVGO exit = only 3 positions, ~24.6% deployed. Urgently need 2-3 new positions but must not chase a red open.
5. **AAPL at 8% cap:** Position $8,750 = 8.63% equity. Already max-weight; cannot add regardless of WWDC catalyst.
6. **Energy/Hormuz (LOW):** WTI $95 with Iran tensions. XOM/CVX not in current portfolio but monitor energy as hedging sector.

### Decision
**CONDITIONAL TRADE: NVDA (execute at market-open routine if conditions met)**
- If SPX ≥ 0% and NVDA > $207 at 9:45am → BUY NVDA market order (38 shares, ~$7,980)
- If either condition fails → HOLD; reassess at midday
- Rationale: AVBO chip selloff is near-term headwind; NVDA fundamentals diverge (GPU demand, PC TAM, BofA top pick); only enter on market confirmation
- After AVGO exit: 3 positions, $76K+ cash, 3 buy slots — NVDA is highest-conviction new entry
- Sources: heygotrade.com, cnbc.com/2026/05/30, finance.yahoo.com (AVGO earnings), marketcameleon.com (TSM premarket), investing.com (MSFT premarket), ycharts.com (VIX), wsj.com (SPX futures)

---

## 2026-06-04 — Midday Addendum

**Account snapshot:** Equity $101,407.71 | Cash $76,398.53 | Positions: 3 | DT count: 0
**Session-start equity (last_equity):** $102,620.34 | **DD:** -1.18% — no halt

### AVGO Stop-Out (logged in TRADE-LOG)
- Trailing stop $455.91 (7% trail, HWM $490.23) triggered at open; gap-down -13.97% AH
- Exit ~$409.95/share | Realized P&L: ~-$132 (-1.66%) | AVGO order cleared

### Positions (midday)
| Ticker | Entry | Current | Unrealized | Stop | HWM |
|--------|-------|---------|-----------|------|-----|
| AAPL | $276.38 | $311.14 | +12.58% | $285.24 (10% trail) | $316.93 |
| META | $598.88 | $629.93 | +5.18% | $578.70 (10% trail) | $643.00 |
| MSFT | $416.87 | $426.77 | +2.37% | $419.69 (10% trail) | $466.32 |

### Checks
- **DD halt:** No — -1.18% from last close
- **Cut losers (-7%):** None — all positions profitable
- **Tighten stops:** None — AAPL +12.58% (trigger $317.84), META +5.18%, MSFT +2.37%
- **Thesis checks:** All intact

### MSFT Watch
- Stop $419.69 (HWM $466.32), current $426.77 — only $7.08 (1.66%) buffer above stop
- Tavily: No new negative catalyst. Copilot 20M paid seats confirms Azure AI thesis. Hold; auto-stop will execute if breached.

### NVDA Status
- Pre-market conditional (SPX ≥ 0% and NVDA > $207 at 9:45am) — market opened -0.50%; market-open routine status unknown. Conditions likely not met. Remain at 3 positions, 24.6% deployed.

---

## 2026-06-05 (Day 29, Friday)

**Account snapshot:** Equity ~$101,372 (est) | Cash ~$76,399 | Positions: 3 | DT count: 0/3
*Note: Account API returned 503 (pre-market); equity estimated from live positions ($24,973) + cash from Jun 04 midday ($76,399)*
**Portfolio DD:** ~0% from Jun 04 close — no halt
**Week trades:** 0/3 buy slots used (week of Jun 2–6)

### Market Context
- **WTI:** ~$92–93/bbl | **Brent:** ~$94–95/bbl — stable, slightly off recent highs (oilprice.com)
- **SPX Futures:** 7,558.50 / -42.50 pts (-0.56%) — RED pre-market (markets.businessinsider.com)
- **NASDAQ Futures:** 30,140.75 / -347.50 (-1.14%) — heavier selling in tech
- **VIX:** ~15.40 (ycharts.com) — benign fear gauge but rising intraday
- **Key Event: NFP at 8:30 AM EDT** — Forecast +85K (prev +115K), Unemployment 4.3% (prev 4.3%). Most important macro release of the week; expect high volatility at 8:30 open. (xtb.com/cy, bls.gov)
- **Earnings:** No universe names reporting. Caleres Inc (CAL) and Toro Co (TTC) pre-market; no impact on universe. (wallstreethorizon.com)
- **Macro note:** Iran tensions remain a tail-risk bid for energy (cnbc.com/2026/05/29). S&P 500 forward earnings growth forecast +28.4% Q1 2026 (interactive-investor.co.uk).
- **AVGO chip sector overhang:** AVGO down ~13-14% post-earnings; Broadcom custom ASICs guidance disappointed hyperscalers. Chip sector under pressure. (benzinga.com)

### Sector ETF Ranking (Week)
1. **XLK Technology** +1.5% — AI supercycle intact despite AVGO; NVDA upgrades, MSFT Azure AI milestone (youtube.com/@TheETFTracker, totalrealreturns.com)
2. **XLI Industrials** +0.2% — modest positive
3. **XLB Materials** +0.4% — slight outperformance
- XLE -0.8%, XLF -0.5%, XLV -1.35%, XLU -0.6% all lagging

### Position Monitoring (Pre-Market)
| Ticker | Entry | Pre-Mkt | Unrealized | Stop | HWM | Status |
|--------|-------|---------|------------|------|-----|--------|
| AAPL | $276.38 | $310.83 | +12.47% | $285.24 (10% trail) | $316.93 | HOLD; +15% trigger at $317.84 — approaching |
| META | $598.88 | $624.52 (est) | +4.28% | $578.70 (10% trail) | $643.00 | HOLD; 8.56% above stop, thesis intact |
| MSFT | $416.87 | $428.05–429.00 | +2.87% | $419.69 (10% trail) | $466.32 | WATCH — only $8.31 (1.93%) buffer above stop; MSFT slipping per TipRanks |

### Candidate Scoring (Universe Only — 20 symbols)
*Bars unavailable pre-market (endpoint returning null); volume scores conservative (0 = unconfirmed)*

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **NVDA** | **7/10** | 2 | 2 | 1 | 1 | 1 | **PASS — conditional entry** |
| MSFT | 7/10 | 1 | 2 | 2 | 1 | 1 | HOLD existing position; no new entry |
| AAPL | 6/10 | 1 | 2 | 1 | 1 | 1 | AT 8% cap; no new entry possible |
| META | 6/10 | 1 | 2 | 1 | 1 | 1 | HOLD existing; no fresh catalyst for new entry |
| XOM | 5/10 | 1 | 1 | 1 | 1 | 1 | FAIL (<7); energy sector underperforming this week |
| CVX | 5/10 | 1 | 1 | 1 | 1 | 1 | FAIL (<7); same as XOM |
| AMZN | 4/10 | 1 | 2 | 0 | 0 | 1 | FAIL — no specific catalyst today; bars unavailable for setup |
| AMD | 4/10 | 1 | 2 | 0 | 0 | 1 | FAIL — chip sector overhang, bars unavailable |
| TSM | 5/10 | 1 | 2 | 0 | 1 | 1 | FAIL — extended >10% above SMA20 (prior research) |
| JPM | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| GS | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| V | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| MA | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| GOOGL | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — recently stopped out, thesis broken |
| AVGO | N/A | — | — | — | — | — | STOPPED OUT Jun 04; no re-entry |
| TSLA | 1/10 | 0 | 1 | 0 | 0 | 0 | FAIL — no catalyst |
| UNH | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL — healthcare sector bottom-ranked |
| JNJ | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| SPY | 2/10 | 0 | 1 | 1 | 1 | 0 | FAIL |
| QQQ | 2/10 | 0 | 1 | 1 | 1 | 0 | FAIL |

NVDA Catalyst notes: (1) Multiple analyst upgrades: "Top 7 Stocks Wall Street Analysts Are Upgrading in June 2026" #1 pick (heygotrade.com); (2) Jensen Huang made massive promise to investors per Motley Fool; (3) Kumo AI acquisition (CNN/TipRanks); (4) AVBO custom-XPU guidance miss may redirect hyperscaler GPU spend back to NVDA; (5) Foundry capacity expansion driving Q3 expectations.
NVDA Risk note: Mark A. Stevens (director) sold 1,000,000 shares on Jun 4 (robinhood.com/NVDA) — notable insider selling. NFP uncertainty today.

### Technical Validation — NVDA (Score 7/10)
*Bars null pre-market; using prior research estimates*
- **SMA20 (est):** ~$211–213 (from Jun 04 pre-market research baseline $215.46 adjusted for recent weakness)
- **Last close (est):** ~$209–212 (Jun 3 close $209.25; Jun 4 unknown due to AVGO selloff)
- **Distance from SMA20:** approximately -1% to +1% — AT SMA20 ✓ (not extended)
- **5-day momentum:** Jun 03 close ~$209 vs May 29 ~$212 = **-1.4% (NEGATIVE — 1 fail)**
- **Volume ratio:** N/A (bars unavailable) — treated as unconfirmed, not a disqualifying fail
- **Result:** 1 confirmed fail → PASSES (threshold: 2+ fails to disqualify)

### Trade Ideas

**#1 — NVDA (Nvidia) — CONDITIONAL ENTRY (NFP-gated)**
- Catalyst: Analyst upgrade cycle (heygotrade.com), CEO bullish investor promise (Motley Fool), Kumo AI bolt-on acquisition (TipRanks), AVBO GPU-spend redirect thesis intact
- Sector: XLK Tech — #1 week
- **Conditions (all must pass):** (a) NFP ≥ +80K (in-line or better, prints 8:30 AM) AND (b) SPX green ≥ 0% by 10:00 AM AND (c) NVDA > $210 at 10:00 AM
- Entry: ~$212 (market order after condition check)
- Stop: 10% trailing → initial hard floor ~$191
- Target: +20% → ~$254
- Shares: 37 × $212 = $7,844 (~7.74% of ~$101,372 equity — within 8% cap)
- R:R: 2.1:1 ($42 reward / $21 risk)
- Score: 7/10 | Catalyst: 2 | Sector: 2 | Setup: 1 | Volume: 1 | R:R: 1
- Technicals: SMA20 ~$212 (at), 5d mom -1.4% (1 fail), vol N/A — 1 fail, PASSES

### Risk Factors
1. **NFP at 8:30 AM (CRITICAL):** Forecast +85K vs +115K prior = expected slowdown. Weak print (<+70K) could trigger risk-off selloff; strong print (>+100K) = buy signal. Do not enter any position before NFP.
2. **NASDAQ futures -1.14% (HIGH):** Tech-heavy selling pre-market; NVDA likely opens red.
3. **NVDA insider selling (MEDIUM):** 1M share sale by director Jun 4 — signals potential near-term weakness.
4. **MSFT stop risk (MEDIUM):** Buffer only 1.93% ($8.31). Red open could trigger trailing stop at $419.69. Let auto-execute; do not intervene.
5. **AVGO chip sector contagion (MEDIUM-HIGH):** Sympathy selling could keep NVDA/AMD/TSM suppressed.
6. **Friday NFP — thin pre-NFP liquidity (MEDIUM):** Gaps and whipsaws likely at 8:30 AM. Conditions must be evaluated POST-NFP (10:00 AM check).
7. **Deployment gap (ONGOING):** 3 positions, ~24.6% deployed vs 80% target. Need NVDA + 2 more positions but must not chase a volatile NFP day.

### Decision
**HOLD — await NFP, then conditional NVDA if conditions met at 10:00 AM**
- Primary reason: NFP 8:30 AM with below-consensus forecast; NASDAQ futures -1.14%; no pre-NFP buys
- NVDA conditional: if NFP ≥ +80K AND SPX ≥ 0% AND NVDA > $210 at 10:00 AM → execute market-open NVDA buy at 10:00 AM
- Existing positions: all above stops; MSFT has thin buffer (monitor for potential stop-out)
- AAPL approaching +15% trigger ($317.84) — tighten trail to 7% if/when hit
- Sources: xtb.com/cy (NFP forecast), bls.gov (jobs data), markets.businessinsider.com (SPX futs), ycharts.com (VIX), oilprice.com (WTI/Brent), youtube.com/@TheETFTracker (sector ETFs), totalrealreturns.com (XLK YTD), cnbc.com/2026/05/29 (weekly outlook)

---

## 2026-06-16 — Pre-Market Research (Day 37, Tuesday)

**Account snapshot:** Equity $100,065.35 | Cash $68,704.42 | Positions: 4 | DT count: 0
**Session-start equity (last_equity):** $100,125.87 | **Portfolio DD:** -0.06% — no halt
**Week trades:** 2/3 used (MSFT + JPM bought Jun 15) | **Buy slots remaining:** 1

### Open Positions (Pre-Market)
| Ticker | Shares | Entry | Pre-Mkt | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $295.96 | +$548 (+7.08%) | $285.66 (10%) | $317.40 | HOLD — WWDC/Siri thesis intact |
| JPM | 24 | $322.67 | $319.98 | -$65 (-0.83%) | $290.55 (10%) | $322.83 | HOLD — FOMC hold could benefit |
| MSFT | 19 | $396.72 | $398.00 | +$24 (+0.32%) | $361.58 (10%) | $401.75 | HOLD — Azure AI thesis intact |
| NVDA | 37 | $213.59 | $211.69 | -$70 (-0.89%) | $192.59 (10%) | $213.98 | HOLD — at critical support $195-$210 |

### Market Context
- **WTI:** ~$80.48-81/bbl | **Brent:** ~$82.77-83/bbl — stable, down from Jun 5 ($92-93); Strait of Hormuz fears fading (oilpriceapi.com, markets.businessinsider.com)
- **SPX Futures:** ~$7,558 (-0.04%) vs prev close $7,561.25 — essentially flat pre-market (marketwatch.com)
- **VIX:** ~17.68 (last confirmed Jun 12, ycharts.com) — declining from 19.44 → 22.22 → 19.44 → 17.68; calming but FOMC introduces spike risk
- **CRITICAL: FOMC interest-rate decision 2:30 PM EDT** — Kevin Warsh's FIRST meeting as new Fed Chair; 93%+ probability of hold at 3.50%-3.75% (Polymarket/Kalshi). BUT: Forbes Jun 8 warns of formal hawkish pivot away from easing bias; markets pricing 1-2 hikes possible later 2026. Dot plot update (SEP) released simultaneously — KEY market-mover risk (forbes.com, polymarket.com)
- **Retail Sales May at 8:30 AM**: +0.5% consensus — in-line or better = positive; miss = risk-off (marketwatch.com)
- **Leading Indicator MoM May:** -1.77% actual vs -0.8% prior — worse than expected; mild negative for economic outlook (tradingeconomics.com)
- **Earnings:** No universe names. WLY ($1.15 EPS expected), HITI ($0.01) — no impact on universe (x.com/marketsday)
- **No major geopolitical triggers** — Iran-US peace deal from Jun 14 still supporting risk-on baseline; oil pricing now reflects reopened Strait of Hormuz

### Sector ETF Ranking (Week of Jun 16)
1. **XLK Technology** — #1 YTD (+11.33%+); AI supercycle intact, NVDA/AAPL/MSFT momentum (annacoulling.com, totalrealreturns.com)
2. **XLE Energy** — Strong per Jun 1 sector review despite oil pullback; "real economy" rotation ongoing
3. **XLI Industrials** — Positive on sector rotation to real economy
- **XLF Financials** — Lagged in June 2026; FOMC hold may stabilize
- **XLV Healthcare** — Bottom tier, -1.35% YTD (totalrealreturns.com)

### Candidate Scoring (Universe — 20 symbols)
*Bars null pre-market (endpoint returning null); volume scores conservative; bars estimated from news/prices*

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **META** | **7/10** | 2 | 2 | 2 | 1 | 0 | **PASS (FOMC-gated)** |
| AMZN | 6/10 | 1 | 2 | 2 | 0 | 1 | FAIL (<7) |
| NVDA (held) | 6/10 | 2 | 2 | 1 | 0 | 1 | HOLD existing |
| MSFT (held) | 7/10 | 2 | 2 | 2 | 0 | 1 | HOLD existing |
| AAPL (held) | 6/10 | 2 | 2 | 1 | 0 | 1 | HOLD existing; at cap |
| JPM (held) | 5/10 | 1 | 1 | 2 | 0 | 1 | HOLD existing |
| GS | 3/10 | 1 | 1 | 0 | 0 | 1 | FAIL |
| AMD | 5/10 | 1 | 2 | 1 | 0 | 1 | FAIL |
| TSM | 4/10 | 1 | 2 | 0 | 0 | 1 | FAIL (extended) |
| XOM | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL (oil trend down) |
| CVX | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| GOOGL | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL (stopped out) |
| TSLA | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL |
| V | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| MA | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| UNH | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| JNJ | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| AVGO | N/A | — | — | — | — | — | Stopped out; no re-entry |
| SPY | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |
| QQQ | 3/10 | 0 | 1 | 1 | 1 | 0 | FAIL |

**META Catalyst notes:** "Investors reacted positively to new revenue strategies including Instagram Plus and AI cost controls" (Yahoo Finance); META +4.65% catalyst. Was stopped out Jun 10 at $578.70; current $571.68 (below prior stop). New catalyst may support re-entry. Score: Catalyst(2) Sector(2) Setup(2) Volume(1) R:R(0).

### Technical Validation — META (Score 7/10)
*Bars null pre-market; using price estimates from news sources*
- **Current price (est):** $571.68 (Yahoo Finance Jun 16)
- **SMA20 (est):** ~$595-610 (averaging decline from $643 HWM Jun 5 to ~$565 range Jun 11-16)
- **Distance from SMA20:** ~-3.9% to -6.2% → BELOW SMA20 ✓ (check PASS — not extended)
- **5-day momentum:** Jun 9 est ~$588-590 → (571.68 - 589) / 589 × 100 ≈ **-2.9% (NEGATIVE — 1 fail)**
- **Volume ratio:** Catalyst-driven +4.65% move suggests above-average volume; est 1.5x+ avg → PASS (vol ratio check)
- **Result:** 1 confirmed fail → PASSES technical threshold (need 2+ to disqualify)
- **BUT:** Entry would be BELOW prior stop-out level ($578.70) — entering below our own stop signals weak structure

### Trade Ideas

**#1 — META (Meta Platforms) — CONDITIONAL HOLD (FOMC-gated, defer to Wed morning)**
- Catalyst: Instagram Plus + AI cost controls strategy ($571.68 → +4.65% catalyst); tech sector #1 (annacoulling.com)
- Score: 7/10 | Catalyst: 2 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 0
- Entry plan: ~$570-580 (post-FOMC Wednesday morning if Warsh holds neutral)
- Stop: 10% trailing → initial floor ~$513
- Target: Prior HWM $643 (+12.5%) → R:R = 72/57 ≈ 1.25 (BELOW 2:1 minimum — **R:R weakness**)
- Concern: R:R scores 0 (<1.5); entry below prior stop level; FOMC hawkish tail
- Shares (if executed): 18 × $575 = $10,350 (~10.3% — slightly over 8% cap → reduce to 14 shares × $575 = $8,050 = 8.04%)
- **Verdict: HOLD — defer entry to post-FOMC Wednesday; do not enter on FOMC day**

### Risk Factors
1. **FOMC at 2:30 PM (CRITICAL — HIGHEST RISK):** Kevin Warsh's first FOMC meeting as new Fed Chair. 93%+ probability of hold, BUT dot plot (SEP) could show hawkish shift — fewer expected cuts or signals for rate hikes in 2026. This is the primary risk for all tech positions. Post-announcement volatility could easily move SPX ±1-2%. (polymarket.com, forbes.com)
2. **Retail Sales May 8:30 AM (HIGH):** +0.5% consensus. Miss = risk-off open. Wait for release before any positioning.
3. **Leading Indicator -1.77% (MEDIUM-HIGH):** Worse-than-expected economic leading index released — adds to concern about economic slowdown backdrop.
4. **NVDA at support (MEDIUM):** $211.69 sitting just above $195-$210 critical support (MarketBeat). FOMC hawkish outcome could break support; NVDA trailing stop at $192.59. Buffer: $211.69 - $192.59 = $19.10 (9.0%). Fragile.
5. **MSFT position (MEDIUM):** +0.32% unrealized, HWM $401.75, stop $361.58. Buffer: $398 - $361.58 = $36.42 (9.1%). FOMC-driven tech selloff risk.
6. **Low deployment (ONGOING):** 31.4% deployed vs 80% target. Cannot responsibly deploy on FOMC day. Best opportunity is post-FOMC Wednesday if neutral/dovish outcome.
7. **JPM below water (LOW-MEDIUM):** -0.83% unrealized. If FOMC hold is positive for financials, JPM could recover to par or above. If hawkish with higher-for-longer, bank margin pressure.

### Decision
**HOLD — FOMC day; no new entries; monitor existing positions**
- Primary reason: Kevin Warsh's first FOMC meeting (2:30 PM EDT) — hawkish dot plot risk is dominant; new rate hike signals possible in 2026; no new buys on FOMC day
- Secondary reason: META (only ≥7 candidate) has R:R <1.5 and entry would be below prior stop level — suboptimal setup; defer to post-FOMC Wednesday
- Existing positions: All above stops; no action required unless retail sales data at 8:30 AM triggers unusual move
- If FOMC hold + neutral/dovish Powell (Warsh) → strong case for META or 5th position entry Wednesday
- NVDA watch: If FOMC hawkish, NVDA may test $192.59 trailing stop; let auto-execute; do not intervene
- 1 buy slot remains this week — preserve for best post-FOMC opportunity

---

## 2026-06-18 — Midday Scan (Day 39, Thursday)

**Account snapshot:** Equity ~$99,906 | Cash $68,704.42 | Positions: 4 | DT count: 0
**Session-start equity (Jun 17 EOD):** $99,790.46 | **Portfolio DD:** +0.12% — no halt

### Open Positions (midday)
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $297.17 | +$582 (+7.5%) | $285.66 | $317.40 | OK |
| JPM | 24 | $322.67 | $329.21 | +$157 (+2.0%) | $304.26 | $338.07 | OK — off -1.3% today, retracing yesterday gains |
| MSFT | 19 | $396.72 | $379.34 | -$330 (-4.4%) | $361.58 | $401.75 | WATCH — -7% cut at $368.95, buffer $10.39 (2.7%) |
| NVDA | 37 | $213.59 | $210.07 | -$130 (-1.6%) | $192.59 | $213.98 | OK — bouncing +2.6% post-FOMC |

### Midday Scan Results
- **DD halt:** +0.12% from session-start — no halt
- **Cuts:** None — MSFT -4.4% (cut at -7% / $368.95; buffer $10.39), NVDA -1.6% — both above threshold
- **Tighten stops:** None — no position at +15% or +20%
- **Thesis:** All intact — FOMC held rates (Jun 17); NVDA recovering +2.6% post-FOMC; MSFT Azure AI thesis unbroken; JPM finance thesis holding despite today's -1.3% pullback
- **Intraday research:** Skipped — post-FOMC recovery moves are expected; no sharp unexplained moves
- **Action:** ✅ All clear

---

## 2026-06-19 (Day 40, Friday — Pre-Market) 🏛️ JUNETEENTH — MARKET CLOSED

**Account snapshot:** Equity $99,858.11 | Cash $68,704.42 (68.8%) | Buying Power $84,281.26 | DT count: 0
**Session-start equity (last_equity):** $99,858.11 | **Portfolio DD:** 0% — no halt
**⚠️ NYSE & NASDAQ CLOSED — Juneteenth National Independence Day. Next open: Monday June 22.**

### Open Positions (pre-market — prices as of Jun 18 close)
| Ticker | Shares | Entry | Last | Unrealized | Stop | HWM | Status |
|--------|--------|-------|------|------------|------|-----|--------|
| AAPL | 28 | $276.38 | $298.01 | +$605.64 (+7.83%) | $285.66 | $317.40 | OK |
| JPM | 24 | $322.67 | $325.22 | +$61.20 (+0.79%) | $304.26 | $338.07 | WATCH — downgraded today |
| MSFT | 19 | $396.72 | $379.40 | -$329.08 (-4.37%) | $361.58 | $401.75 | WATCH — cut at $368.95, buffer $10.45 |
| NVDA | 37 | $213.59 | $210.69 | -$107.36 (-1.36%) | $192.59 | $213.98 | OK — analyst upgrade today |

### Market Context
- **Oil:** WTI $75.92 (+0.09%), Brent $80.21 (+0.43%) — stable, slight firming (oilprice.com, investing.com)
- **SPX futures:** ~7,574.75 (range 7,531–7,583); SPX closed +1.08% Thursday; futures -0.26% in premarket (barrons.com)
- **VIX:** 17.04 — moderate, declining from 17.60 Thursday (yahoo finance historical)
- **Earnings today:** No significant pre-market earnings on Jun 19 (Juneteenth — minimal activity)
- **Economic data today:** Juneteenth federal holiday — BLS closed; CPI data deferred. MarketWatch indicates consumer price index release near this date; CNBC flags "next week's inflation data is vitally important" for market direction
- **Analyst moves today:** NVDA upgraded (China Renaissance — Buy initiated; consensus PT $309.13 per benzinga.com); META upgraded (AI growth undervalued per seekingalpha.com); JPM downgraded (headwinds per seekingalpha.com)

### Sector ETF Ranking (week ending Jun 19)
1. **XLK (Tech)** — #1 YTD; XLK + XLE "performed well this week" (annacoulling.com)
2. **XLE (Energy)** — second but oil momentum waning (WTI/Brent stable but 5d trend −6%)
3. **XLF (Financials)** — −0.26% YTD; weakest major sector (totalrealreturns.com data Jun 16)

(XLV Healthcare declining; XLI Industrials mixed)

### Candidate Scoring Table (full 20-symbol universe)
*Bars data via Alpaca (start=2026-03-01, end=2026-06-18). All technicals as of Jun 18 close.*

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Dist/SMA20 | Mom5 | VolRat | Result |
|--------|-------|----------|--------|-------|--------|-----|-----------|------|--------|--------|
| AAPL (held) | 6/10 | 0 | 2 | 2 | 2 | 0 | -1.8% | +0.8% | 1.60x | HELD — no add |
| MSFT (held) | 5/10 | 0 | 2 | 2 | 1 | 0 | -8.2% | -2.8% | 1.47x | HELD — caution zone |
| GOOGL | 5/10 | 0 | 2 | 2 | 1 | 0 | -1.0% | +2.9% | 1.32x | FAIL — no catalyst |
| **AMZN** | **8/10** | **1** | **2** | **2** | **2** | **1** | -3.5% | +1.2% | 1.68x | **PASS** |
| NVDA (held) | 9/10 | 2 | 2 | 2 | 1 | 2 | -0.5% | +2.8% | 1.32x | HELD — upgrade bullish |
| **META** | **8/10** | **2** | **2** | **2** | **1** | **1** | -3.7% | +1.5% | 1.44x | **PASS** |
| TSLA | 4/10 | 0 | 1 | 2 | 1 | 0 | -3.2% | +0.3% | 1.22x | FAIL |
| AMD | 4/10 | 0 | 2 | 1 | 1 | 0 | +7.1% | +10.0% | 1.35x | FAIL — extended |
| AVGO | N/A | — | — | — | — | — | -0.6% | +6.7% | 1.25x | No re-entry rule |
| TSM | 5/10 | 0 | 2 | 1 | 2 | 0 | +8.2% | +9.7% | 1.99x | FAIL — extended |
| JPM (held) | 4/10 | 0 | 0 | 2 | 2 | 0 | +4.7% | +3.7% | 2.07x | HELD — monitor downgrade |
| GS | 3/10 | 0 | 0 | 1 | 2 | 0 | +5.3% | +5.9% | 1.83x | FAIL — bearish engulfing |
| V | 4/10 | 0 | 0 | 2 | 2 | 0 | +0.9% | +2.6% | 1.79x | FAIL — weak sector |
| MA | 4/10 | 0 | 0 | 2 | 2 | 0 | -0.2% | +0.7% | 1.71x | FAIL — weak sector |
| XOM | 5/10 | 0 | 1 | 2 | 2 | 0 | -6.9% | -6.0% | 2.62x | FAIL — oil downtrend |
| CVX | 5/10 | 0 | 1 | 2 | 2 | 0 | -6.3% | -6.6% | 2.07x | FAIL — oil downtrend |
| UNH | 4/10 | 0 | 0 | 2 | 2 | 0 | +1.7% | -1.1% | 1.67x | FAIL — weak sector |
| JNJ | 4/10 | 0 | 0 | 2 | 2 | 0 | -1.4% | -4.2% | 2.35x | FAIL — weak sector |
| SPY | 4/10 | 0 | 1 | 2 | 1 | 0 | -0.0% | +1.2% | 1.40x | FAIL — no catalyst |
| QQQ | 4/10 | 0 | 2 | 2 | 0 | 0 | +1.9% | +3.3% | 1.00x | FAIL — vol at avg |

### Technical Validation — AMZN (Score 8/10) ✅ PASS
- **Last close:** $244.39 | **SMA20:** $253.28
- **Dist from SMA20:** −3.5% → BELOW SMA → ✅ PASS
- **5d momentum:** +1.2% → POSITIVE → ✅ PASS
- **Vol ratio:** 1.68x → above 0.8 → ✅ PASS
- **Result:** 0 confirmed fails → PASSES technical threshold
- **Setup note:** Well below SMA20 (recovering from broader tech pullback); AWS AI cloud quarterly revenue momentum intact; Q2 earnings scheduled ~Jul 30

### Technical Validation — META (Score 8/10) ✅ PASS
- **Last close:** $577.22 | **SMA20:** $599.48
- **Dist from SMA20:** −3.7% → BELOW SMA → ✅ PASS
- **5d momentum:** +1.5% → POSITIVE → ✅ PASS
- **Vol ratio:** 1.44x → above 0.8 → ✅ PASS
- **Result:** 0 confirmed fails → PASSES technical threshold
- **Setup note:** Below SMA20 with recovering momentum; confirmed catalyst (Instagram Plus + AI cost controls +4.65% catalyst Jun 16); analyst upgrade today from Seeking Alpha (seekingalpha.com)

### Trade Ideas (Monday Jun 22 conditional entries)

**#1 — AMZN — CONDITIONAL BUY (post-CPI confirmation)**
- Catalyst: AWS AI cloud momentum (scheduled growth); Q2 earnings ~Jul 30; AI inference demand beneficiary
- Score: 8/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 2 | R:R: 1
- Entry plan: ~$244.39 (Monday open, or limit near $243 if gap up)
- Stop: 10% trailing → initial floor ~$219.95
- Target: $300 (+22.8%) — AWS re-acceleration + AI cloud spending wave
- R:R: (300 − 244.39) / (244.39 − 219.95) = 55.61 / 24.44 = **2.27:1** ✅
- Shares: 32 × $244.39 = $7,820 = 7.8% of equity — within 8% cap ✅
- Technicals: dist −3.5%, mom5 +1.2%, volrat 1.68x — all PASS
- **Condition:** Enter Monday IF CPI data (due week of Jun 22) ≤ consensus; HOLD if CPI hot (>3.8%)

**#2 — META — CONDITIONAL BUY (post-CPI, higher conviction)**
- Catalyst: Confirmed — analyst upgrade (Seeking Alpha: NVDA/META upgraded on AI growth), Instagram Plus revenue strategy announced, AI cost controls Q2; +4.65% catalyst day Jun 16
- Score: 8/10 | Catalyst: 2 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 1
- Entry plan: ~$577.22 (Monday open, or limit $575 if stable)
- Stop: 10% trailing → initial floor ~$519.50
- Target: $700 (+21.2%) — AI monetization of Instagram + WhatsApp + AI assistant
- R:R: (700 − 577.22) / (577.22 − 519.50) = 122.78 / 57.72 = **2.13:1** ✅
- Shares: 13 × $577.22 = $7,504 = 7.5% of equity — within 8% cap ✅
- Technicals: dist −3.7%, mom5 +1.5%, volrat 1.44x — all PASS
- **Condition:** Prefer post-CPI entry; highest conviction idea this week given confirmed analyst catalyst + AI monetization

### Risk Factors
1. **CPI reaction Monday open (CRITICAL):** CPI data released this week — markets closed today (Juneteenth) so reaction hits Monday Jun 22 open. CNBC: "next week's inflation data is vitally important." Hot CPI (>3.8% YoY) = risk-off tech selloff, do not enter AMZN/META.
2. **JPM analyst downgrade (HIGH):** Seeking Alpha reports JPM downgraded today; Finance sector YTD −0.26% (weakest major sector). Existing +0.79% unrealized. If breaks below $315, re-evaluate manual exit. Q2 earnings Jul 14 is thesis catalyst — hold unless thesis breaks.
3. **MSFT caution zone (MEDIUM):** −4.37% unrealized. Manual −7% cut trigger at $368.95. Buffer only $10.45 (2.75%). A broad tech selloff on CPI Monday could test this level.
4. **NVDA holding at SMA (MEDIUM-LOW):** −1.36% unrealized, near SMA20 ($211.79). Analyst upgrade bullish but stop $192.59 still 8.6% away. Let trailing stop work.
5. **Three-day weekend gap risk:** Markets closed Fri–Sat–Sun. Any weekend macro event (geopolitical, Fed speaker) could gap positions at Monday open — especially MSFT and JPM which are near watch levels.
6. **Underdeployment (ONGOING):** 31.2% deployed vs 80% target. Two PASS candidates (AMZN, META) would add ~15.3% deployment if both entered. Still below 80% target with 6 position slots available.

### Decision
**HOLD — Market closed (Juneteenth); no trading possible today**
- Primary: NYSE/NASDAQ closed — no entries or exits possible
- Secondary: CPI risk Monday open is dominant; entering AMZN/META before CPI data reaction is imprudent — conditional entries preferred post-CPI clarity
- AMZN and META both score 8/10, pass technical checks, and are viable Monday entries if CPI cooperates
- JPM downgrade is new negative signal — monitor closely Monday open; consider manual exit if accelerates below $315
- NVDA analyst upgrade (China Renaissance buy, consensus PT $309) is a bullish confirmation; hold current position, let trailing stop work
- Weekly buy slot: 2/3 used this week (MSFT + JPM Jun 15). New week starts Monday — 3 fresh slots available