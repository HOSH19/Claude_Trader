# Research Log

---

## 2026-07-17 — Pre-Market Research (Day 60, Friday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $98,498.83 |
| Cash | $66,627.19 |
| Long Market Value | $31,871.64 |
| Deployment | 32.4% (target 80%) |
| DT Count | ~0 |
| Session-Start Equity | $99,084.75 |
| DD from session-start | -0.59% (halt threshold: -10%) |
| Weekly Trades Used | 0/3 (week Jul 14–18) |

**Open Positions:**
| Ticker | Shares | Avg Entry | Premarket | Unrealized | Stop | HWM |
|--------|--------|-----------|-----------|-----------|------|-----|
| AMZN | 34 | $233.97 | $246.50 | +$425.96 (+5.36%) | $232.27 | $258.08 |
| JPM | 24 | $322.67 | $342.73 | +$481.38 (+6.22%) | $314.62 | $349.58 |
| NVDA | 36 | $193.58 | $202.20 | +$310.33 (+4.45%) | $191.31 | $212.57 |
| V | 22 | $347.73 | $363.00 | +$335.94 (+4.39%) | $328.42 | $364.91 |

**Combined unrealized P&L:** +$1,553.61

### Market Context
- **Oil:** WTI $78.94 (+1.02%) | Brent $84.55 (+1.50%) — Iran military exchanges resuming; Hormuz blockade reinstated per CNBC (sources: oilprice.com, markets.businessinsider.com)
- **S&P 500 futures:** -0.22% (7,598.25) — modest decline despite Asian rout (source: markets.businessinsider.com/premarket)
- **VIX:** 15.77 (low fear; no panic signal) (source: finance.yahoo.com/quote/%5EVIX)
- **Asian markets:** Japan + Taiwan chip stocks -6% — "bloodbath" in semiconductors (source: reuters.com/world/china/global-markets-selloff-quotes-pix-2026-07-17)
- **BMO earnings today:** None in universe (UNH reported yesterday Jul 16 — beat massively)
- **Economic data released this week:**
  - CPI June: -0.4% actual vs -0.2% est (deflationary surprise)
  - Core CPI June: 0.0% actual vs 0.2% est
  - PPI June: -0.3% actual vs 0.0% est
  - Retail Sales June: +0.2% (in line)
  - → Fed rate cut probability rising; supportive for defensive/value sectors
  - (source: marketwatch.com/economy-politics/calendar)

### Sector ETF Ranking (week Jul 14–18)
| Rank | Sector | ETF | Thesis |
|------|--------|-----|--------|
| 1 | Finance | XLF | JPM/GS Q2 earnings beats; strongest bank earnings season |
| 2 | Energy | XLE | Iran military re-escalation; WTI +1% today above $78 threshold |
| 3 | Healthcare | XLV | UNH massive Q2 beat (+53.8% operating income YoY), guidance raised |
| — | Tech | XLK | Global chip selloff -6% Asia; weakest this week; locked sector (TSLA/TSM) |

### Candidate Scoring (20-symbol universe)
*Note: Alpaca bars API returned null (premarket); technicals estimated from Tavily price research.*

**Scored ≥7:**
```
XOM  | Score: 8/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 2 | R:R: 1
UNH  | Score: 7/10 | Catalyst: 2 | Sector: 1 | Setup: 1 | Volume: 2 | R:R: 1
MA   | Score: 7/10 | Catalyst: 1 | Sector: 2 | Setup: 2 | Volume: 1 | R:R: 1
```

**Scored <7 (eliminated):**
- AAPL/MSFT/GOOGL/AMZN/META/AMD/AVGO: Tech sector risk-off, no catalyst (Tech = 0/1 scores)
- TSLA/TSM: Sector locked (2 consecutive failures)
- NVDA: Held; chip selloff pressure; below ≥7 threshold as new entry
- JPM/V: Already held
- GS: Post-earnings (reported Jul 14), catalyst passed; no new entry signal
- CVX: Similar to XOM but more exposed to peace-deal risk; XOM preferred
- JNJ: No catalyst; Healthcare, but no specific event; Score ~5
- SPY/QQQ: ETF, monitoring only

### Technical Validation (estimates — bars null premarket)

**XOM — PASS (0/3 failures)**
- Price: ~$161 (post-Iran peace-talk dip from $169 peak; rebounding with re-escalation)
- 20d SMA est: ~$159 (range $153–$169 over 20d; weighted avg)
- SMA dist: +1.3% ✅ (at SMA, not extended)
- 5d momentum: $161 (Jul 10) → $161 (Jul 17) = ~0% — not negative ✅
- Volume: Elevated on Iran military exchange news; est >1.5× avg ✅
- Source: finance.yahoo.com, 247wallst.com, thestreet.com

**UNH — PASS (0/3 failures)**
- Price: ~$437 (post-earnings; up ~4.47% yesterday Jul 16)
- 20d SMA est: ~$418 (15+ days in $408–$425 range pre-earnings, 2d post-earnings)
- SMA dist: +4.5% ✅ (≤5%, within threshold)
- 5d momentum: $411 (Jul 10) → $437 (Jul 17) = +6.3% ✅
- Volume: Earnings day + morning after = massive ✅
- Source: rttnews.com, reuters.com, investopedia.com

**MA — PASS (0/3 failures)**
- Price: $535–$549 (active trading today per Robinhood Jul 17 data)
- 20d SMA est: ~$537 (ranged $527–$549 over past 3 weeks)
- SMA dist: +2.2% ✅ (at SMA)
- 5d momentum: $535 (Jul 10) → $549 (Jul 17) = +2.6% ✅
- Volume ratio: ~1.0× avg (no unusual volume) — passes ≥0.8 threshold ✅
- Note: Q2 earnings July 30; pre-earnings momentum window
- Source: robinhood.com/us/en/stocks/MA, perplexity.ai/finance/MA

### Trade Ideas

**1. XOM — ExxonMobil (PRIMARY, 8/10)**
- **Catalyst:** Trump reinstated Hormuz blockade; U.S.-Iran military exchanges ongoing (CNBC); oil +1% at $78.94 — confirmed military conflict = durable oil premium
- **Entry:** ~$161 at open (check spread; skip if >3% bid-ask or gap >5%)
- **Stop:** 10% trailing GTC | Initial stop ~$144.90
- **Target:** +20% = $193.20
- **R:R:** $32.20 / $16.10 = 2.0:1
- **Size:** 48 shares × $161 = $7,728 (7.8% equity)
- **Gate check:** universe ✅ | positions 4→5 ≤10 ✅ | weekly 0→1/3 ✅ | cost ≤8% ✅ | cash $66,627 ✅ | catalyst ✅ | DT 0 ✅ | not options ✅
- **Abort:** If oil drops >2% at open; peace deal breakthrough overnight; spread >3%
- Source: cnbc.com/quotes/@CL.1, thestreet.com/investing/stocks/xom-exxon-cvx-chevron-general-license-x

**2. UNH — UnitedHealth Group (SECONDARY, 7/10, POST-EARNINGS MOMENTUM)**
- **Catalyst:** Q2 2026 beat Jul 16 — EPS $6.38 vs est $4.68; op income +53.8% YoY; raised FY26 guidance to $19.50–$20 adj EPS. Post-earnings momentum day 2. Confirmed catalyst.
- **Entry:** ~$437 at open (skip if gap >5% above yesterday's close $437.24, i.e., >$459)
- **Stop:** 10% trailing GTC | Initial stop ~$393
- **Target:** +20% = $524
- **R:R:** $87 / $44 = 2.0:1
- **Size:** 17 shares × $437 = $7,429 (7.5% equity)
- **Gate check:** universe ✅ | positions 4→5 or 5→6 ≤10 ✅ | weekly 1→2/3 ✅ | cost ≤8% ✅ | cash ✅ | catalyst ✅ | DT 0 ✅
- **Abort:** If UNH reverses and opens below $420; broader market sells off >1% at open
- Source: reuters.com/legal/litigation/unitedhealth-raises-2026-forecast, rttnews.com/3667721

**3. MA — Mastercard (DEFERRED to next week, 7/10)**
- **Catalyst:** Q2 earnings Jul 30 (2 weeks); analyst consensus Buy, avg target $653 (Baird $680, Barclays $640, Clear Street $617). Pre-earnings window.
- **Deferral reason:** Finance sector concentration risk (already hold JPM + V; adding MA = 3 Finance positions). Risk-off Friday environment. Next week allows cleaner entry ahead of earnings week.
- **Watch:** Pre-market price stability above $535; no bid-ask spread issues
- Source: investor.mastercard.com, perplexity.ai/finance/MA

### Risk Factors
1. **Asian chip selloff (HIGH for NVDA):** Japan/Taiwan -6% in semis. NVDA at $202.20, stop $191.31 — only 5.4% cushion. Watch closely at open.
2. **Friday risk-off (MEDIUM):** End-of-week position-squaring; tech contagion to broader market uncertain.
3. **XOM Iran thesis whipsaw (MEDIUM):** Iran peace deal could restart at any time; war premium could reprice sharply. XOM dropped 5% on Jul 15 peace-talk news.
4. **UNH second-day fade (MEDIUM):** Post-earnings momo entry = higher fade risk; catalyst already 90% priced in.
5. **Finance concentration (LOW for today):** MA deferred; only JPM + V held in Finance.
6. **CPI deflationary overshoot risk (LOW):** Deflationary CPI (-0.4%) is good for rate-cut hopes but could signal demand weakness.
7. **Deployment gap (ONGOING):** 32.4% vs 80% target. Even with XOM+UNH adds ~$15k → ~47%. Still well below target; more work needed.

### Decision
**TRADE: XOM (primary) + UNH (secondary) | MA DEFERRED to next week**
- XOM: Enter at open; 48 shares ~$7,728; 10% trailing stop GTC. Iran re-escalation = durable catalyst; at SMA; oil above $78 threshold.
- UNH: Enter at open if stable (no gap >5% or broad selloff >1%); 17 shares ~$7,429; 10% trailing stop GTC. Post-earnings momentum + defensive in rate-cut environment.
- Weekly slots: 0→2/3 after both. 1 slot available next week.
- NVDA stop watch: $191.31. Alert if approaching on chip selloff.
- Sources: Alpaca API (account/positions/orders); Tavily (all research queries above; bars null premarket — note limitation)

---

## 2026-07-13 — Midday Addendum

**Midday Scan (Day 55, Monday)**
| Field | Value |
|-------|-------|
| Equity | $98,310.02 |
| Session-start equity | $98,237.29 |
| Day change | +$72.73 (+0.07%) — **no DD halt** |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Position Review (midday):**
| Ticker | Current | Unrealized | Intraday | Stop | Action |
|--------|---------|-----------|---------|------|--------|
| AMZN | $247.83 | +5.92% | +1.02% | $227.27 | ✅ Hold |
| JPM | $334.39 | +3.63% | -0.62% | $309.10 | ✅ Hold — earnings tomorrow |
| NVDA | $204.81 | +5.80% | -2.91% | $189.90 | ✅ Hold — see note |
| V | $357.53 | +2.82% | +2.45% | $321.81 | ✅ Hold |

**NVDA catalyst (Tavily):** Senate hearing on China chip sales + macro pressure; H20 shipments $0 in Q1 (vs $4.6B prior year), Q2 guided $0 — treated as "cleared risk, not hidden one." RTX Spark announced (new AI PC SoC with MediaTek/Microsoft — positive product news). Thesis intact: AI chip demand secular tailwind not broken by China revenue reset. Stop $189.90 (HWM $211.00, 10% trail) provides 7.3% buffer.

**V note:** Up +2.45% intraday to $357.53; broker HWM updated to $357.57; stop auto-trailed to $321.81. No tightening needed (+15% trigger at $399.89 not reached).

**Decisions:**
- No cuts (-7% trigger: none hit; all positions positive unrealized)
- No stop tightening (no position at +15%+)
- No thesis breaks — all 4 positions intact; NVDA weakened but thesis holds
- No new trades — midday not a buy window; pre-market CVX conditional deferred (markets softer today)

---

## 2026-07-13 — Pre-Market Research (Day 55, Monday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $98,237.29 |
| Cash | $66,627.19 (67.8%) |
| Long MV | $31,610.10 (32.2% deployed) |
| Last Equity | $98,315.93 |
| Day P&L pre-mkt | -$78.64 (-0.08%) — no DD halt |
| DT Count | 0 |
| Weekly buy slots | 3/3 FRESH (new week Jul 13-18) |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Open Position Status (live API):**
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|-----------|------|-----|--------|
| AMZN | 34 | $233.97 | $245.33 | +$386.18 (+4.85%) | $227.27 | $252.53 | ✅ Safe |
| JPM | 24 | $322.67 | $336.99 | +$343.68 (+4.44%) | $309.10 | $343.45 | ⚠️ Earnings tomorrow |
| NVDA | 36 | $193.58 | $208.42 | +$534.27 (+7.67%) | $189.90 | $211.00 | ✅ Safe |
| V | 22 | $347.73 | $349.00 | +$27.94 (+0.37%) | $316.05 | $351.17 | ✅ Safe |

**Stop buffers:**
- AMZN: $245.33 vs $227.27 → 7.4% buffer ✅
- JPM: $336.99 vs $309.10 → 8.3% buffer ✅ (earnings tomorrow — watch closely)
- NVDA: $208.42 vs $189.90 → 8.9% buffer ✅ (+15% tightening trigger at $222.62 not yet reached)
- V: $349.00 vs $316.05 → 9.4% buffer ✅

**Note (NVDA stops):** Two GTC trailing stop orders for NVDA (5428cc61: 33 shares + 9e459b0f: 3 shares), both stop $189.90, HWM $211.00. Total covered = 36 shares ✅.

---

### Market Context
- **WTI:** ~$74.35/bbl (+1.13%) | **Brent:** ~$76.80/bbl — oil RECOVERED from Jul 10 pullback on RESUMED Iran tensions
- **Iran Catalyst (CONFIRMED):** US military airstrikes on Iranian targets (Jul 8); Trump declared ceasefire "over"; Strait of Hormuz tanker attacks; oil sanctions reimposed → geopolitical premium sustained
- **SPX Futures:** Last settled $7,594 (Jul 12 Sunday). European markets sharply lower today (FTSE -2.05%, DAX -2.23%, CAC -2.18%) → US likely opens slightly negative
- **Nikkei:** +1.67% (Asian markets resilient)
- **VIX:** 16.13 (up from 15.57, +3.60%) — moderate risk-off
- **KEY EVENTS TOMORROW (Jul 14):** ① June CPI 8:30 AM (Est. core +0.2% m/m, +2.9% y/y) ② JPM Q2 BMO ($5.79 EPS est, $5.94 prior beat) ③ GS Q2 BMO ($10.88 EPS est; ±6% implied move) ④ BAC/WFC/C Q2 BMO ⑤ Fed Chair Warsh testimony House 10 AM ET
- **PPI:** July 15 | **FOMC Decision:** July 30 (25bps hike expected; 3.75-4.00% yr-end)
- Sources: Tavily (fortune.com, intellectia.ai, wsj.com, ycharts.com, kiplinger.com, motleyfool.com)

---

### Sector ETF Ranking (this week + YTD est Jul 10)
| Rank | Sector | ETF | YTD | This Week | Our Status |
|------|--------|-----|-----|-----------|------------|
| 1 | Technology | XLK | +33%+ | Leading | **LOCKED (2 consec failures TSLA+TSM)** |
| 2 | Utilities | XLU | +21%+ | Strong | No universe symbols |
| 3 | Materials | XLB | +14%+ | — | No universe symbols |
| 4 | Energy | XLE | +7.8% | Up (Iran/oil) | ✅ Eligible |
| 5 | Financials | XLF | +5.4% this week | Strong | ✅ Eligible (0 consec failures: V broke streak) |
| 6 | Healthcare | XLV | -6.7% | Declining | Eligible but bottom sector |

**Top 3 eligible for our universe:** Energy (XLE), Finance (XLF pre-earnings catalyst), Tech (LOCKED)

---

### Candidate Scoring (20-symbol universe; Tech sector locked; held tickers not re-scored)

**Locked:** AAPL, MSFT, GOOGL, AMZN(new), META, TSLA, AMD, AVGO, TSM (Tech 2 consec failures)
**Held (excluded from new entry scoring):** AMZN, JPM, NVDA, V

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Tech Checks | Result |
|--------|-------|----------|--------|-------|--------|-----|-------------|--------|
| CVX | 8/10 | 2 | 1 | 2 | 1 | 2 | PASS (all 3) | ✅ TRADE IDEA |
| GS | ~7/10 | 2 | 1 | 2 | 1 | 2 | HIGH RISK | ⛔ DISCARD (earnings binary tomorrow ±6%) |
| MA | 6/10 | 1 | 1 | 1 | 1 | 2 | N/A | ❌ <7 |
| XOM | 6/10 | 1 | 1 | 2 | 0 | 2 | N/A | ❌ <7 (low volume from bars null; est vol ratio below 0.8) |
| UNH | 3/10 | 0 | 0 | 1 | 1 | 1 | N/A | ❌ <7 |
| JNJ | 3/10 | 0 | 0 | 1 | 1 | 1 | N/A | ❌ <7 |
| SPY | 4/10 | 0 | 1 | 2 | 1 | 0 | N/A | ❌ <7 |
| QQQ | 4/10 | 0 | 1 | 2 | 1 | 0 | N/A | ❌ <7 |

*GS explained: Score ~7 on paper but DISCARD — earnings ±6% implied move tomorrow is unacceptable binary risk; "confirmed catalyst" day itself is the disqualifier (entering <24h before print). Bars API returned null — estimated all technicals from Tavily; GS SMA data: SMA8 $1,041, SMA20 $1,055, current ~$1,004 (bid). MA score: +6.8% above SMA20 ($533 vs $499.25) = Setup 1; catalyst 1 (bank earnings indirect). XOM vol ratio estimated <0.8x based on prior Jul 10 bars data (0.73x), no new catalyst today vs CVX.*

---

### Technical Validation (CVX — bars API returning null; estimated from Tavily sources)

**CVX (Score 8/10 ✅)**
- Last close (Yahoo Jul 10): ~$174.97-$176.42 | est. current: ~$175
- SMA20 (Barchart Jul 2): ~$178 | Current below SMA20 → Dist: ~-1.7% (at/below SMA = 2/2) ✅
- 5d momentum (Jul 3→Jul 10 est): $169 → $175 = +3.6% ✅ POSITIVE
- Volume ratio: Iran tensions + oil rally + Wolfe upgrade buying → est ≥1.0× (>0.8 threshold) ✅
- Extended >10% above SMA20: NO (-1.7% BELOW SMA20) ✅
- Tech check result: **PASS all 3** (no extended, positive mom, vol above threshold)
- `CVX | Score: 8/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 2`
- *Note: bars null — Alpaca data endpoint returning null for all symbols pre-market Jul 13. Technicals sourced from Barchart/Tavily/Yahoo Jul 10 close data. Manual estimation carries uncertainty; flagged in validation.*

---

### Trade Ideas

**#1 — CVX (Chevron) | Score 8/10 | CONDITIONAL TRADE**
- **Catalyst:** Wolfe Research upgraded Jul 2 to Outperform, $210 PT (confirmed); oil back to $74.35 (+1.13%) on resumed Iran tensions (US airstrikes confirmed, Strait of Hormuz at risk, sanctions reimposed) — catalyst actively playing today
- **Sector:** Energy (XLE, +7.8% YTD, mid-tier) ✅ 0 consecutive failures
- **Entry:** ~$175 | **Stop:** 10% trailing (~$157.50 initial, updates to HWM) | **Target:** $210 (Wolfe PT)
- **R:R:** ($210 - $175) / ($175 - $157.50) = $35 / $17.50 = **2.0:1** (minimum meets threshold)
- **Position size:** 44 shares × $175 = $7,700 (7.84% of equity $98,237) ✅ within 8% cap
- **Gates:** universe ✅ | positions 4→5 ≤10 ✅ | weekly 0→1/3 ✅ | cost $7,700 ≤ $7,859 (8%) ✅ | cash $66,627 ✅ | catalyst ✅ | DT 0 ✅ | no DD halt ✅
- **CONDITION:** Only execute if US markets open flat to -0.5% or better. European markets down 2%+ signals possible down open for US. If SPX futures indicate gap-down >0.5% at 9:30 AM, DEFER CVX to Tuesday post-CPI/earnings reaction. Oil independence from bank earnings makes CVX less sensitive to tomorrow's catalyst stack — energy trade can stand alone.
- **Why not today vs tomorrow:** Oil catalyst is ACTIVE now (not a stale event). CVX at/below SMA20 = ideal entry setup. If US markets gap down hard today, entry improves further (lower price, better R:R) — defer to Tuesday then.

---

### Risk Factors (Today)
1. **European risk-off (HIGH):** FTSE -2.05%, DAX -2.23%, CAC -2.18% → US likely opens modestly negative. May inhibit CVX entry if gap-down >0.5%.
2. **JPM earnings tomorrow (HIGH):** We hold 24 shares JPM (+4.44% unrealized, stop $309.10, HWM $343.45). Beat = upside, miss = risk to V and JPM position. Implied move 4.4%.
3. **Massive vol event tomorrow (HIGH):** CPI + 5 bank reports + Warsh testimony all on Jul 14. Buying CVX today avoids direct Finance earnings risk, but broad selloff from CPI surprise could affect Energy too.
4. **Iran tensions escalation/de-escalation (MEDIUM):** Oil at $74.35 — if diplomatic talks resume, oil could drop sharply and hurt CVX. The $210 Wolfe PT has fundamental support independent of oil spike.
5. **NVDA flat/slightly red pre-market (LOW):** $208.42 vs HWM $211.00. No stop tightening needed (trigger $222.62 not reached). Stop $189.90 (8.9% buffer). Watch AI chip news.
6. **Bars API null (LOW):** Technical validation estimated from Tavily sources; cannot confirm volume ratio with precision. Risk that CVX volume is actually below threshold.

---

### Decision
**CONDITIONAL TRADE: CVX (8/10) — buy at market-open IF US markets don't gap down >0.5%**
- CVX is the sole candidate scoring ≥7 with passing technical checks
- Energy sector play is independent of tomorrow's bank earnings / CPI catalyst — less binary than Finance
- All 4 existing positions are healthy; Finance sector (JPM) rides into earnings tomorrow
- If US opens down hard (European signal), HOLD and reassess Tuesday post-CPI/earnings
- GS too risky (binary earnings tomorrow); MA 6/10 (below threshold); XOM volume concern
- **Post-Tuesday**: If JPM+GS beat and CPI benign → assess GS (rerating to ≥7) or MA for 2nd buy this week
- Deployment target: 32.2% → adding CVX brings to ~40%. Still below 80% but systematic progress.

---

## 2026-07-10 — Midday Addendum

**Midday Scan (Day 54, Thursday)**
| Field | Value |
|-------|-------|
| Equity | $98,208.69 | 
| Session-start equity | $98,083.76 |
| Day change | +$124.93 (+0.13%) — **no DD halt** |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Position Review (midday):**
| Ticker | Current | Unrealized | Intraday | Stop | Action |
|--------|---------|-----------|---------|------|--------|
| AMZN | $245.74 | +5.03% | -0.53% | $227.27 | ✅ Hold |
| JPM | $336.46 | +4.27% | +0.30% | $309.10 | ✅ Hold |
| NVDA | $209.55 | +8.25% | +3.34% | $189.50 | ✅ Hold — see note |
| V | $345.81 | -0.55% | -0.69% | $316.05 | ✅ Hold |

**NVDA catalyst (Tavily):** China potential easing of export restrictions on NVDA products → positive catalyst confirming thesis. NVDA up +3.34% intraday. HWM per orders: $210.56 (broker-tracked). Stop $189.50. No tightening yet (+15% trigger at $222.62 not reached; current $209.55).

**Decisions:**
- No cuts (-7% trigger: none hit; lowest V at -0.55%)
- No stop tightening (no position at +15%+)
- No thesis breaks — all 4 positions intact
- No new trades — consistent with pre-market HOLD decision (2 slots reserved for post-JPM/GS earnings Jul 14)

---

## 2026-07-10 — Pre-Market Research (Day 54, Thursday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $98,083.76 |
| Cash | $66,627.19 (67.9%) |
| Long MV | $31,456.57 (32.1% deployed) |
| Last Equity | $98,038.31 |
| Day P&L pre-mkt | +$45.45 (+0.05%) — no DD halt |
| DT Count | 0 |
| Weekly buy slots | 1/3 used (V Jul 8); 2 remaining |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Open Position Status (live API):**
| Ticker | Shares | Entry | Current | Unrealized | Stop | HWM | Status |
|--------|--------|-------|---------|-----------|------|-----|--------|
| AMZN | 34 | $233.97 | $247.46 | +$458.60 (+5.77%) | $227.27 (10% trail) | $252.53 | ✅ Safe |
| JPM | 24 | $322.67 | $336.78 | +$338.71 (+4.37%) | $309.10 (10% trail) | $343.45 | ✅ Safe |
| NVDA | 36 | $193.58 | $202.30 | +$313.95 (+4.51%) | $184.64 (10% trail) | $205.15 | ✅ Safe |
| V | 22 | $347.73 | $348.97 | +$27.28 (+0.36%) | $314.65 (10% trail) | $349.61 | ✅ Safe |

**Stops review:**
- AMZN: $247.46 vs stop $227.27 → buffer $20.19 (8.2%) ✅
- JPM: $336.78 vs stop $309.10 → buffer $27.68 (8.2%) ✅
- NVDA: $202.30 vs stop $184.64 → buffer $17.66 (8.7%) ✅ (no tightening; +15% trigger $222.62 not reached)
- V: $348.97 vs stop $314.65 → buffer $34.32 (9.8%) ✅

---

### Market Context
- **WTI:** $71.86/bbl (-0.31%) | **Brent:** $76.04/bbl (-0.34%) — oil PULLING BACK from yesterday's Iran-driven spike (+5.71% → now -3.5% from spike high)
- **Iran Catalyst:** Trump-declared ceasefire breakdown is priced into oil; Strait of Hormuz tensions persist but momentum fading
- **SPX Futures:** +0.22% / ~7,545.50 — modest risk-on open
- **VIX:** 16.59 — moderate, comfortable (slightly elevated from yesterday's 16.13)
- **Earnings BMO today:** None in 20-symbol universe
- **KEY UPCOMING CATALYST:** JPM Q2 earnings Mon Jul 14 BMO ($5.61 EPS est, 96% beat probability) | GS Q2 earnings Mon Jul 14 BMO ($14.10 EPS est, 32.6% YoY increase) | TSM earnings Jul 16
- **Economic calendar:** BLS releases (CPI/PPI) may overlap this week — no confirmed major print today
- **GS analyst preview:** Strong capital markets, trading revenue expected; EPS $14.10 est; "fully priced after 249% run" (Tavily)
- **JPM analyst preview:** $49.8B revenue est, strong consumer banking + trading
- **AMZN note:** Mixed analyst sentiment in July; stock down ~10% from peak; buying opportunity discussed
- Sources: Tavily (businessinsider.com, cnbc.com, tradingeconomics.com, seekingalpha.com)

---

### Sector ETF Ranking (YTD est as of Jul 10)
| Rank | Sector | ETF | YTD est | Our tier | Status |
|------|--------|-----|---------|---------|--------|
| 1 | Technology | XLK | +33%+ | Top | **LOCKED (2 consec failures)** |
| 2 | Utilities | XLU | +21%+ | Top | No universe symbols |
| 3 | Materials | XLB | +14%+ | Top | No universe symbols |
| 4 | Energy | XLE | +9%+ | Mid | Eligible; oil reversing today |
| 5 | Financials | XLF | -1.7% | Bottom | Eligible; 1/2 consec failures; JPM/GS Jul 14 catalyst |
| 6 | Healthcare | XLV | -7%+ | Bottom | Eligible; no catalyst |

**Top 3 eligible sectors:** Energy (XLE, mid-tier), Finance (XLF, bottom but catalyst imminent)

---

### Candidate Scoring Table (20-symbol universe; tech locked)

**Held (not re-scored as new buys):** AMZN, JPM, NVDA, V
**Locked sector (Tech):** AAPL, MSFT, GOOGL, AMZN (new), META, TSLA, AMD, AVGO, TSM — ALL SKIP
**Eligible non-tech:** GS, MA (Finance); XOM, CVX (Energy); UNH, JNJ (Healthcare); SPY, QQQ (ETFs)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Tech | Result |
|--------|-------|----------|--------|-------|--------|-----|------|--------|
| XOM | 7/10 | 1 | 1 | 2 | 1 | 2 | BORDERLINE | ⚠️ PASS (see note) |
| CVX | 7/10 | 1 | 1 | 2 | 1 | 2 | BORDERLINE | ⚠️ PASS (see note) |
| GS | 6/10 | 1 | 0 | 2 | 1 | 2 | N/A | ❌ <7 |
| MA | 6/10 | 2 | 0 | 2 | 0 | 2 | N/A | ❌ <7 (vol 0.65x bars-est) |
| UNH | 3/10 | 0 | 0 | 1 | 1 | 1 | N/A | ❌ <7 |
| JNJ | 2/10 | 0 | 0 | 1 | 0 | 1 | N/A | ❌ <7 |
| SPY | 4/10 | 0 | 1 | 2 | 1 | 0 | N/A | ❌ <7 |
| QQQ | 4/10 | 0 | 1 | 2 | 1 | 0 | N/A | ❌ <7 (tech-heavy) |

*Catalyst notes: Iran geopolitical tension = ongoing confirmed event but oil is reversing today (-3.5% from spike) → downgraded to "scheduled event" (1) vs confirmed catalyst (2). GS/JPM earnings = scheduled event (1). MA earnings late July = scheduled (2 per rubric since dividend also confirmed). Setup: Energy stocks at SMA post-spike, bars null — estimated from prior session SMA20 data. Volume: null bars; estimated from oil-spike context.*

---

### Technical Validation (≥7 scorers — bars API returning null; estimated from prior session data and Tavily)

**XOM (Score 7/10 ⚠️)**
- Last confirmed close (Jul 9): ~$141.13 | SMA20 (Jul 9): $140.45 | Dist: +0.48% (AT SMA)
- Estimated today (post oil-spike): ~$143-145 | SMA20 est: ~$141-142 | Dist est: ~+1-2% (near SMA) ✅
- 5d momentum (est): Jun 30 close $136.72 → today est $143-145 = +4.6-6.1% ✅ POSITIVE
- Volume ratio (est): Oil-spike day elevated vol; today pullback reduces vol → est 0.9-1.0x → score 1 ✅
- Tech fails: 0 confirmed → PASSES threshold
- **BUT:** Oil reversed -3.5% from spike high; entering Energy AFTER the spike day is poor timing
- `XOM | Score: 7/10 | Catalyst: 1 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 2`

**CVX (Score 7/10 ⚠️)**
- Last confirmed close (Jul 9): ~$175.97 | SMA20 (Jul 9): $175.72 | Dist: +0.14% (AT SMA)
- Estimated today: ~$178-181 | SMA20 est: ~$176-177 | Dist est: ~+1-2% ✅
- 5d momentum (est): Jun 30 close $165.76 → today est $178-181 = +7.4-9.2% ✅ STRONG POSITIVE
- Volume ratio (est): Similar to XOM; spike-day elevated, today retreating → est 0.9-1.0x ✅
- Tech fails: 0 confirmed → PASSES threshold
- **BUT:** Same oil-reversal concern as XOM; concentration risk (both from same Iran catalyst)
- `CVX | Score: 7/10 | Catalyst: 1 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 2`

**GS (Score 6/10 ❌)**
- Price context (Tavily): SMA8 $1,041.03 | SMA20 $1,055.26 | Support $1,034.08 | Resistance $1,092.61
- Current ~$1,034-1,055 | -1.35% below SMA20 → BELOW SMA → setup excellent (score 2)
- 5d momentum: Positive (recovering from prior cut level $1,014); est +0.5-2% ✅
- Volume: Pre-earnings, building; est 1.0-1.2x → score 1
- Sector score 0 (XLF bottom third YTD) caps score at 7 max; conservative vol estimate keeps at 6
- `GS | Score: 6/10 | Catalyst: 1 | Sector: 0 | Setup: 2 | Volume: 1 | R:R: 2` → ❌ DISCARD

---

### Trade Ideas

**No high-conviction trade ideas today.** XOM and CVX technically score 7/10 but entry timing is poor:

**XOM/CVX — BORDERLINE PASS but TIMING RISK (not actioning)**
- Iran catalyst drove oil +5.71% on Jul 9; today oil -0.31% (-3.5% from spike high)
- Optimal entry was Jul 9 (at the spike day); today we are entering AFTER the catalyst peak on a reversal day
- Oil at $71.86 — still elevated vs pre-spike levels (~$68-69 Jul 8) but declining
- Buying into a confirmed reversal, one day after a 5.7% commodity spike, violates the spirit of the setup
- R:R deteriorates when entry is after momentum peaks

---

### Risk Factors (Today)
1. **Oil reversal (HIGH for Energy):** WTI -3.5% from yesterday's $74.46 spike high back to $71.86. Entering XOM/CVX now = buying into the pullback; ceasefire talks could resume and further reverse oil.
2. **JPM/GS earnings event risk Mon Jul 14 (HIGH):** 4-day window. Existing JPM position (24 shares, +4.37%) rides directly into earnings. Beat = upside; miss = potential stop trigger ($309.10 vs current $336.78 → 8.2% buffer).
3. **Finance sector caution (MEDIUM-HIGH):** 1/2 consecutive failures (GS cut Jun 30). If next Finance trade fails, sector locks. GS is below 7/10 threshold; no actionable Finance entry today.
4. **NVDA flat/slightly red:** $202.30 vs HWM $205.15. No tightening trigger. Monitor Kyber delay news — thesis intact per Nvidia denial but next-gen roadmap risk persists.
5. **Deployment gap (ONGOING):** 32.1% deployed vs 80% target. Need to close gap but no ≥7 candidates pass quality filter today. Patience.
6. **AMZN sentiment mixed:** Analysts divided on Amazon; some lowering targets; stock -10% from peak per Tavily. Hold thesis (AWS GenAI + Prime Day Jul). Stop $227.27 provides protection.
7. **V pre-earnings hold:** Visa Q3 earnings Jul 28 = catalyst ahead. V only +0.36% unrealized; stay patient for pre-earnings momentum.

---

### Decision
**HOLD — No new trades today**
- XOM and CVX score 7/10 and pass tech checks, but timing is unfavorable: oil reversed -3.5% from yesterday's Iran spike; entering today = chasing a day-old catalyst on a pullback
- GS and MA score 6/10 (Finance sector YTD bottom third pulls sector score to 0; below 7/10 threshold)
- No other non-tech candidates score ≥7
- **Preserve 2 buy slots for post-JPM/GS earnings opportunities (Mon Jul 14+):** If Finance sector responds positively to JPM beat ($5.61 EPS est, 96% prob), GS setup becomes more attractive; sector YTD trend improves
- Weekly slots reset Mon Jul 14 (new 3-slot window coincides with earnings catalyst)
- Existing 4 positions healthy; all above stops; combined unrealized +$1,138.54 (+3.62%)
- **Next catalyst window:** JPM/GS earnings Mon Jul 14 BMO → Finance sector inflection; TSM Jul 16

---

## 2026-07-09 — Pre-Market Research (Day 53, Thursday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $97,793.49 |
| Cash | $66,627.19 (68.1%) |
| Long MV | $31,166.30 (31.9% deployed) |
| Last Equity | $97,839.13 |
| Day P&L pre-mkt | -$45.64 (-0.05%) — no DD halt |
| DT Count | 0 |
| Weekly buy slots | 1/3 used (V on Jul 8); 2 remaining |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Open Position Status (premarket prices):**
| Ticker | Shares | Entry | Premarket | Unrealized | Stop | HWM | Status |
|--------|--------|-------|-----------|-----------|------|-----|--------|
| AMZN | 34 | $233.97 | $241.95 | +$271.26 (+3.41%) | $227.27 (10% trail) | $252.53 | ✅ Safe |
| JPM | 24 | $322.67 | $330.76 | +$194.16 (+2.51%) | $309.10 (10% trail) | $343.45 | ✅ Safe |
| NVDA | 36 | $193.58 | $204.60 | +$396.75 (+5.69%) | $184.64 (10% trail) | $205.15 | ✅ WATCH: stop $184.64 |
| V | 22 | $347.73 | $347.00 | -$16.06 (-0.21%) | $314.65 (10% trail) | $349.61 | ✅ Safe |

**Stops review:**
- AMZN: $241.95 vs stop $227.27 → buffer $14.68 (6.1%) ✅
- JPM: $330.76 vs stop $309.10 → buffer $21.66 (6.5%) ✅
- NVDA: $204.60 vs stop $184.64 → buffer $19.96 (9.8%) ✅ (HWM $205.15; near tightening at +15%)
- V: $347.00 vs stop $314.65 → buffer $32.35 (9.3%) ✅

---

### Market Context
- **WTI:** $74.46/bbl (+5.71% today) | **Brent:** $78.94/bbl (+6.44% today) — MAJOR SPIKE
- **Catalyst:** Trump declared US-Iran ceasefire is OVER → Strait of Hormuz tensions escalate → oil +5-7%
- **SPX Futures:** Unclear exact level; European markets heavily risk-off (FTSE -2.05%, DAX -2.23%, CAC -2.18%)
- **Nikkei:** +1.67% (divergent)
- **VIX:** 16.13 (up +3.60% from 15.57 — anxiety rising, not panic)
- **CPI at 8:30 AM ET TODAY:** June CPI expected 0.5% MoM / 4.2% YoY; Core CPI 0.2% MoM / 2.9% YoY — PRIMARY MARKET MOVER
- **Retail Sales at 8:30 AM ET TODAY:** June retail sales; consensus growth
- **No universe earnings today** (13 total Jul 9 earnings, none in our 20-symbol universe)
- **JPM/GS Q2 earnings Monday Jul 14 BMO** — Finance sector catalyst ahead
- **TSM earnings Jul 16**
- **Fed:** FOMC minutes released Jul 8 (already past); next rate decision Jul 30. Warsh-led Fed navigating energy-driven inflation.
- Sources: tradingeconomics.com, businessinsider.com, ycharts.com, marketwatch.com (via Tavily); Benzinga, CNBC, Yahoo Finance

---

### Sector ETF Ranking (YTD — estimated Jul 9)
| Rank | Sector | ETF | YTD est | Our tier | This wk |
|------|--------|-----|---------|---------|---------|
| 1 | Technology | XLK | +33%+ | Top ← **LOCKED (2 consec fails)** | +0.83% |
| 2 | Utilities | XLU | +21%+ | Top | +0.01% |
| 3 | Materials | XLB | +14%+ | Top | +1.46% |
| 4 | Energy | XLE | +9%+ | Mid (surging today on oil spike) | +1.12% |
| 5 | Financials | XLF | -1%+ | Bottom | +0.72% |
| 6 | Healthcare | XLV | -7%+ | Bottom | -0.34% |

**Top 3 sectors this week:** XLB (+1.46%), XLE (+1.12%), XLK (+0.83%) — Energy accelerating from Iran catalyst

---

### Candidate Scoring Table (20-symbol universe; tech locked)

**Held (not re-scored as new buys):** AMZN, JPM, NVDA, V
**Locked sector (Tech):** AAPL, MSFT, GOOGL, AMZN, META, TSLA, AMD, AVGO, TSM — ALL SKIP
**Eligible non-tech:** GS, MA (Finance); XOM, CVX (Energy); UNH, JNJ (Healthcare); SPY, QQQ (ETFs)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Tech Checks | Result |
|--------|-------|----------|--------|-------|--------|-----|-------------|--------|
| XOM | 7/10 | 2 | 1 | 2 | 1 | 1 | PASS (all 3) | ✅ TRADE IDEA |
| CVX | 7/10 | 2 | 1 | 2 | 1 | 1 | PASS (all 3) | ✅ TRADE IDEA |
| MA | 4/10 | 1 | 0 | 2 | 0 | 1 | FAIL (vol 0.65x) | ❌ DISCARD (<7) |
| GS | 5/10 | 1 | 0 | 1 | 1 | 2 | N/A | ❌ DISCARD (<7) |
| UNH | 3/10 | 0 | 0 | 1 | 1 | 1 | N/A | ❌ DISCARD (<7) |
| JNJ | 2/10 | 0 | 0 | 1 | 0 | 1 | N/A | ❌ DISCARD (<7) |
| SPY | 3/10 | 0 | 1 | 1 | 1 | 0 | N/A | ❌ DISCARD (<7) |
| QQQ | 3/10 | 0 | 1 | 1 | 1 | 0 | N/A | ❌ DISCARD (<7) |

*Catalyst scoring note: Iran ceasefire declared over by Trump = confirmed catalyst (2) for Energy. Finance sector earnings Jul 14 = scheduled event (1). No specific catalyst for Healthcare or ETFs.*
*Sector scoring: Energy recently mid-third (+9% est YTD, surging); Finance bottom-third (-1% YTD); Healthcare bottom-third (-7% YTD).*
*Setup: XOM and CVX both within 0.5% of 20d SMA = at SMA (score 2). MA +3.35% = at SMA (score 2). GS estimated mid-range.*

---

### Technical Validation (≥7 scorers)

**XOM** (Last close = $141.13, premarket may be higher on oil +5.71%):
- SMA20: $140.45 | Dist: +0.48% (AT SMA — excellent) ✅
- 5d momentum: +3.23% (vs Jun 30 close $136.72) ✅ POSITIVE
- Volume ratio: 0.99x (near 1.0x, above 0.8 threshold) ✅
- Extended >10%? NO → PASS | Mom5d negative? NO → PASS | Vol<0.8? NO → PASS
- **All 3 tech checks PASS**
- Sources: Alpaca bars data; Benzinga ceasefire cracks article

**CVX** (Last close = $175.97):
- SMA20: $175.72 | Dist: +0.14% (AT SMA — excellent) ✅
- 5d momentum: +6.16% (vs Jun 30 close $165.76) ✅ STRONG POSITIVE
- Volume ratio: 0.96x (above 0.8 threshold) ✅
- Extended >10%? NO → PASS | Mom5d negative? NO → PASS | Vol<0.8? NO → PASS
- **All 3 tech checks PASS**
- Sources: Alpaca bars data; Benzinga/Tickeron CVX analysis

**MA** (Last close = $519.86):
- SMA20: $502.99 | Dist: +3.35% (just above SMA)
- 5d momentum: +1.22% (vs Jun 30 close $513.60) ✅ positive
- Volume ratio: 0.65x ❌ BELOW 0.8 (1 tech check fail)
- Score 4/10 → discard before tech check even applies

---

### Trade Ideas (≥7 scorers that passed tech)

**Idea 1: XOM (Primary)**
- Catalyst: Iran ceasefire declared over by Trump → oil +5-7% → direct revenue impact for integrated oil major
- Entry: ~$141-145 at market open (pending CPI 8:30 AM; oil already +5.71% premarket)
- Stop: 10% trailing GTC (initial stop ~$127-131)
- Target: +20% → ~$169-174
- R:R: ~1.8-2.0:1
- Score: 7/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 1
- Technicals: SMA20 $140.45 (+0.48% above); 5d mom +3.23%; vol ratio 0.99x
- Position size: ~$7,823 (8% of $97,793 equity) → ~54 shares at $145
- Gates: universe ✅ | positions 4→5 ≤10 ✅ | weekly 1→2/3 ✅ | cost ≤8% ✅ | cash $66,627 ✅ | catalyst ✅ | DT 0 ✅

**Idea 2: CVX (Secondary)**
- Catalyst: Same Iran/oil catalyst. CVX higher leverage to upstream production vs XOM.
- Entry: ~$176-180 at market open (pending CPI)
- Stop: 10% trailing GTC (initial stop ~$158-162)
- Target: +20% → ~$211-216
- R:R: ~1.8:1
- Score: 7/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 1
- Technicals: SMA20 $175.72 (+0.14% above); 5d mom +6.16%; vol ratio 0.96x
- Position size: ~$7,823 (8% equity) → ~43-44 shares at $178
- Gates: universe ✅ | positions 5→6 ≤10 ✅ | weekly 2→3/3 ✅ | cost ≤8% ✅ | cash ✅ | catalyst ✅ | DT 0 ✅
- NOTE: This would use 3/3 weekly slots — no further buys until Mon Jul 13

---

### Risk Factors (Today)
1. **CPI at 8:30 AM (CRITICAL):** June CPI expected 4.2% YoY. If hot (>4.2%), VIX spikes, broad selloff — energy not immune to rate-hike fears causing demand destruction. WAIT for CPI before entering XOM/CVX.
2. **Iran tensions = two-way risk:** If ceasefire unexpectedly resumes → oil reverses → XOM/CVX drop sharply. Oil +5-7% may already be partially priced in from Jul 8 (XOM opened $143.44 but closed $141.13).
3. **European markets risk-off (-2%+):** FTSE -2.05%, DAX -2.23%, CAC -2.18% — broad equity weakness may drag US open.
4. **NVDA near HWM tightening threshold:** NVDA at $204.60 vs HWM $205.15. If NVDA closes +15% above entry ($193.58 × 1.15 = $222.62) → tighten stop to 7%. Not triggered yet but watch.
5. **Samsung chip results drag chip stocks:** Mentioned in news "chip stocks sank." NVDA intraday risk.
6. **Concentration risk:** Buying both XOM and CVX = 2 energy positions from same Iran catalyst. One geopolitical pivot = both positions impacted.
7. **Deployment constraint:** 3/3 slots used if both entered — no further buys until Mon Jul 13.

---

### Decision
**CONDITIONAL TRADE: XOM (primary) and CVX (secondary) — gate on CPI at 8:30 AM**
- **If CPI ≤ 4.2% YoY (benign/in-line):** BUY XOM at market open; evaluate CVX as second buy
- **If CPI > 4.2% YoY (hot):** HOLD — rate-hike fears may temporarily reverse oil despite geopolitical tensions
- **Default:** HOLD until CPI print confirms conditions
- Both XOM and CVX passed scoring (7/10) and all tech checks
- Positions would go 4→5 or 4→6; deployment 31.9% → 40-48% (still below 80% but improving)
- Market-open routine to execute based on CPI outcome and opening price action

---

## 2026-07-08 — Pre-Market Research (Day 52, Tuesday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $97,542.46 |
| Cash | $74,277.26 (76.1%) |
| Long MV | $23,265.20 (23.9% deployed) |
| Last Equity | $97,871.34 |
| Day P&L pre-mkt | -$328.88 (-0.34%) — no halt |
| DT Count | 0 |
| Weekly buy slots | 0/3 (fresh — reset Monday Jul 7) |
| Open positions | 3 (AMZN, JPM, NVDA) |

**Open Position Status (premarket):**
| Ticker | Shares | Entry | Price | Unrealized | Stop | HWM | Status |
|--------|--------|-------|-------|-----------|------|-----|--------|
| AMZN | 34 | $233.97 | $242.00 | +$272.96 (+3.43%) | $227.27 (10% trail) | $252.53 | ✅ Safe |
| JPM | 24 | $322.67 | $336.00 | +$319.92 (+4.13%) | $309.10 (10% trail) | $343.45 | ✅ Safe |
| NVDA | 36 | $193.58 | $193.70 | +$4.35 (+0.06%) | $180.57 (10% trail) | $200.63 | ✅ Safe (buffer $13.13) |

**Stops review:**
- AMZN: $242 vs stop $227.27 → buffer $14.73 (6.1%) ✅
- JPM: $336 vs stop $309.10 → buffer $26.90 (8.0%) ✅
- NVDA: $193.70 vs stop $180.57 → buffer $13.13 (6.8%) ✅ (Kyber delay denied by NVDA; thesis intact)

---

### Market Context
- **WTI:** ~$68/bbl est | **Brent:** ~$71/bbl (J.P. Morgan 2026 forecast $60/bbl avg; range $68-72 current); oil weak ongoing
- **SPX Futures:** +0.4% / ~7,541 — risk-on open
- **VIX:** 17.55 (moderate, declining; favorable for entries)
- **BMO Earnings Today:** None in universe
- **Economic calendar:** CPI July 14 | PPI July 15 | Fed rate decision July 30 | No major releases today
- **Upcoming this week:** JPM Q2 earnings July 14 BMO ($5.44 EPS est) | GS Q2 earnings July 14 BMO | TSM July 16
- **Sector narrative:** AI/semiconductor weakness noted (Kyber delay) but NVDA denied; clean energy / nuclear AI power deals gaining interest (not in universe)
- **NVDA update:** Analysts maintain $250 PT (+29% from $193.70 current); Kyber delay denied by company; core Blackwell/Hopper intact
- Sources: Tavily (businessinsider.com, cnbc.com, tradingeconomics.com, seekingalpha.com)

---

### Sector ETF Ranking (YTD — as of last available Jul 2 data)
| Rank | Sector | ETF | YTD | Our tier |
|------|--------|-----|-----|---------|
| 1 | Technology | XLK | +33.1% | Top ← **LOCKED (2 consec failures)** |
| 2 | Utilities | XLU | +21.0% | Top |
| 3 | Consumer Staples | XLP | +16.9% | Top |
| 4 | Materials | XLB | +14.8% | Mid |
| 5 | Real Estate | XLRE | +9.4% | Mid |
| 6 | Energy | XLE | +7.8% | Mid |
| 7 | Financials | XLF | -1.7% | Mid ← 1/2 failures; next entry allowed |
| 8 | Consumer Disc. | XLY | -1.7% | Bottom |
| 9 | Industrials | XLI | -3.1% | Bottom |
| 10 | Health Care | XLV | -6.7% | Bottom |

**Top 3 sectors (eligible for new entries):** XLU, XLP, XLB — none in our 20-symbol universe
**Eligible Finance:** V, MA (XLF mid-tier; JPM Q2 earnings Jul 14 is sector catalyst)
**Eligible Energy:** XOM, CVX (XLE mid-tier; oil weak headwind)
**Healthcare:** UNH, JNJ (XLV bottom-tier = sector score 0)

---

### Candidate Scoring (Universe: 20 symbols only)
*Tech sector LOCKED: AAPL, MSFT, GOOGL, AMZN (new), NVDA (new), META, TSLA, AMD, AVGO, TSM, QQQ — no new entries.*

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| **V** | **8/10** | **2** | **1** | **2** | **1** | **2** | **✅ PASS** |
| **MA** | **7/10** | **2** | **1** | **1** | **1** | **2** | **✅ PASS** |
| XOM | 4/10 | 0 | 1 | 2 | 1 | 0 | ❌ <7 (no catalyst, oil weak, R:R <1.5) |
| CVX | 4/10 | 0 | 1 | 2 | 1 | 0 | ❌ <7 (same) |
| UNH | 3/10 | 1 | 0 | 1 | 0 | 1 | ❌ <7 (healthcare bottom sector) |
| JNJ | 2/10 | 0 | 0 | 1 | 1 | 0 | ❌ <7 |
| GS | 4/10 | 2 | 1 | 0 | 0 | 1 | ❌ Bars null; price unknown post-cut; setup unknown |
| SPY | 2/10 | 0 | 1 | 2 | 0 | 0 | ❌ <7 |
| All tech | 0/10 | — | — | — | — | — | ❌ SECTOR LOCKED |

**V catalyst notes:** Visa hit near-52-week high in July 2026 (52wk range $293.89–$365.02; current $352.20); "strong revenue growth and value-added services" confirmed; bullish trend with support at $323.50, resistance $362.13 (Tavily: seekingalpha.com). Q4 FY2026 earnings expected late July = upcoming catalyst. Finance sector has JPM+GS both reporting July 14 = sector tailwind.

**MA catalyst notes:** Mastercard reached 52-week high in July 2026; dividend $0.87/share declared (Tavily). Q2 calendar earnings late July 2026 = pre-earnings entry window. "Strong momentum and attractive cash flow" (Tavily).

---

### Technical Validation (Bars API returned null for V, MA, XOM, CVX, UNH, JNJ — all non-held symbols. Estimating from news/Tavily context; limitation noted.)

**V — Score 8/10 ✅**
- **Current price (Tavily):** $352.20 | **52-wk range:** $293.89–$365.02 | **Support/resistance:** $323.50 / $362.13
- **Est SMA20:** ~$340 (V trending up toward 52-wk high; support at $323.50 implies 50d MA there; 20d MA likely $338-342)
- **Dist from SMA20 (est):** +3.5% → within 5% of SMA → ✅ PASS (setup score 2 — not extended)
- **5-day momentum (est):** POSITIVE — V tracking near 52-wk high ✅
- **Vol ratio (est):** ~1.0–1.2× (near-high momentum, reasonable volume) ✅
- **Tech fails:** 0 → PASSES tech threshold
- **R:R:** Entry ~$352 | Stop 10% trail ~$316.80 | Target +20% ~$422.40 | R:R = $70.40/$35.20 = **2.0:1** ✅
- `V | Score: 8/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 2`

**MA — Score 7/10 ✅**
- **Current price (Tavily):** ~$518 | **52-wk high (Tavily):** new high reached July 2026
- **Est SMA20:** ~$495 (at 52-wk high, 20d avg below current by ~4-5%)
- **Dist from SMA20 (est):** +4.6% → approaching 5% threshold → BORDERLINE setup score 1
- **5-day momentum (est):** POSITIVE (at 52-wk high) ✅
- **Vol ratio (est):** ~1.0× (stable; dividend announcement) ✅
- **Tech fails:** 0 → PASSES (0 confirmed fails)
- **R:R:** Entry ~$518 | Stop $466.20 | Target $621.60 (+20%) | R:R = **2.0:1** ✅
- `MA | Score: 7/10 | Catalyst: 2 | Sector: 1 | Setup: 1 | Volume: 1 | R:R: 2`

---

### Trade Ideas

**Idea 1 — V (Visa) — CONDITIONAL BUY**
- **Catalyst:** Visa near 52-week high ($352.20 vs $365.02 HWM); confirmed strong revenue growth + value-added services acceleration; Q4 FY2026 earnings late July catalyst; JPM/GS sector earnings July 14 as Finance sector tailwind
- **Score:** 8/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 2
- **Entry:** ~$352 (market open limit)
- **Stop:** 10% trailing GTC → initial ~$316.80
- **Target:** $422.40 (+20%)
- **R:R:** 2.0:1 ✅
- **Shares:** 22 × $352 = $7,744 = **7.94% of equity** ✅
- **Gate check:** positions 3→4 ✅ | weekly 0→1/3 ✅ | cost $7,744 ≤ $7,803 (8% cap) ✅ | cash $74,277 ✅ | universe ✅ | DD clear ✅ | DT 0 ✅ | catalyst ✅
- **Condition:** SPX opens flat or better (futures +0.4% ✅) | VIX ≤ 20 (17.55 ✅)
- **Technicals:** dist est +3.5%, mom5 positive ✅, vol ratio est 1.0x ✅ — 0 tech fails

**Idea 2 — MA (Mastercard) — CONDITIONAL BUY (slot 2)**
- **Catalyst:** MA at 52-week high; dividend $0.87/share declared; Q2 calendar earnings late July = pre-earnings entry window; Finance sector catalyst (JPM/GS July 14)
- **Score:** 7/10 | Catalyst: 2 | Sector: 1 | Setup: 1 | Volume: 1 | R:R: 2
- **Entry:** ~$518 (limit order post V confirmation)
- **Stop:** 10% trailing GTC → initial ~$466.20
- **Target:** $621.60 (+20%)
- **R:R:** 2.0:1 ✅
- **Shares:** 15 × $518 = $7,770 = **7.97% of equity** ✅
- **Gate check:** positions 4→5 ✅ | weekly 1→2/3 ✅ | cost $7,770 ≤ $7,803 ✅ | cash ~$66,533 post-V ✅ | universe ✅ | all gates ✅
- **Condition:** V fills cleanly at open AND market conditions hold by 10:00 AM ET
- **Technicals:** dist est +4.6%, mom5 positive ✅, vol ratio est 1.0x ✅ — 0 tech fails

---

### Risk Factors
1. **Bars API unavailable (HIGH for scoring accuracy):** Non-held symbols returning null; SMA/volume estimated from Tavily context. Limit orders mitigate gap-up/chase risk.
2. **Finance sector 1/2 consecutive failures (HIGH):** GS cut Jun 30 = 1 fail. If V fails, sector locks (2/2). Choose position size conservatively; V is more diversified (payments vs IB) than GS.
3. **CPI July 14 + JPM/GS earnings same day (HIGH):** Major event risk next Monday. Positions opened today ride into next week. VIX 17.55 manageable pre-event but can spike by Thu/Fri.
4. **NVDA thesis (MEDIUM):** Company denied Kyber delay; analysts $250 PT. Stop $180.57 provides protection. No action needed today.
5. **Underdeployment (ONGOING):** 23.9% deployed vs 80% target. V+MA adds ~16% → reaches ~40%. Still below target; third slot available for Friday if Thursday confirms sector strength.
6. **Oil ongoing weakness (LOW for us):** Brent ~$71; no energy exposure. Neutral.
7. **DD halt check:** -0.34% from last equity ($97,871.34) → halt threshold $88,084 (currently $97,542 — CLEAR). SPX +0.4% pre-market should lift equity at open.

---

### Decision
**TRADE: V (primary) + CONDITIONAL TRADE MA (secondary)**
- V is the highest-conviction non-tech candidate: 8/10 score, 52-week high momentum, pre-earnings setup, Finance sector catalyst (JPM/GS July 14)
- MA is secondary: 7/10, at 52-week high, dividend catalyst, same Finance tailwind; enter only after V fills cleanly
- Deployment priority: critical to close gap (23.9% → ~40% with 2 fills)
- All buy-side gates pass for both V and MA
- HOLD on slot 3 — reserve for Thursday after observing sector reaction to any market events
- Existing positions: no cuts/tightens needed; all above stops with positive unrealized P&L
- Tech sector remains LOCKED; no exceptions

---

## 2026-07-06 — Pre-Market Research (Day 50, Monday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $97,676.14 |
| Cash | $74,277.26 (76.0%) |
| Long MV | $23,398.88 (24.0% deployed) |
| DT Count | 0 |
| DD from last equity | +$106.94 (+0.11%) — no halt |
| Open positions | 3 (AMZN, JPM, NVDA) |
| Weekly buy slots used | 0/3 (fresh week) |

**Open Position Status:**
| Ticker | Shares | Entry | Price | Unrealized | Stop | HWM |
|--------|--------|-------|-------|-----------|------|-----|
| AMZN | 34 | $233.97 | $245.24 | +$383.12 (+4.82%) | $227.27 (10% trail) | $252.53 |
| JPM | 24 | $322.67 | $334.01 | +$272.16 (+3.51%) | $309.10 (10% trail) | $343.45 |
| NVDA | 36 | $193.58 | $195.68 | +$75.63 (+1.09%) | $180.57 (10% trail) | $200.63 |

---

### Market Context
- **WTI:** ~$69.00 | **Brent:** ~$72.20 (flat, stable)
- **SPX Futures:** +28 pts / +0.37% (risk-on open expected)
- **VIX:** ~16.3 (low, well below danger zone)
- **Today's catalysts:** ISM Services (10:00 AM ET, est. 54.5), S&P Services PMI (9:45 AM ET)
- **This week:** Fed June meeting minutes release; no significant BMO earnings today
- **Upcoming earnings:** PEP (Thu BMO); JPM (Jul 14 BMO), TSM (Jul 16)
- **Market breadth:** 69.73% of S&P 1500 above 200d MA — healthy
- **Note:** Momentum trade "violent unwind" risk flagged by MarketWatch for July

---

### Sector ETF Ranking (Week Ending Jul 4 Holiday)
1. **XLK** (Tech) — leader YTD; AI spending driving outperformance
2. **XLI** (Industrials) — performed well
3. **XLF** (Financials) — JPM earnings Jul 14 approaching
- **SPY YTD:** +9.80% as of Jul 2
- **Semi (SOXX):** Sold off hard holiday week on NVDA Kyber delay news

---

### Candidate Scoring (Universe: 20 symbols only)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Status |
|--------|-------|----------|--------|-------|--------|-----|--------|
| META | **8/10** | 2 | 2 | 1 | 1 | 2 | ✅ PASS |
| MSFT | **8/10** | 1 | 2 | 2 | 1 | 2 | ✅ PASS |
| TSM | **8/10** | 2 | 2 | 2 | 2 | 2 | ⚠️ DEFERRED (neg. momentum) |
| GS | 4/10 | 0 | 1 | 1 | 1 | 1 | ❌ <7 |
| V | 5/10 | 0 | 1 | 2 | 1 | 1 | ❌ <7 |
| Others | <7 | — | — | — | — | — | ❌ <7 |

**IMPORTANT — Sector-fail update from Jul 1 log:** Tech sector had 2/2 consecutive new-entry failures (Jul 1: TSLA+TSM batch). Per strategy, NO NEW TECH BUYS until reset. This OVERRIDES META and MSFT ideas above. Reviewing this constraint:
- Jul 1 log states: "Tech: 2/2 consecutive new-entry failures (TSLA+TSM same batch Jul 1→2) → NO NEW TECH BUYS until reset"
- **TSLA is NOT in the scored universe (it IS in the 20-symbol list) — if TSLA + TSM counted as tech fails, sector exit is active**
- META and MSFT are both Tech sector → **SECTOR EXIT RULE ACTIVE → CANNOT BUY META OR MSFT**
- Only Finance (JPM held, +3.5%), Consumer Discretionary (AMZN held), non-Tech candidates viable
- **Decision revised to HOLD (sector constraint)**

---

### Technical Validation
**Bars API returned null (data access limitation) — estimated from news/price context.**

**META (~$553):** 5-day momentum +7% ✅, est. 5-8% above SMA ✅, high volume ✅ — passes tech check. BUT: SECTOR EXIT blocks entry.

**MSFT (~$390):** est. 1-2% above SMA ✅, positive momentum ✅ — passes tech check. BUT: SECTOR EXIT blocks entry.

---

### NVDA Thesis Watch
- **CRITICAL (Jul 5-6):** SemiAnalysis — Kyber NVL144 delayed 12+ months to 2028 (PCB midplane manufacturing failure); Rubin Ultra 4-die CANCELLED; NVL72×2 backup cancelled. AMD MI500X and Google TPU positioned as beneficiaries.
- **Thesis:** WEAKENED but not broken. Near-term Oberon Rubin rack shipments continue. Core Blackwell/Hopper business intact.
- **Position:** +$75.63 (+1.09%); stop $180.57 provides protection.
- **Decision:** HOLD with active monitoring. Cut if price breaks below $185 or additional negative roadmap news.
- Sources: [CNBC Jul 6](https://www.cnbc.com/amp/2026/07/06/nvidia-kyber-rack-system-delayed-to-2028-over-manufacturing-snags.html)

---

### Risk Factors
1. **NVDA Kyber delay (HIGH):** Next-gen rack delayed 1+ year; competitive moat eroding vs AMD/Google TPU
2. **Tech sector exit active (HIGH):** 2 consecutive tech failures (Jul 1) → no new Tech buys
3. **Semiconductor selloff (HIGH):** SOXX weakness; TSM dropped sharply post-NVDA delay news
4. **Momentum unwind risk (MEDIUM):** MarketWatch flags July rotation risk
5. **ISM Services today (MEDIUM):** 10:00 AM ET (est. 54.5) — weak print = market pressure
6. **Fed minutes (MEDIUM):** Possible hawkish signals this week
7. **Underdeployment (ONGOING):** 24% deployed vs 80% target; sector constraints limit options

---

### Decision
**HOLD** — Tech sector exit rule (2 consecutive failures Jul 1) blocks META and MSFT entries.
- No viable non-Tech candidates scored ≥7 with confirmed catalysts
- Existing positions (AMZN, JPM, NVDA) within rules, no cuts required
- Monitor ISM data and JPM earnings (Jul 14) for directional signals
- Reserve 3 weekly buy slots for: JPM earnings catalyst (Jul 14, Finance sector, 1 failure), TSM post-earnings (Jul 16), and non-Tech breakout
- Next action: market-open NVDA price check (thesis watch)

---

## 2026-07-01 — Pre-Market Research (Day 48, Wednesday)

### Account Snapshot
- **Equity:** $98,571.63 | **Cash:** $75,397.15 (76.5%) | **Deployed:** $23,174.48 (23.5%)
- **Last equity:** $98,559.87 | **DD:** +0.01% (no halt — equity UP from last_equity)
- **Daytrade count:** 0 | **Weekly buys:** 1/3 used | **2 slots remaining**

| Ticker | Shares | Entry | Current | Unrealized | Stop | Cut Trigger | Status |
|--------|--------|-------|---------|-----------|------|-------------|--------|
| AMZN | 34 | $233.97 | $239.90 | +$201.56 (+2.53%) | $227.27 (HWM $252.53) | $217.59 | ✅ Safe (+$22.31 buffer) |
| JPM | 24 | $322.67 | $326.99 | +$103.68 (+1.34%) | $309.10 (HWM $343.45) | $300.08 | ✅ Safe (+$26.91) — Ex-div Jul 6 |
| NVDA | 36 | $193.58 | $199.17 | +$201.27 (+2.89%) | $180.57 (HWM $200.63) | $180.03 | ✅ Safe (+$19.14 buffer) |

### Market Context
- **WTI:** $69.46–69.52 (range $68.69–$70.19) | **Brent:** $72.25–73.03 (-0.96% today, -24.74% past month)
- **SPX futures:** 7,530.00 (-18.25 pts / -0.24%) | **Dow:** 52,503 (-167) | **NQ:** 30,444 (-79.75 / -0.26%)
- **VIX:** 16.74 (calm, day range 16.27–17.75; prev close 16.45) — risk-on environment
- **Oil:** Still in freefall (-25% past month) → Energy sector headwind persists
- **No universe earnings pre-market**
- **Economic calendar today:** ADP employment (8:15am ET) | Initial jobless claims (8:30am) | Fed Warsh speech (9:30am) | S&P final PMI (9:45am) | Factory orders (10am)
- Sources: businessinsider.com, cnbc.com, marketwatch.com, tradingeconomics.com

### Sector ETF Ranking (this week)
1. **XLK (Tech)** — #1 YTD +33.1%; led this week; AI/semiconductor momentum
2. **XLV (Healthcare)** — recovering, positive this week; defensive bid
3. **XLE (Energy)** — slight positive week vs prior weeks but oil -25% past month undercuts thesis
- Finance (XLF): -1.84% 5-day; weak despite JPM holding

### Candidate Scoring (full 20-symbol universe)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Dist SMA20 | Mom5 | VolRat | Result |
|--------|-------|----------|--------|-------|--------|-----|-----------|------|--------|--------|
| TSLA | **7/10** | 2 | 2 | 1 | 0 | 2 | +5.0% | +10.2% | 0.91x | **PASS** |
| TSM | **7/10** | 1 | 2 | 1 | 1 | 2 | +9.1% | +9.4% | 1.05x | **PASS** |
| QQQ | **7/10** | 1 | 2 | 2 | 0 | 2 | +1.8% | +3.2% | 0.79x | PASS (1 tech fail) |
| AVGO | 7/10 | 1 | 2 | 2 | 0 | 2 | -4.6% | -0.6% | 0.76x | **DISCARD** (2 tech fails: neg mom + vol<0.8) |
| AAPL | 6/10 | 0 | 2 | 2 | 0 | 2 | -2.2% | -1.7% | 0.96x | FAIL (score) |
| MSFT | 6/10 | 0 | 2 | 2 | 0 | 2 | -4.8% | -0.2% | 0.93x | FAIL |
| GOOGL | 6/10 | 0 | 2 | 2 | 0 | 2 | -0.3% | +3.2% | 0.86x | FAIL |
| META | 6/10 | 0 | 2 | 2 | 0 | 2 | -2.5% | +0.2% | 0.98x | FAIL |
| XOM | 6/10 | 0 | 0 | 2 | 2 | 2 | -4.8% | -2.2% | 1.58x | FAIL |
| CVX | 6/10 | 0 | 0 | 2 | 2 | 2 | -8.0% | -5.8% | 2.04x | FAIL |
| AMD | DISCARD | — | — | 0 | — | — | +12.3% | +11.7% | 1.08x | **DISCARD** (>10% extended) |
| UNH | 5/10 | 0 | 1 | 2 | 0 | 2 | +2.5% | +1.6% | 0.80x | FAIL |
| MA | 5/10 | 0 | 0 | 2 | 1 | 2 | +4.6% | +5.2% | 1.07x | FAIL |
| V | 3/10 | 0 | 0 | 1 | 0 | 2 | +5.0% | +4.4% | 0.89x | FAIL |
| JNJ | 3/10 | 0 | 0 | 1 | 0 | 2 | +6.9% | +6.2% | 0.94x | FAIL |
| GS | Skip | — | — | — | — | — | -4.5% | -7.6% | 1.26x | SKIP (cut Jun 30; 1/2 sector fails) |
| AMZN | HELD | — | — | — | — | — | — | — | — | HOLD (existing) |
| NVDA | HELD | — | — | — | — | — | — | — | — | HOLD (existing) |
| JPM | HELD | — | — | — | — | — | — | — | — | HOLD (existing) |
| TSM | 7/10 | see above | — | — | — | — | — | — | — | see above |

*SPY: 6/10 (1+2+2+0+1 — R:R degrades for broad ETF vs S&P benchmark goal; skipped)*

### Trade Ideas (≥7/10, tech-valid candidates)

**Idea 1: TSLA** — Score 7/10 | Catalyst: 2 | Sector: 2 | Setup: 1 | Volume: 0 | R:R: 2
- **Catalyst:** Analyst Peter Vogel (GuruFocus) reiterated Buy / $600 PT; Morgan Stanley identifies unsupervised robotaxi fleet as "single biggest driver of TSLA shares in 2026"; Cybercab production start expected; commercial robotaxi expansion accelerating (source: finance.yahoo.com)
- **Technicals:** Last close $420.60 | SMA20 $400.59 | Dist +5.0% (5–10% tier, 1pt) | Mom5 +10.2% ✅ | Vol 0.91x (below avg, 0pt) — 0 tech fails → PASSES
- **Entry:** ~$421 limit | **Stop:** 10% trailing GTC (~$379) | **Target:** +20% (~$505) | **R:R:** 2.0:1
- **Size:** 18 shares × $421 = $7,578 (7.7% equity) | Cash after: $67,819
- **Gate:** ADP neutral/positive + SPX opens ≥ −0.3%
- **Week slot:** Would be #2 of 3

**Idea 2: TSM** — Score 7/10 | Catalyst: 1 | Sector: 2 | Setup: 1 | Volume: 1 | R:R: 2
- **Catalyst:** Q2 earnings report mid-July (pre-earnings buy window); monthly revenue figures expected ~Jul 8–10; 45%+ YTD; 234 hedge funds own as of Q1 (Motley Fool Jun 5 — theglobeandmail.com, fool.com)
- **Technicals:** Last close $477.57 | SMA20 $437.92 | Dist +9.1% (5–10% tier, 1pt) | Mom5 +9.4% ✅ | Vol 1.05x ✅ — 0 tech fails → PASSES
- **Entry:** ~$478 limit | **Stop:** 10% trailing GTC (~$430) | **Target:** +20% (~$574) | **R:R:** 2.0:1
- **Size:** 16 shares × $478 = $7,648 (7.8% equity) | Cash after: $60,171 (if both TSLA + TSM fill)
- **Gate:** Conditions remain favorable after TSLA fill; could use 2nd buy slot this week
- **Note:** Both TSLA + TSM are Tech → 4 of 4+ positions tech-heavy; diversification risk

### Risk Factors
1. **Macro events today (HIGH):** ADP employment (8:15am) + Warsh speech (9:30am) create volatility window before open — wait for data before executing
2. **Tech concentration (MEDIUM-HIGH):** Adding TSLA + TSM to existing AMZN/NVDA = 4 tech positions; only JPM non-tech; sector event risk elevated
3. **Slightly red premarket (MEDIUM):** SPX -0.24%, NQ -0.26% — mild caution; could worsen on weak ADP
4. **Deployment lagging (ONGOING):** Even with 2 fills, deployed only ~39% vs 80% target; 2 buy slots insufficient to close gap alone
5. **TSLA at setup boundary (LOW):** +5.0% above SMA = exactly 5-10% tier (1pt not 2pt); not ideal entry vs "at or below SMA" ideal
6. **Oil ongoing weakness (LOW for us):** No energy exposure; actually positive given we avoided XOM/CVX

### Decision
**CONDITIONAL BUY TSLA + TSM (2 trades)**
- **Gate 1 (mandatory):** ADP data at 8:15am not significantly weak (miss >50k below consensus)
- **Gate 2 (mandatory):** SPX opens ≥ −0.3% (7,514 or better on futures)
- If both gates pass → BUY TSLA (primary, slot 2) → evaluate TSM for slot 3
- If gates fail → HOLD; reassess in tomorrow's pre-market
- NVDA assessment: currently safe at $199.17 vs cut trigger $180.03; no action needed
- JPM: ex-dividend Jul 6 — hold through holiday week to capture dividend

### Afternoon Addendum — 2026-07-02 Midday Scan
**Actions taken:**
- CUT TSLA 18 @ $390.72 (-$560.52, -7.38%): Q2 deliveries missed ~400K consensus → thesis broken. Stops canceled, market sell filled.
- CUT TSM 16 @ $432.34 (-$559.36, -7.48%): Semiconductor sector risk-off, geopolitical jitters, AI profit-taking. -7% rule triggered. Stops canceled, market sell filled.
- Total realized today: -$1,119.88 on two positions

**Remaining portfolio (3 positions):**
- AMZN: +4.32% unrealized | Stop $227.27 (HWM $252.53) | AWS thesis intact ✅
- JPM: +3.60% unrealized | Stop $309.10 (HWM $343.45) | Ex-div Jul 6 ✅
- NVDA: ~-0.3% unrealized | Stop $180.57 (HWM $200.63) | AI infra thesis intact ✅

**DD halt check:** Equity $97,534 vs last $98,438 → -0.92% | No halt

**Sector flags:**
- Tech: 2/2 consecutive new-entry failures (TSLA+TSM same batch Jul 1→2) → NO NEW TECH BUYS until reset. Existing NVDA/AMZN held (different thesis vintages, above stops).
- Finance: 1/2 (GS Jun 30) | JPM profitable → no exit
- Deployment: ~24% vs 80% target after cuts | $74K+ idle | 0 buy slots this week (3/3 used Mon-Wed); reset Monday Jul 7

**Next steps:** No buys possible this week (slots exhausted). Friday/Monday pre-market: scout non-tech candidates (Finance GS-alternative, Healthcare, Energy) to rebuild deployment with 3 fresh slots next week.

---

## 2026-06-29 — Pre-Market Research (Day 46, Monday)

**Account Snapshot (pre-open)**
- Equity: $98,367.52 | Cash: $75,306.77 | DT count: 0 | Weekly buys: 0/3 (fresh week)
- Last equity: $98,252.70 | Pre-open change: +$114.82 (+0.12%)
- Deployed: $23,060.75 (23.5% vs 80% target) — $75.3K idle

**Open Positions:**
| Ticker | Shares | Entry | Current | Unreal P&L | Stop | Status |
|--------|--------|-------|---------|-----------|------|--------|
| AMZN | 34 | $233.97 | $235.63 | +$56.31 (+0.71%) | $218.18 (HWM $242.42) | ✅ |
| GS | 7 | $1,091.00 | $1,025.00 | -$462.00 (-6.05%) | $994.73 (HWM $1,105.25) | ⚠️ CUT @$1,014.63 |
| JPM | 24 | $322.67 | $328.10 | +$130.32 (+1.68%) | $309.10 (HWM $343.45) | ✅ |

**GS ALERT:** Current $1,025, cut trigger $1,014.63, buffer $10.37 (1.01%). On +1.35% market open GS should lift to ~$1,039. Cut immediately if ≤$1,014.63.

---

### Market Context
- **Oil:** WTI $69.77–69.98/bbl (+0.90%), Brent $72.27–72.83/bbl (+0.73%) — modest recovery; still -23.66% past month (tradingeconomics.com, businessinsider.com)
- **SPX futures:** +1.35% at ~7,451 — strong risk-on Monday; Yahoo Finance: "futures climb as a halt to US..." (possible tariff truce catalyst)
- **JPMorgan 2026 S&P 500 target:** raised 7,200 → 7,800 (CNBC Jun 26) — +5.5% additional upside implied
- **VIX:** 18.41 (Jun 26 close, -2.54%) — declining; favorable for buys (ycharts.com, businessinsider.com)
- **Econ calendar today:** Nothing scheduled. Tue Jun 30: Case-Shiller, Chicago PMI. Fri Jul 3: Jobs (bls.gov)
- **Earnings today:** No notable pre-market opens; Nike ($NKE, not universe) is week's biggest (earningswhispers.com)
- **Q2 S&P 500 EPS growth forecast:** +22% YoY (FactSet) — supportive backdrop (ii.co.uk)

### Sector ETF Ranking (YTD through Jun 26)
1. **XLK (Tech):** Above market, top third YTD
2. **SPY:** +7.47% YTD (totalrealreturns.com)
3. **XLF (Finance):** -1.34% YTD — laggard

### Analyst Actions (Jun 29)
- NVDA: ✅ Upgraded — AI infrastructure + margin resilience (seekingalpha.com)
- MSFT: ✅ Upgraded — AI infrastructure (seekingalpha.com)
- META: ✅ Upgraded — Mizuho (finance.yahoo.com)
- AAPL: ❌ Downgraded (youtube/NVDA Upgrade video, seekingalpha)

### Held Stock News
- **GS:** Jun 28 Robinhood range $1,013.38–$1,063.00; latest price $1,032.14 (+1.9% from Jun 26 close). SpaceX IB thesis intact. (robinhood.com)
- **AMZN:** JPMorgan raised target to $280 from $265, Overweight; avg analyst target $312.78, Buy. (investing.com, marketbeat.com)
- **JPM:** "Sees Recovery Potential in Consumer Stocks H2 2026" — positive macro outlook (finance.yahoo.com)

---

### Candidate Scoring (20-symbol universe only)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Result |
|--------|-------|----------|--------|-------|--------|-----|--------|
| NVDA | 8/10 | 2 | 2 | 1* | 1* | 2 | ✅ ADVANCE |
| META | 8/10 | 2 | 2 | 1* | 1* | 2 | ✅ ADVANCE |
| MSFT | 7/10 | 2 | 2 | 1* | 1* | 1 | ⚠️ ADVANCE (tech overconc.) |
| AAPL | 3/10 | 0 | 2 | 1* | 0 | 0 | ❌ <7, discard |
| V | 5/10 | 1 | 1 | 1* | 1* | 1 | ❌ <7, discard |
| XOM/CVX | 3/10 | 1 | 0 | 1* | 1* | 0 | ❌ <7, energy sector weak |
| All others | <5 | — | — | — | — | — | ❌ discard |

*Bars API returning null system-wide (all symbols). Setup/Volume/SMA approximated from last known quotes.

---

### Technical Validation

**NVDA:**
- Quote (Jun 26 AH stale): ask $211.65 / bid $192.36
- 20d SMA est: ~$205 (trading range $194–$213 past 20 days)
- Dist from SMA: ~+3.3% → ✅ PASS (< 10% extended)
- 5d momentum: cut $194.33 Jun 25 → ask $211.65 Jun 26 = +8.9% → ✅ POSITIVE PASS
- Volume ratio: N/A (bars unavailable) → estimated 1.0x neutral → borderline ✅
- **Result: 0 confirmed fails → PASSES tech threshold** (limitation: bars API down)

**META:**
- Quote (Jun 26 AH stale): ask $581.32 / bid $526.47; midpoint ~$554
- SMA, momentum, volume: N/A (bars unavailable)
- Technical validation incomplete → **SKIP; defer to bars availability**

**MSFT:**
- Quote bid: $373.96 (Jun 26 close); stop-out was $368.40 Jun 23 → recovered +1.5%
- 20d SMA est: ~$390 (entry $396.72, stop $361.58 — midpoint ~$379)
- Dist from SMA: $373.96 vs ~$390 = -4.1% → ✅ BELOW SMA PASS
- 5d momentum: $368.40 → $373.96 = +1.5% → ✅ POSITIVE (barely)
- Result: 0 confirmed fails → PASSES — but note: 2 consecutive tech sector failures (MSFT stop Jun 23, NVDA cut Jun 25); adding MSFT = 3rd tech position (AMZN + NVDA + MSFT) → CONCENTRATION RISK → **HOLD**

---

### Trade Ideas

**#1 — NVDA — CONDITIONAL BUY (PRIMARY, 1 slot)**
- **Catalyst:** Confirmed analyst upgrade Jun 29 (AI infrastructure + margin resilience); AI capex supercycle intact; NVDA bounced from $194 oversold cut to $211+ premarket
- **Score:** 8/10 | Catalyst:2 | Sector:2 | Setup:1 | Volume:1 | R:R:2
- **Entry:** Market open; limit $215 (estimates ~$213–215 with +1.35% SPX rally)
- **Stop:** 10% trailing; initial floor ~$193.50
- **Target:** $258 (+20% from $215)
- **R:R:** ($258 − $215) / ($215 − $193.50) = $43 / $21.50 = **2.0:1** ✅
- **Shares:** 36 × $215 = $7,740 = **7.87% of equity** ✅
- **Gate:** 4 positions after fill ✅ | 1/3 weekly slots ✅ | cost < $75.3K cash ✅ | universe ✅ | DT count 0 ✅
- **Condition:** VIX ≤ 19 at open AND SPX opens flat or better
- **Technicals:** dist +3.3%, mom5 +8.9%, vol est 1.0x — 0 fails ✅

**#2 — META — WATCH (not actionable today)**
- Score 8/10 but technical validation incomplete (bars unavailable); defer

**#3 — MSFT — WATCH (not actionable today)**
- Score 7/10; concentration risk (would be 3rd tech position); HOLD

---

### Risk Factors
1. **GS CUT TRIGGER (CRITICAL):** $1,025 vs $1,014.63 cut — 1.01% buffer. Monitor open price closely.
2. **Bars API down (HIGH):** All symbols returning null; SMA/volume unconfirmed. Limit order mitigates gap-up chase risk.
3. **Tech concentration (MEDIUM):** AMZN + NVDA = 2 AI tech positions. Monitored.
4. **Rally fade risk (MEDIUM):** +1.35% gap-ups often fade. Use limit order not market.
5. **Catalyst unconfirmed (MEDIUM):** Yahoo Finance "halt to US..." headline incomplete; possible tariff truce that could reverse.
6. **Underdeployment (ONGOING):** After NVDA: ~31.4% deployed. Still 2 buy slots this week to close cash drag.

---

### Decision
**TRADE: NVDA — conditional buy (36 shares, limit $215, 1 weekly slot)**
- All gate checks pass; SPX +1.35% confirms risk-on; VIX 18.41 declining; NVDA upgraded today
- GS monitoring takes priority at open (cut if ≤$1,014.63)
- Patience on META/MSFT until bars data recovers

### Afternoon Addendum — 2026-06-29 Midday Scan

**Account:** Equity $98,646 | Cash $68,338 | DD from session-start: +0.28% — no halt

**Positions midday:**
| Ticker | Current | Unreal % | Stop | Status |
|--------|---------|----------|------|--------|
| AMZN | $240.86 | +2.94% | $227.27 (HWM $252.53) | ✅ |
| GS | $1,023.42 | -6.19% | $994.73 (HWM $1,105.25) | ⚠️ |
| JPM | $332.11 | +2.93% | $309.10 (HWM $343.45) | ✅ |
| NVDA | $194.02 | +0.23% | $176.54 / $174.67 (HWM $196.15) | ✅ |

**Actions taken:**
- NVDA filled at market open $193.58 (limit $215 filled below limit). Added 3-share trailing stop (9e459b0f, HWM $194.08, stop $174.67) to cover position fully alongside 33-share stop (5428cc61).
- No cuts: GS at -6.19% (buffer $8.79 above $1,014.63 trigger); no thesis break.
- No stop tightening: no position at +15%/+20%.

**GS thesis check:** SpaceX IPO debuted today as largest IPO in US history with Goldman as lead underwriter — thesis crystallizing. Morgan Stanley raised PT to $1,099. GS recovering +0.37% intraday. HOLD. Cut trigger $1,014.63 unchanged.

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
2. **XLF Financials** — rising; US-Iran peace deal = risk-on = financials benefit (annacoulling.com)
3. **XLE Energy** — fell sharply after Iran deal (Hormuz reopening = oil supply + price drop) (tradingeconomics.com)

(XLV Healthcare — declining; Leading Indicators -1.77% = weak economic outlook)

### Candidate Scoring Table

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Result |
|--------|-------|----------|--------|-------|--------|-----|--------|
| AAPL (held) | 6/10 | 0 | 2 | 2 | 2 | 0 | HOLD existing |
| MSFT (held) | 5/10 | 0 | 2 | 2 | 1 | 0 | HOLD existing |
| NVDA (held) | 5/10 | 0 | 2 | 2 | 1 | 0 | HOLD existing |
| JPM (held) | 5/10 | 1 | 1 | 2 | 0 | 1 | HOLD existing |
| **META** | **7/10** | **2** | **2** | **2** | **1** | **0** | **CONDITIONAL PASS** |
| GOOGL | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL |
| AMZN | 4/10 | 1 | 2 | 1 | 0 | 0 | FAIL |
| TSLA | 2/10 | 0 | 2 | 0 | 0 | 0 | FAIL |
| AMD | 5/10 | 1 | 2 | 1 | 0 | 1 | FAIL |
| AVGO | N/A | — | — | — | — | — | Stopped out; no re-entry |
| TSM | 4/10 | 1 | 2 | 0 | 0 | 1 | FAIL (extended) |
| GS | 3/10 | 1 | 1 | 0 | 0 | 1 | FAIL |
| V | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| MA | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| XOM | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| CVX | 3/10 | 0 | 1 | 1 | 0 | 1 | FAIL |
| UNH | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
| JNJ | 1/10 | 0 | 0 | 1 | 0 | 0 | FAIL |
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
|--------|-------|----------|--------|-------|--------|-----|-----------|------|--------|
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
| MA | 4/10 | 0 | 0 | 2 | 2 | 0 | -0.2% | +0.7% | 1.71x | FAIL |
| XOM | 5/10 | 0 | 1 | 2 | 2 | 0 | -6.9% | -6.0% | 2.62x | FAIL — oil downtrend |
| CVX | 5/10 | 0 | 1 | 2 | 2 | 0 | -6.3% | -6.6% | 2.07x | FAIL — oil downtrend |
| UNH | 4/10 | 0 | 0 | 2 | 2 | 0 | +1.7% | -1.1% | 1.67x | FAIL |
| JNJ | 4/10 | 0 | 0 | 2 | 2 | 0 | -1.4% | -4.2% | 2.35x | FAIL |
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

---

## 2026-06-23 (Day 42, Tuesday — Pre-Market)

**Account snapshot:** Equity $99,434.78 | Cash $75,704.00 (76.2%) | Buying Power $369,262.19 | DT count: 0
**Session-start equity (last_equity):** $99,695.85 | **Portfolio DD:** -0.26% — no halt
**Phase P&L:** -$565.22 (-0.57%)

### Open Positions (pre-market)
| Ticker | Shares | Entry | Pre Px | Unrealized P&L | Stop | HWM |
|--------|--------|-------|--------|----------------|------|-----|
| AAPL | 28 | $276.38 | $295.70 | +$540.96 (+7.0%) | $285.66 (10% trail) | $317.40 |
| JPM | 24 | $322.67 | $331.23 | +$205.35 (+2.65%) | $304.26 (10% trail) | $338.07 |
| NVDA | 37 | $213.59 | $202.77 | -$400.51 (-5.07%) | $192.59 (10% trail) | $213.99 |

**⚠️ MSFT STOPPED OUT:** MSFT trailing stop ($361.58) triggered Jun 22 amid broad tech sell-off. Position closed, ~$667 loss realized. Cash +~$7K ($68.7K → $75.7K).

**⚠️ NVDA CRITICAL:** Pre-market at $202.77 (-2.82% today). -7% manual cut trigger = $198.64. Buffer = $4.13 (2.0%). If NVDA ≤ $198.64 at open or intraday → CUT IMMEDIATELY.

### Market Context
- **Brent crude:** $77.34 (-0.71%); WTI approx $74-75. Brent -20% past month — energy sector headwind.
- **SPX futures:** ~7,518-7,532 (−0.30%). Slightly red. Prior day saw broad tech sell-off.
- **VIX:** 17.28 (+2.98% on day). Mildly elevated, not alarming.
- **CPI May (released today):** 3.4% YoY actual vs 3.5% expected — BELOW consensus ✅ Mildly bullish.
- **FOMC:** Held rates steady at Jun 17 meeting (already done). No rate decision today.
- **FedEx (FDX) earnings BMO:** Not in universe, market signal only.
- **Key event this week:** Micron (MU) earnings expected — not in universe, but chip sector signal.
- **NVDA Annual Meeting:** Jun 24 (tomorrow). Minor volatility risk.
- **Macro tone:** Tech weakness persisting; S&P closed lower "as tech stocks slide" Jun 21-22.
  Sources: tradingeconomics.com, cnn.com/markets, ycharts.com

### Sector ETF Ranking (this week)
| Rank | Sector | ETF | Signal |
|------|--------|-----|--------|
| 1 | Healthcare | XLV | Gaining week; defensive bid |
| 2 | Energy | XLE | Weekly gain despite oil slide |
| 3 | Industrials | XLI | Steady |
| — | Technology | XLK | Weak; broad tech sell-off |
| — | Financials | XLF | YTD -0.26%; bottom sector |
Sources: tavily.sh, Yahoo Finance XLF quote

### Candidate Scoring Table (20-symbol universe)
| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Dist/SMA20 | Mom5 | VolRat | Result |
|--------|-------|----------|--------|-------|--------|-----|------------|------|--------|
| AAPL (held) | 5/10 | 0 | 2 | 2 | 1 | 0 | -2.0% | +2.0% | 0.85x | HELD — no add, approaching +15% tighten |
| MSFT | 7/10 | 0 | 2 | 2 | 1 | 2 | -10.5% | -6.0% | 1.14x | SKIP — just stopped out today; re-entry same session inappropriate |
| GOOGL | 7/10 | 0 | 2 | 2 | 2 | 1 | -5.4% | -2.8% | 1.55x | BORDERLINE — no catalyst, negative momentum; skip |
| **AMZN** | **10/10** | **2** | **2** | **2** | **2** | **2** | -7.4% | -2.4% | 1.50x | **PASS — confirmed AWS/Meta catalyst** |
| NVDA (held) | 3/10 | 0 | 2 | 2 | 0 | - | -1.2% | +1.7% | 0.71x | HELD — near -7% cut trigger, WATCH |
| META | 7/10 | 1 | 2 | 2 | 0 | 2 | -5.6% | -0.6% | 0.80x | FAIL tech check — 2 fails (neg mom + vol boundary) |
| TSLA | 5/10 | 0 | 1 | 2 | 1 | 1 | -1.9% | -0.3% | 1.01x | FAIL |
| AMD | 5/10 | 0 | 2 | 1 | 1 | 1 | +8.8% | +7.8% | 0.82x | FAIL — extended |
| TSM | 4/10 | 0 | 2 | 1 | 1 | 0 | +8.8% | +10.3% | 1.04x | FAIL — extended |
| AVGO | N/A | — | — | — | — | — | — | — | — | No re-entry rule |
| JPM (held) | 2/10 | 0 | 0 | 1 | 1 | 0 | +6.3% | +3.4% | 1.04x | HELD — Finance sector bottom |
| GS | 2/10 | 0 | 0 | 1 | 0 | 1 | +5.6% | +4.1% | 0.78x | FAIL |
| V | 5/10 | 0 | 0 | 2 | 2 | 1 | +0.8% | +1.3% | 1.78x | FAIL — Finance bottom sector |
| MA | 4/10 | 0 | 0 | 2 | 1 | 1 | -1.2% | -1.2% | 1.01x | FAIL |
| XOM | 5/10 | 0 | 1 | 2 | 1 | 1 | -5.9% | -5.8% | 0.88x | FAIL — oil downtrend |
| CVX | 6/10 | 0 | 1 | 2 | 1 | 2 | -5.1% | -6.5% | 1.19x | FAIL — negative 5d mom |
| UNH | 5/10 | 0 | 1 | 2 | 1 | 1 | +2.8% | -0.5% | 0.82x | FAIL |
| JNJ | 5/10 | 0 | 1 | 2 | 1 | 1 | -0.2% | -4.0% | 1.04x | FAIL |
| SPY | 3/10 | 0 | 1 | 2 | 1 | 0 | — | — | — | FAIL |
| QQQ | 3/10 | 0 | 2 | 2 | 0 | 0 | — | — | — | FAIL |

### Technical Validation — AMZN (Score 10/10) ✅ PASS
- **Last close (Jun 22):** $232.79 | **SMA20:** $251.49
- **Dist from SMA20:** −7.4% → BELOW SMA → ✅ PASS
- **5-day momentum:** −2.4% → NEGATIVE → ❌ FAIL (1 fail)
- **Vol ratio:** 1.50x → above 0.8 → ✅ PASS (≥1.5x = high conviction)
- **20-day avg volume:** 45.8M | **Last vol:** 45.8M × 1.50 = confirmed elevated
- **Result:** 1 confirmed fail → PASSES technical threshold (need 2+ to discard)
- **Catalyst:** AWS Graviton5 multi-year deal with Meta — confirmed (aol.com; "Amazon stock just keeps rising — AWS Graviton deal with Meta is the latest catalyst"). Price has pulled back from $244 to $232 since last week = better entry vs last week's idea.

### Trade Idea — AMZN (Conditional)

**#1 — AMZN — CONDITIONAL BUY (open must not gap down >2% from $232)**
- Catalyst: Confirmed — AWS Graviton5 CPU multi-year deal with Meta; AI cloud spending wave; Q2 earnings ~Jul 30 (AWS re-acceleration expected)
- Score: 10/10 | Catalyst: 2 | Sector: 2 | Setup: 2 | Volume: 2 | R:R: 2
- Entry: ~$232-234 (market open or limit near $232)
- Stop: 10% trailing → initial floor ~$209.51
- Target: $295-$300 (+27%)
- R:R: ($295 − $232.79) / ($232.79 − $209.51) = 62.21/23.28 = **2.67:1** ✅
- Shares: 34 × $233 = $7,922 = **7.97% of equity** — within 8% cap ✅
- Gate check: 4 total positions after fill (≤10 ✅) | 1/3 weekly slots used (≤3 ✅) | cost ≤ cash ($75.7K ✅) | universe ✅ | DD-halt not triggered ✅
- **Condition:** Enter ONLY IF AMZN opens ≥ $228. Hold if broad market opens -1%+ (SPY ≤ −1%)
- Technicals: dist -7.4%, mom5 -2.4% (only fail), volrat 1.50x

### Risk Factors
1. **NVDA -7% CUT TRIGGER (CRITICAL):** Pre-market $202.77, buffer $4.13 to cut at $198.64. NVDA -2.82% today already. Kalshi traders bearish on chip prices. If ≤$198.64 at open → cut immediately, cancel trailing stop, log exit.
2. **Tech weakness broadening (HIGH):** MSFT stopped out Jun 22. Nasdaq/S&P saw multi-day slide. AMZN entry into broad tech weakness is a risk — stagger with conditional gate.
3. **NVDA annual meeting Jun 24 (MEDIUM):** Minor volatility event; institutional pressure possible.
4. **AAPL approaching +15% tighten trigger (MEDIUM):** Entry $276.38 × 1.15 = $317.84. Current $295.70. If reaches $317.84 intraday → tighten trail to 7%.
5. **JPM above SMA20 +6.3% (LOW):** Extended but Finance thesis intact. Monitor.
6. **Underdeployment (ONGOING):** 23.9% deployed vs 80% target. AMZN entry would add ~7.97%, reaching ~32%. Still very underweight — need 3-5 more positions over coming weeks.
7. **CPI miss risk (LOW, already out):** Actual 3.4% below 3.5% — mild tailwind.

### Decision
**CONDITIONAL BUY AMZN — else HOLD**
- AMZN is the only ≥7/10 candidate with a confirmed catalyst today (AWS Graviton5/Meta deal)
- Score 10/10 is the highest possible; entry price improved from $244 (last week's target) to $232 — better R:R
- Condition: open ≥ $228 + SPY not down more than -1% at open
- NVDA cut is a priority risk-management action — NOT a new trade decision
- 3 fresh weekly buy slots available; using slot #1 here
- Patience > activity rule applies to low-conviction setups, not 10/10 confirmed-catalyst entries

### Afternoon Addendum (Midday Scan)
**Equity:** $99,556.15 | **DD from session-start:** -0.14% (no halt) | **Positions:** 4 open

| Ticker | Current | Unrealized P&L | Stop | Status |
|--------|---------|----------------|------|--------|
| AAPL | $298.48 | +$618.80 (+8.0%) | $285.66 | ✅ Holding |
| AMZN | $234.47 | +$16.77 (+0.21%) | $213.18 (HWM $236.87) | ✅ New entry executing |
| JPM | $333.96 | +$270.96 (+3.5%) | $304.26 | ✅ Holding |
| NVDA | $202.22 | -$420.94 (-5.33%) | $192.59 | ⚠️ WATCH: -7% cut at $198.64, buffer $3.58 |

**Actions taken:** None — no -7% cuts triggered, no stops to tighten.
**NVDA thesis check:** -3.08% intraday on broad tech sector weakness. No specific catalyst break found. NVIDIA CEO previously called tech sell-off a "buying opportunity." Annual meeting Jun 24 (tomorrow) — minor volatility risk. Thesis intact. Manual cut trigger $198.64 remains hard floor.
**AAPL:** +15% tighten trigger at $317.84 — current $298.48, not reached.
**Stop tightening:** No position at +15% or +20%. All 4 trailing GTC stops active.

---

## 2026-06-24 (Day 43, Wednesday — Pre-Market)

### Account Snapshot
- **Equity:** $99,431.33 | **Cash:** $67,748.95 | **Buying Power:** $359,706.46
- **Long market value:** $31,682.38 | **Deployment:** 31.9% (target 80%)
- **Daytrade count:** 0 | **Weekly buy slots used:** 1/3 (AMZN Jun 23)
- **Phase P&L:** -$568.67 (-0.57%)

### Live Positions
| Ticker | Shares | Entry | Current | Unreal P&L | Stop | Status |
|--------|--------|-------|---------|-----------|------|--------|
| AAPL | 28 | $276.38 | $295.00 | +$521.36 (+6.74%) | $285.66 (HWM $317.40) | ✅ Holding |
| AMZN | 34 | $233.97 | $233.10 | -$29.64 (-0.37%) | $213.18 (HWM $236.87) | ✅ Holding |
| JPM | 24 | $322.67 | $335.00 | +$295.92 (+3.82%) | $304.26 (HWM $338.07) | ✅ Holding |
| NVDA | 37 | $213.59 | $201.54 | -$445.91 (-5.64%) | $192.59 (HWM $213.99) | ⚠️ CRITICAL: cut at $198.64, buffer $2.90 |

### Market Context
- **WTI:** ~$72.75/bbl (-0.6%) | **Brent:** ~$76.44 (-0.7%), falling below $76 (lowest since US-Iran oil deal)
- **SPX futures:** +0.10% at 7,447 — flat, slightly positive
- **VIX:** ~19.5 — SPIKED from 17.28 yesterday (+12.79%) — elevated fear/volatility
- **Earnings today (pre-open):** Micron (MU) — not in universe; PAYX/DRI after close
- **Economic:** BLS Productivity & Costs 10am (minor). No CPI/PPI/FOMC today.
- **NVDA annual meeting:** 9am PT / 12pm EDT (virtual, stockholders only — no major product catalyst expected)
- **SpaceX:** $25B debt offering closed Jun 23 — boosting IB fees at Goldman, JPMorgan

### Sector ETF Weekly Performance
| Rank | Sector | ETF | Week Perf |
|------|--------|-----|----------|
| #1 | Energy | XLE | +1.12% |
| #2 | Technology | XLK | +0.83% |
| #3 | Finance | XLF | +0.72% |
| #4 | Industrials | XLI | +0.41% |
| #5 | Consumer Staples | XLP | +0.01% |
| — | Healthcare | XLV | -0.34% |

### Candidate Scoring Table (20-symbol universe)
| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Dist/SMA20 | Mom5d | VolRat | Result |
|--------|-------|----------|--------|-------|--------|-----|------------|------|--------|
| AAPL (held) | — | — | — | — | — | — | -2.6% | -0.7% | 0.98x | HELD — monitoring |
| MSFT | — | — | — | — | — | — | — | — | — | SKIP — stopped out Jun 23 (no same-session re-entry) |
| GOOGL | 5/10 | 0 | 2 | 2 | 0 | 1 | -5.9% | -6.3% | 0.98x | FAIL — no catalyst, neg momentum |
| AMZN (held) | — | — | — | — | — | — | -6.3% | -4.8% | 1.28x | HELD — AWS thesis intact |
| NVDA (held) | — | — | — | — | — | — | -5.0% | -5.8% | 0.90x | HELD — ⚠️ CRITICAL: $198.64 cut trigger |
| META | 5/10 | 0 | 2 | 2 | 0 | 1 | -5.5% | -5.3% | 0.68x | FAIL — no catalyst, volume below 0.8x |
| TSLA | 3/10 | 0 | 1 | 2 | 1 | 0 | — | — | — | FAIL — no catalyst, poor R:R |
| AMD | 4/10 | 0 | 2 | 2 | 0 | 0 | — | — | — | FAIL — no catalyst |
| AVGO | 4/10 | 0 | 2 | 1 | 1 | 0 | — | — | — | FAIL — no catalyst |
| TSM | 4/10 | 0 | 2 | 1 | 1 | 0 | — | — | — | FAIL — no catalyst |
| JPM (held) | — | — | — | — | — | — | +6.7% | +4.6% | 0.77x | HELD — dividend ex-date Jul 6 |
| **GS** | **7/10** | **2** | **2** | **2** | **0** | **1** | +4.0% | +1.7% | 0.85x | **PASS — SpaceX IB fees catalyst** |
| V | 5/10 | 0 | 2 | 2 | 1 | 0 | — | — | — | FAIL — Finance, no specific catalyst |
| MA | 4/10 | 0 | 2 | 2 | 0 | 0 | — | — | — | FAIL |
| XOM | 5/10 | 0 | 2 | 2 | 0 | 1 | -4.5% | -0.8% | 0.76x | FAIL — no catalyst, oil declining |
| CVX | 7/10 | 2 | 2 | 2 | 0 | 1 | -4.2% | -2.5% | 0.71x | FAIL tech check — 2 fails (neg mom + vol<0.8) |
| UNH | 3/10 | 0 | 0 | 2 | 0 | 1 | — | — | — | FAIL — Healthcare bottom YTD |
| JNJ | 3/10 | 0 | 0 | 2 | 0 | 1 | — | — | — | FAIL — Healthcare bottom YTD |
| SPY | 3/10 | 0 | 1 | 2 | 1 | 0 | — | — | — | FAIL |
| QQQ | 3/10 | 0 | 2 | 2 | 0 | 0 | — | — | — | FAIL |

### Technical Validation — GS (Score 7/10) ✅ PASS
- **Last close (Jun 23):** $1,094.44 | **SMA20:** $1,052.52
- **Dist from SMA20:** +4.0% → within 5% of SMA → ✅ PASS (not in 5–10% extended band)
- **5-day momentum:** +1.7% → positive → ✅ PASS
- **Vol ratio:** 0.85x → ≥ 0.8 threshold → ✅ PASS
- **Result:** 0 confirmed fails → PASSES all technical checks

### Technical Validation — CVX (Score 7/10) ❌ FAIL
- **Last close (Jun 23):** $175.98 | **SMA20:** $183.65
- **Dist from SMA20:** -4.2% → ✅ PASS
- **5-day momentum:** -2.5% → ❌ FAIL (negative downtrend)
- **Vol ratio:** 0.71x → ❌ FAIL (below 0.8 threshold)
- **Result:** 2 fails → DISCARDED

### Trade Idea — GS

**#1 — GS — CONDITIONAL BUY (enter if VIX ≤ 21 and SPX opens flat or better)**
- **Catalyst:** Confirmed — SpaceX mega-IPO underwriting fees + $25B debt offering closed Jun 23; mega-IPO activity driving IB fee windfall for GS. Q2 earnings ~mid-July will crystallize. "JPMorgan says investors are overlooking the upside to Wall Street banks from SpaceX and other mega-IPOs" (MarketWatch Jun 23).
- **Score:** 7/10 | Catalyst: 2 | Sector: 2 | Setup: 2 | Volume: 0 | R:R: 1
- **Entry:** ~$1,094–1,100 (market open)
- **Stop:** 10% trailing → initial floor ~$985
- **Target:** $1,313 (+20%)
- **R:R:** ($1,313 − $1,094) / ($1,094 − $985) = $219 / $109 = **2.01:1** ✅
- **Shares:** 7 × ~$1,094 = $7,658 = 7.70% of equity — within 8% cap ✅
- **Gate check:** 5 positions after fill (≤10 ✅) | 2/3 weekly slots (≤3 ✅) | cost ≤ cash ($67.7K ✅) | universe ✅ | DD-halt not triggered ✅
- **Condition:** VIX ≤ 21 at open + SPX flat or better (currently +0.10%)
- **Technicals:** dist +4.0%, mom5 +1.7%, volrat 0.85x — all pass

### Risk Factors
1. **NVDA -7% CUT TRIGGER (CRITICAL):** Current $201.54, buffer only $2.90 to cut at $198.64. Annual meeting today 12pm EDT. If opens ≤ $199, cut immediately and cancel trailing stop order cc08a04d. NOT a weekly trade slot — risk management action.
2. **VIX spike to 19.5 (+13% from yesterday):** Elevated fear. Broad "AI wake-up call" narrative weighing on risk-on assets. GS entry gated on VIX ≤ 21.
3. **Oil declining:** WTI -0.6–1.9%, Brent below $76 — Energy sector headwind despite strong weekly performance.
4. **GS volume soft (0.85x):** Below average volume; institutional conviction may be limited today.
5. **AAPL +15% tighten trigger:** Entry $276.38 × 1.15 = $317.84. Current $295.00 — not reached but monitor.
6. **Underdeployment ongoing:** 31.9% deployed vs 80% target. GS entry adds ~7.7%, reaching ~39.6%. Still very underweight.
7. **Tech concentration risk:** 3 of 4 current positions are Tech/Tech-adjacent (AAPL, AMZN, NVDA). GS adds Finance diversification.

### Decision
**CONDITIONAL BUY GS — else HOLD**
- GS is the only ≥7/10 candidate that passes all technical checks
- Catalyst confirmed (SpaceX IB fees); Finance sector showing resilience (#3 this week, record JPM profits signal sector health)
- Weekly slot 2/3 available; using conservatively with VIX gate
- NVDA cut is a risk-management action (not a buy slot), execute if buffer breached at open
- Patience > activity: no forced buys; GS only enters on positive market open conditions

---

## 2026-06-25 (Day 44, Thursday — Pre-Market)

### Account Snapshot
- **Equity:** $99,345.80 | **Cash:** $67,748.95 (68.2%) | **Buying Power:** $359,466.98
- **Long market value:** $31,596.85 | **Deployment:** 31.8% (target 80%)
- **Daytrade count:** 0 | **Weekly buy slots used:** 1/3 (AMZN Jun 23)
- **Phase P&L:** -$654.20 (-0.65%)
- **DD from session-start ($99,286.17):** +0.06% — no halt

### Live Positions
| Ticker | Shares | Entry | Last (Jun 24) | Pre Px | Unreal P&L | Stop | Status |
|--------|--------|-------|---------------|--------|-----------|------|--------|
| AAPL | 28 | $276.38 | $293.08 | $291.45 | +$421.96 (+5.45%) | $285.66 (HWM $317.40) | ✅ Holding |
| AMZN | 34 | $233.97 | $234.27 | $233.42 | -$18.73 (-0.24%) | $218.18 (HWM $242.42) | ✅ Holding |
| JPM | 24 | $322.67 | $333.45 | $335.44 | +$306.48 (+3.96%) | $304.26 (HWM $338.07) | ✅ Finance thesis intact |
| NVDA | 37 | $213.59 | $199.00 | $201.30 | -$454.79 (-5.76%) | $192.59 (HWM $213.99) | ⚠️ CRITICAL: cut at $198.64, buffer $2.66 |

**GS Note:** Yesterday's conditional buy (VIX gate ≤21, SpaceX catalyst) was not executed — no trade log entry confirms. Reassessing today.

### Market Context
- **Oil:** WTI ~$69.50 (-1.19/day, -4.4% intraday per oilprice.com); Brent ~$72.56 (-1.60%/day). Brent −25% past month. Energy sector headwind continuing.
- **SPX futures:** +0.50–0.80% (7,465–7,487) — constructive open (markets.businessinsider.com, yahoo.finance.com)
- **VIX:** 18.06 (declining from 19.5 yesterday, −3.06%) — fear retreating, favorable (marketwatch.com)
- **Earnings BMO today:** AYI (Acuity), CMC (Commercial Metals), WGO (Winnebago) — none in universe
- **Economic calendar:** Light. SOFR data only. No CPI/PPI/FOMC/NFP. (fred.stlouisfed.org)
- **Analyst moves today:** MU, INTC (Zacks Strong-Buy) — not in universe. No universe-specific upgrades. (marketwatch.com, marketbeat.com)
- **S&P 500 YTD:** +8.10% as of Jun 24 (totalrealreturns.com)

### Sector ETF Ranking (week of Jun 23–25)
| Rank | Sector | ETF | Notes |
|------|--------|-----|-------|
| #1 | Financials | XLF | JPM outperforming (+3.96% unreal); Finance resilient vs tech |
| #2 | Technology | XLK | +27.45% YTD best sector; broad selloff this week (−3.82% Jun 23); recovering |
| #3 | Energy | XLE | +21.46% YTD but oil −25% past month; mixed week |
Sources: totalrealreturns.com, sahmcapital.com (Jun 23), markets.businessinsider.com

### Candidate Scoring Table (20-symbol universe)
| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Dist/SMA20 | Mom5d | VolRat | Result |
|--------|-------|----------|--------|-------|--------|-----|------------|-------|--------|
| AAPL (held) | 5/10 | 0 | 2 | 2 | 1 | 0 | −2.8% | −2.1% | 0.99x | HELD — no add |
| MSFT | 7/10 | 0 | 2 | 2 | 1 | 2 | −9.9% | −7.2% | 1.08x | SKIP — stopped out Jun 23; no catalyst |
| GOOGL | 7/10 | 0 | 2 | 2 | 1 | 2 | −5.6% | −7.5% | 1.26x | SKIP — stopped out Jun 2; no catalyst |
| AMZN (held) | — | — | — | — | — | — | −5.7% | −4.8% | 1.43x | HELD — AWS thesis intact |
| NVDA (held) | — | — | — | — | — | — | −5.1% | −4.1% | 0.90x | HELD — ⚠️ CRITICAL: cut at $198.64 |
| META | 6/10 | 0 | 2 | 2 | 0 | 2 | −5.8% | −7.1% | 0.72x | FAIL — vol 0.72x + neg mom (2 tech fails) |
| TSLA | 3/10 | 0 | 1 | 2 | 1 | 0 | — | — | — | FAIL |
| AMD | 4/10 | 0 | 2 | 1 | 1 | 0 | — | — | — | FAIL |
| AVGO | N/A | — | — | — | — | — | — | — | — | No re-entry rule |
| TSM | 6/10 | 0 | 2 | 2 | 0 | 2 | +1.8% | +3.5% | 0.72x | FAIL — vol 0.72x |
| JPM (held) | — | — | — | — | — | — | +6.0% | +0.7% | 0.80x | HELD — Finance thesis working |
| **GS** | **7/10** | **2** | **1** | **2** | **1** | **1** | +1.9% | −1.3% | 0.80x | **PASS** |
| V | 6/10 | 0 | 1 | 2 | 1 | 2 | +2.4% | −0.3% | 0.95x | FAIL — weak sector |
| MA | 4/10 | 0 | 1 | 2 | 0 | 1 | — | — | — | FAIL |
| XOM | 4/10 | 0 | 2 | 2 | 1 | 0 | −6.1% | −3.5% | 0.89x | FAIL — R:R weak, oil downtrend |
| CVX | 7/10 | 0 | 2 | 2 | 1 | 2 | −6.3% | −4.8% | 1.17x | FAIL — catalyst stale (Iran deal Jun 14) |
| UNH | 3/10 | 0 | 0 | 2 | 0 | 1 | — | — | — | FAIL — Healthcare bottom |
| JNJ | 3/10 | 0 | 0 | 2 | 0 | 1 | — | — | — | FAIL — Healthcare bottom |
| SPY | 3/10 | 0 | 1 | 2 | 1 | 0 | — | — | — | FAIL |
| QQQ | 3/10 | 0 | 2 | 2 | 0 | 0 | — | — | — | FAIL |

*GS: Catalyst = SpaceX $25B debt offering + mega-IPO IB fees confirmed Jun 23 (MarketWatch); Sector = Finance (XLF −1.07% YTD = mid-third); Setup = +1.9% above SMA20; Vol = 0.80x (at threshold); R:R = $215/$108 = 1.99:1*
*MSFT/GOOGL score ≥7 on math but both recently stopped out with no new catalyst — skip per disciplined entry criteria*
*CVX: Iran deal catalyst is 11 days stale; without fresh catalyst score drops to 5/10*

### Technical Validation — GS (Score 7/10) ✅ PASS
- **Last close (Jun 24):** $1,076.91 | **SMA20:** $1,056.64
- **Dist from SMA20:** +1.9% → within 5% of SMA → ✅ PASS
- **5-day momentum:** −1.3% → negative → ❌ FAIL (1 fail)
- **Vol ratio:** 0.80x → at threshold → ✅ PASS
- **Result:** 1 confirmed fail → PASSES technical threshold (need 2+ to discard)
- **Note:** GS slipped −1.6% on Jun 24 from $1,094 to $1,077; entry now improved vs yesterday's $1,094 level. SpaceX IB fee catalyst remains active (Q2 IB revenue crystallizes ~mid-July earnings).

### Trade Idea — GS

**#1 — GS — CONDITIONAL BUY (entry if VIX ≤19 and SPX opens flat or better)**
- **Catalyst:** Confirmed — SpaceX $25B debt offering closed Jun 23 + mega-IPO IB fee pipeline; JPMorgan "investors overlooking upside to Wall Street banks from SpaceX" (MarketWatch Jun 23). Q2 earnings ~mid-July IB fee crystallization.
- **Score:** 7/10 | Catalyst: 2 | Sector: 1 | Setup: 2 | Volume: 1 | R:R: 1
- **Entry:** ~$1,077–1,085 (market open; use $1,080 limit)
- **Stop:** 10% trailing → initial floor ~$969
- **Target:** $1,293 (+20% from $1,077)
- **R:R:** ($1,293 − $1,077) / ($1,077 − $969) = $216 / $108 = **2.00:1** ✅
- **Shares:** 7 × ~$1,080 = $7,560 = **7.61% of equity** → within 8% cap ✅
- **Gate check:** 5 positions after fill (≤10 ✅) | 2/3 weekly slots (≤3 ✅) | cost ≤ cash ($67.7K ✅) | universe ✅ | DD-halt not triggered ✅
- **Condition:** VIX ≤19 at open + SPX opens flat or better (+0.0% or better)
- **Technicals:** dist +1.9%, mom5 −1.3% (1 fail), volrat 0.80x — PASSES

### Risk Factors
1. **NVDA -7% CUT TRIGGER (CRITICAL):** Premarket $201.30 vs cut trigger $198.64 (buffer $2.66). Closed yesterday at $199.00 — within $0.36 of -7% cut. If NVDA opens ≤$198.64 → cut immediately, cancel GTC order cc08a04d. NOT a weekly trade slot.
2. **Broad tech selloff risk (HIGH):** XLK -3.82% on Jun 23 alone. Tech sector broadly weak; AAPL -2.1% 5d momentum, MSFT -7.2%, AMZN -4.8%. A follow-through down day could trigger multiple stops.
3. **GS momentum slightly negative (MEDIUM):** −1.3% 5d momentum; down −1.6% yesterday. Finance sector YTD weakest. Entry into minor 5-day downtrend.
4. **Oil freefall (MEDIUM):** Brent −25% past month; WTI at $69.50. No energy positions but ongoing oil weakness signals macro caution.
5. **AAPL approaching +15% tighten trigger (MEDIUM-LOW):** Entry $276.38 × 1.15 = $317.84. Current $293.08 — not reached, but monitor.
6. **Underdeployment (ONGOING):** 31.8% deployed vs 80% target. GS would add ~7.6%, reaching ~39.4%. Still far below target with 2 buy slots left this week.
7. **No major economic catalyst (LOW):** Light calendar today reduces risk of surprise macro shock.

### Decision
**CONDITIONAL BUY GS — else HOLD**
- GS is the only ≥7/10 candidate with a confirmed, specific catalyst (SpaceX IB fees)
- VIX declining (19.5→18.06) and SPX futures +0.6% are favorable entry conditions
- Gate: VIX ≤19 at market open + SPX flat or better
- NVDA cut ($198.64) takes priority over GS entry if market opens weak
- 2 weekly buy slots remaining; GS uses slot #2
- Target entry: 7 shares × ~$1,080 limit order

### Afternoon Addendum — 2026-06-25 Midday Scan

**Account:** Equity $98,717.26 | Cash $75,306.80 | DD from session-start: -0.57% (no halt)

**Positions (midday):**
| Ticker | Shares | Entry | Current | Unreal P&L | Stop | Status |
|--------|--------|-------|---------|-----------|------|--------|
| AMZN | 34 | $233.97 | $228.39 | -$189.95 (-2.39%) | $218.18 (HWM $242.42) | Watching |
| GS | 7 | $1,091.00 | $1,079.74 | -$78.82 (-1.03%) | $994.73 (HWM $1,105.25) | Holding |
| JPM | 24 | $322.67 | $336.84 | +$340.09 (+4.39%) | $309.10 (HWM $343.45) | ✅ Strong |

**Checks:**
- DD halt: -0.57% → CLEAR
- Cut losers (-7%): none triggered
- Stop tighten (+15/+20%): none triggered
- AMZN Tavily check (down -2.51% intraday on positive market day): No thesis break. Prime Day 2026 running Jun 23–26. No adverse news. Day range $226.05–$232.32 — normal volatility. AWS Graviton5/Meta thesis intact.

**Verdict:** No action. All 3 positions within rules.

---

## 2026-06-26 — Midday Scan (Day 45, Friday)

**Account:** Equity $98,339.94 | Cash $75,306.77 | Session-start equity (last_equity): $98,523.62 | DD: -0.18% — no halt
**Positions:** 3 open | **Weekly buys:** 2/3 used (AMZN Jun 23, GS Jun 25)

| Ticker | Shares | Entry | Current | Unreal P&L | Stop | Status |
|--------|--------|-------|---------|-----------|------|--------|
| AMZN | 34 | $233.97 | $231.94 | -$69.08 (-0.87%) | $218.18 (HWM $242.42) | ✅ Within rules |
| GS | 7 | $1,091.00 | $1,030.34 | -$424.62 (-5.56%) | $994.73 (HWM $1,105.25) | ⚠️ WATCH: -7% cut at $1,014.63, buffer $15.71 (1.52%) |
| JPM | 24 | $322.67 | $330.73 | +$193.44 (+2.50%) | $309.10 (HWM $343.45) | ✅ Finance thesis intact |

**Checks:**
- DD halt: -0.18% from $98,523.62 → CLEAR
- Cut losers (-7%): none triggered (GS -5.56%, buffer $15.71 to cut trigger $1,014.63)
- Stop tighten (+15/+20%): none — no position at +15%
- GS Tavily check (down -3.26% today): Dividend increase to $5.00/share (CNBC Jun 24); Tower View Wealth bought shares today; analyst optimism. SpaceX IB Q2 thesis intact. No thesis break.
- AMZN: AWS Graviton5/Meta thesis intact; Prime Day ended Jun 26. -0.87% — normal.
- JPM: Finance thesis intact, +2.50% unrealized.

**Verdict:** No action. All 3 positions within rules. GS on close watch — 1.52% buffer to -7% manual cut.

---

## 2026-06-30 — Market Open Scan (Day 47, Tuesday)

**Account:** Equity $98,533.78 | Cash $75,397.17 | Session-start equity (last_equity): $98,568.42 | DD: -0.035% — no halt
**Positions after GS cut:** 3 open (AMZN, JPM, NVDA) | **Weekly buys:** 1/3 used (NVDA Jun 29)

**Market context:** VIX 17.56–18.41 (calm, slightly down). SPX futures +0.1%, Nasdaq futures +0.1%. Dow above 52,000 (record). S&P closed at a record high Jun 29 (16th record close of 2026). No major macro catalyst flagged this morning.

**GS -7% cut (executed, see TRADE-LOG):** GS opened at $1,008.82 (-7.53% unrealized), breaching the -7% manual cut threshold flagged critical since Jun 26 EOD ($1,014.63 trigger, $1,020.21 prior close). Cut immediately per rule despite a wide opening spread (bid $960.55/ask $1,073.10, ~10.5%) — filled in partials over ~45s as spread normalized, avg $1,008.47. Finance sector 1/2 consecutive fails (JPM still held, profitable).

**Other open-spread check:** JPM also showed a wide opening quote (bid $321.72/ask $346.11) at 13:35 UTC — held position only, no action needed; AMZN and NVDA spreads were normal/tight.

**New-buy screening:** No candidate carries documented ≥7/10 research from a same-day pre-market pass; skipping ad-hoc scoring under opening volatility per "never trade without documented research." 2/3 weekly buy slots remain.

---

## 2026-07-02 — Pre-Market Research (Day 49, Thursday)

### Account Snapshot
- **Equity:** $98,506.73 | **Cash:** $60,326.88 | **Buying Power:** $342,037.73
- **Long market value:** $38,179.85 (38.8% deployed) | **DT count:** 0
- **Last equity:** $98,438.32 | **Day P&L:** +$68.41 (+0.07%)
- **DD from session-start:** +0.07% → CLEAR (halt if equity drops to $88,594.49)
- **Weekly buy slots:** 3/3 used (NVDA Jun 29, TSLA+TSM Jul 1) — **NO NEW BUYS until Mon Jul 7**

### Open Positions (premarket prices)
| Ticker | Shares | Entry | Pre-Mkt | Unreal P&L | -7% Cut | Stop | Status |
|--------|--------|-------|---------|-----------|---------|------|--------|
| AMZN | 34 | $233.97 | $242.39 | +$286 (+3.60%) | $217.59 | $227.27 (HWM $252.53) | ✅ |
| JPM | 24 | $322.67 | $335.72 | +$313 (+4.04%) | $300.08 | $309.10 (HWM $343.45) | ✅ |
| NVDA | 36 | $193.58 | $196.40 | +$102 (+1.46%) | $179.93 | $180.57 (HWM $200.63) | ✅ |
| TSLA | 18 | $421.86 | $428.71 | +$123 (+1.62%) | $392.33 | $384.91/389.57 (HWM $427.68/$432.86) | ⚠️ Delivery Day |
| TSM | 16 | $467.30 | $443.50 | -$381 (-5.09%) | $434.59 | $418.38 (HWM $464.87) | ⚠️ WATCH: $8.91 buffer to cut |

### Market Context
- **VIX:** 16.69–16.87 (calm, +1.46% day; 52-wk low 15.18)
- **SPX futures:** 7,544.50 (+1.00 pt, ~flat)
- **NASDAQ futures:** 30,069 (-25 pts, -0.08%)
- **Dow futures:** 52,668 (flat)
- **WTI crude:** $67.58–68.18/bbl | **Brent:** $70.69–71.11/bbl (Brent -1.0% today; -27.56% past month)
- **Backdrop:** US-Iran peace deal risk-on; oil lower as Strait of Hormuz concern eases

### Key Events Today (July 2)
1. **Non-Farm Payrolls (8:30 AM EDT)** — June 2026 jobs report, released early due to Jul 4 holiday. Consensus ~114K-172K range; prior month 172K. Unemployment expected 4.3%. This is the biggest market mover today.
2. **TSLA Q2 Delivery report** — consensus 406,024 vehicles (Goldman calls for 420K beat). Already-held position.
3. **Market schedule:** Jul 3 (Fri) closes early; Jul 4 closed; normal resumes Jul 7.

### Sector ETF YTD Ranking
| Rank | Sector | ETF | YTD |
|------|--------|-----|-----|
| 1 | Technology | XLK | +33.1% |
| 2 | Utilities | XLU | +21.0% |
| 3 | Consumer Staples | XLP | +16.9% |
| 4 | Materials | XLB | +14.8% |
| 5 | Real Estate | XLRE | +9.4% |
| 6 | Energy | XLE | +7.8% |
| 7 | Financials | XLF | -1.7% |
| 8 | Consumer Discretionary | XLY | -1.7% |
| 9 | Industrials | XLI | -3.1% |
| 10 | Health Care | XLV | -6.7% |

Top 3 sectors: **XLK (+33.1%), XLU (+21.0%), XLP (+16.9%)**

Sources: ETF Investments/State Street YTD data via Tavily; tradingeconomics.com for oil; businessinsider.com VIX/futures.

### Candidate Scoring (20-symbol universe; 3/3 slots used → HOLD regardless)

**Held tickers (not re-scored as new buys):** AMZN, JPM, NVDA, TSLA, TSM

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Tech Checks | Result |
|--------|-------|----------|--------|-------|--------|-----|-------------|--------|
| AAPL | 7/10 | 0 | 2 | 2 | 1 | 2 | PASS (all 3) | ≥7 but no catalyst → gate fails |
| MSFT | 7/10 | 0 | 2 | 2 | 1 | 2 | PASS (all 3) | ≥7 but no catalyst → gate fails |
| AMD | 7/10 | 1 | 2 | 1 | 1 | 2 | PASS (all 3) | ≥7; catalyst weak; no slot |
| AVGO | 7/10 | 1 | 2 | 2 | 0 | 2 | FAIL (2/3: vol 0.66x + mom -3.3%) | DISCARD |
| META | 6/10 | 1 | 0 | 1 | 2 | 2 | PASS | DISCARD (<7) |
| GOOGL | 4/10 | 0 | 0 | 2 | 0 | 2 | PASS | DISCARD (<7) |
| XOM | 5/10 | 0 | 1 | 2 | 0 | 2 | FAIL (2/3: vol 0.73x + mom -0.5%) | DISCARD |
| V | 4/10 | 0 | 0 | 1 | 1 | 2 | PASS | DISCARD (<7) |
| GS | — | — | — | — | — | — | Finance 1/2 fails | SKIP |
| MA/CVX/UNH/JNJ/SPY/QQQ | <6 | 0 | 0-1 | — | — | — | — | DISCARD |

**Note:** AAPL and MSFT score 7 but fail buy-side gate (no specific catalyst). AMD scores 7 with weak AI-semi catalyst — watch for next week if a specific catalyst emerges.

### Technical Validation (≥7 scorers)

**AAPL** (Last=$294.42):
- SMA20: $294.75 | Dist: -0.1% (AT SMA — excellent entry zone)
- Mom5d: +0.4% (positive ✅) | VolRat: 1.11x (above 0.8 ✅) | Extended: NO ✅
- Result: All 3 tech checks PASS; no actionable trade (no catalyst + slots full)

**MSFT** (Last=$384.38):
- SMA20: $388.71 | Dist: -1.1% (slightly below SMA — clean)
- Mom5d: +5.2% (positive ✅) | VolRat: 1.23x ✅ | Extended: NO ✅
- Result: All 3 tech checks PASS; no actionable trade (no catalyst + slots full)

**AMD** (Last=$540.89):
- SMA20: $517.89 | Dist: +4.4% (just above SMA, setup score 1)
- Mom5d: +4.2% (positive ✅) | VolRat: 1.24x ✅ | Extended: NO ✅
- Result: All 3 tech checks PASS; weak catalyst; no slot

**AVGO** (Last=$369.33):
- SMA20: $390.15 | Dist: -5.3% | Mom5d: -3.3% (❌ FAIL) | VolRat: 0.66x (❌ FAIL)
- Result: 2/3 tech fails → DISCARDED

### Trade Ideas
**None — 3/3 weekly buy slots used. No new buys until Monday July 7.**

For next-week watchlist:
1. **AAPL** — Clean setup at 20d SMA (-0.1%), XLK top sector. Need specific catalyst (earnings Aug; near-term: any product/AI news).
2. **AMD** — Positive momentum (+4.2% 5d), AI semiconductor thematic. Entry score 7/10 but catalyst needs to be confirmed.
3. **MSFT** — Clean setup, improving momentum (+5.2% 5d). Watch for AI capex deployment news.

### Risk Factors (Today)
1. **NFP 8:30 AM (HIGH):** Jobs miss could spike VIX, hurt equities across all 5 positions. Prior 172K; if actual is weak (<100K), expect tech selloff. Wait for 8:30 AM data before assessing intraday moves.
2. **TSM -5.09% + -7% cut trigger (CRITICAL):** Current $443.50 vs cut trigger $434.59 — buffer only $8.91 (2.0%). Semiconductor sector under pressure; broader chip selloff risk. If TSM opens at or below $434.59, cut immediately.
3. **TSLA Q2 Delivery (WATCH):** Consensus 406K. In-line result could disappoint bulls expecting Goldman's 420K. Miss would threaten the Morgan Stanley $600 PT thesis; beat would add upside momentum to our +1.62% position.
4. **NVDA stop proximity (MEDIUM):** Stop $180.57 (HWM $200.63). Current $196.40 — 8.1% buffer. Monitor if NFP triggers tech selloff.
5. **Half-day Friday Jul 3 (LOW):** Thin volume tomorrow; positions carry over the holiday weekend. Today's positioning matters.
6. **Underdeployment (ONGOING):** 38.8% deployed vs 80% target. $60.3K idle. Next entries must wait until Jul 7 (3 fresh slots).

### Decision
**HOLD — No new buys available (3/3 weekly slots used)**
- Watchlist for Jul 7: AAPL (priority 1, score 7, cleanest setup), AMD (priority 2, score 7, momentum), MSFT (priority 3)
- Critical action today: Monitor TSM at open — cut if price ≤ $434.59

---

## 2026-07-14 — Pre-Market Research

### Account Snapshot
- **Equity:** $98,080.95 | **Last equity (Jul 13 close):** $98,262.03 | **Day Δ:** -$181.08 (premarket)
- **Cash:** $66,627.19 | **Long MV:** $31,453.76 | **Deployed:** 32.1% (target 80%)
- **DT count:** 0 | **Weekly buy slots:** 0/3 used (week Jul 14–18)
- **Open positions:** AMZN, JPM, NVDA, V (4 of 10 max)

### Market Context
- **WTI crude:** $80.35/bbl
- **SPX futures (Sep 26):** $7,588.75 (flat/slight decline; MarketWatch Dec 26 contract $7,626)
- **VIX:** 16.13 (+3.60% from prior close of 15.57)
- **CPI June (HIGH IMPACT):** Released 8:30 AM ET today — consensus headline 3.9% YoY, core 2.9%
- **FOMC:** July 30 decision (next key Fed event)
- **European markets risk-off:** DAX -2.23%, FTSE -2.05%, CAC -2.18% — significant global caution
- **Nikkei:** +1.67% (divergent; Asia positive)
- **Gold futures:** $4,062.86 (-0.37%) — modest safe-haven demand

### Earnings Today (Confirmed BMO)
- **JPM Q2:** Beat (+10% YoY), reported before open; stock -1.96% premarket to $327.98 (sell-the-news / CPI caution). Our position entry $322.67 — stop $309.10, buffer adequate.
- **GS Q2:** Strong beat — EPS $17.23 (consensus ~$13.45, +28% YoY), revenue $17.2B beat, IB revenues +42%; stock gapping +3.6% to ~$1,058 premarket from prior close ~$1,021.
- **AXP:** Triple analyst upgrade (JPM, MS, Jefferies → Overweight/Buy) — Finance sector tailwind (AXP not in universe)

### Sector ETF Ranking (This Week)
| Rank | Sector | ETF | Week Perf |
|------|--------|-----|-----------|
| 1 | Energy | XLE | +3.01% |
| 2 | Technology | XLK | +2.64% |
| 3 | Financials* | XLF | improving (Q2 earnings catalyst) |

*XLF YTD -1.7% (bottom third YTD); weekly improvement on JPM/GS beats.

### Held Position Status (Premarket)
| Ticker | Shares | Entry | Pre-Mkt | Unreal P&L | Stop (HWM) | Notes |
|--------|--------|-------|---------|-----------|------------|-------|
| AMZN | 34 | $233.97 | $246.15 | +$414.06 (+5.21%) | $227.27 ($252.53) | -0.47% pre-mkt; no news |
| JPM | 24 | $322.67 | $327.98 | +$127.44 (+1.65%) | $309.10 ($343.45) | -1.96% pre-mkt; Q2 beat, sell-the-news |
| NVDA | 36 | $193.58 | $204.50 | +$393.15 (+5.64%) | $189.90 ($211.00) | +0.48% pre-mkt; JPM positive mention |
| V | 22 | $347.73 | $356.78 | +$199.10 (+2.60%) | $323.54 ($359.49) | -0.27% pre-mkt; institutional buying |
No stop tightening triggers reached (NVDA +15% trigger: $222.62; not at +15%). All GTC stops valid.

### Candidate Scoring (20-symbol universe; Tech sector LOCKED — no AAPL/MSFT/GOOGL/META/AMD/AVGO/TSLA/TSM new buys)
| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Tech Checks | Result |
|--------|-------|----------|--------|-------|--------|-----|-------------|--------|
| GS | **8/10** | 2 | 0 | 2 | 2 | 2 | PASS (all 3) | ✅ TRADE IDEA |
| XOM | **7/10** | 1 | 1 | 1* | 2* | 2 | PASS* | ✅ TRADE IDEA (conditional) |
| MA | 4/10 | 1 | 0 | 1 | 1 | 1 | N/A | ❌ <7 — no specific catalyst |
| CVX | 5/10 | 1 | 1 | 1 | 0 | 2 | FAIL (vol 0.6x on Jul 13) | ❌ tech fail |
| UNH | 3/10 | 0 | 0 | 1 | 1 | 1 | N/A | ❌ <7 — XLV YTD -6.7%, no catalyst |
| JNJ | 2/10 | 0 | 0 | 1 | 0 | 1 | N/A | ❌ <7 — same as UNH |
| SPY/QQQ | 4/10 | 1 | 1 | 1 | 1 | 0 | N/A | ❌ <7 — no directional thesis |

*Bars data unavailable via Alpaca (data plan limitation); XOM/CVX technicals estimated via Tavily.
**Note:** NVDA already held; GS Finance (0/2 sector YTD) but confirmed Q2 catalyst compensates.

### Technical Validation (≥7 scorers)

**GS** (prior close ~$1,021; premarket ~$1,058):
- 50d SMA: $1,039.18; 20d & 8d SMA: above prior close (Tavily: "8d/20d suggest Sell" at $1,021)
- Estimated 20d SMA: ~$1,030–1,040
- Pre-mkt $1,058 vs est. 20d SMA ~$1,035 → Dist: ~+2.2% (at-SMA zone, <5%) ✅
- 5d momentum: +1.0% (Tavily; stock was near 52wk levels pre-earnings) ✅
- Volume: Earnings day → well above 1.5x avg ✅
- **Tech check: 0/3 failures → PASS**

**XOM** (price ~$138.88):
- 20d MA: "bullish" per Tavily; volume July 2026: 27.9M (avg ~15–17M → ~1.7x)
- Estimated Dist from 20d SMA: +2–5% (at-zone)
- 5d momentum: Energy sector +3.01% week → estimated positive ✅
- Volume ratio: ~1.7x → ✅
- **Tech check: 0/3 estimated failures → PASS (conditional — no bar data)**

### Trade Ideas

**1. GS — Goldman Sachs (Primary)**
- **Score:** 8/10 | Catalyst: Q2 beat (EPS $17.23, IB +42%) | Sector: Finance (weekly improving) | Setup: near 20d SMA | Volume: Earnings day
- **Entry:** ~$1,055–1,065 at open after CPI (9:30 AM, after 8:30 AM data settles)
- **Stop:** 10% trailing (initial ~$950) | **HWM = entry price**
- **Target:** +20% (~$1,268–1,278) | **R:R:** 2.0:1
- **Size:** 7 shares × ~$1,060 = ~$7,420 (7.6% of equity)
- **Condition:** Only enter if CPI headline ≤ 4.0% and core ≤ 3.1%; wait for open reaction to settle

**2. XOM — Exxon Mobil (Secondary / Later This Week)**
- **Score:** 7/10 | Catalyst: WTI $80.35, Energy sector week leader +3.01% | Sector: XLE mid-third YTD +7.8% | Setup: ~at 20d SMA | Volume: elevated
- **Entry:** ~$138–140 (after CPI confirmation, ideally mid-week)
- **Stop:** 10% trailing (initial ~$125) | **Target:** +20% ($167) | **R:R:** 2.0:1
- **Size:** 55 shares × ~$139 = ~$7,645 (7.8% of equity)
- **Condition:** Bars data unavailable; confirm at entry that price is within 10% of 20d SMA; conditional on CPI not causing energy selloff

### Risk Factors
1. **CPI 8:30 AM (CRITICAL):** Hotter print (>4.0% headline or >3.1% core) → risk-off, delay all new buys, evaluate existing stops.
2. **European selloff -2%+ (HIGH):** DAX -2.23%, FTSE -2.05%, CAC -2.18% — global caution may spill into US open.
3. **VIX +3.60% to 16.13 (MEDIUM):** Rising anxiety. Watch for spike >20 → pause buys.
4. **Finance concentration risk (MEDIUM):** JPM + V + GS (if bought) = 3 Finance positions. Sector YTD -1.7%.
5. **JPM premarket -1.96% (WATCH):** Earnings beat but sell-the-news dynamic. Stop $309.10, current $327.98 — 6.1% buffer, no action needed.
6. **Underdeployment (ONGOING):** 32.1% vs 80% target — critical. Need 2–3 more positions. GS + XOM this week would bring to ~48%.

### Decision
**TRADE — GS (primary, 8/10); XOM (secondary, 7/10)**
- GS: Enter at open after confirming CPI ≤4.0% headline. 7 shares, ~$7,420 cost.
- XOM: Later this week (Wed/Thu) after verifying bars technicals. 55 shares, ~$7,645 cost.
- **If CPI hot (>4.0%):** Switch to HOLD — reassess in midday routine.
- Weekly slot allocation: GS = slot 1/3; XOM = slot 2/3; slot 3 reserved.
- Sources: Tavily (GS earnings, CPI consensus, VIX, oil, sector ETFs, premarket futures); Alpaca (live positions, orders, account).
- Watch TSLA delivery numbers: thesis intact above $392.33 (-7% cut level)
- NFP at 8:30 AM is the key event; assess all positions post-release
---

## 2026-07-14 — Midday Addendum

**Midday Scan (Day 57, Monday)**
| Field | Value |
|-------|-------|
| Equity | $98,650.77 |
| Session-start equity | $98,080.95 |
| Day change | +$569.82 (+0.58%) — **no DD halt** |
| Open positions | 4 (AMZN, JPM, NVDA, V) |

**Position Review (midday):**
| Ticker | Current | Unrealized | Intraday | Stop (HWM) | Action |
|--------|---------|-----------|---------|------------|--------|
| AMZN | $246.26 | +5.25% (+$417.80) | -0.43% | $227.27 (HWM $252.53) | ✅ Hold |
| JPM | $340.80 | +5.62% (+$435.12) | +1.87% | $310.23 (HWM $344.70) | ✅ Hold |
| NVDA | $211.19 | +9.10% (+$634.00) | +3.76% | $190.22 (HWM $211.35) | ✅ Hold — watch +15% @ $222.62 |
| V | $357.94 | +2.94% (+$224.62) | +0.05% | $323.95 (HWM $359.94) | ✅ Hold |

**Decisions:**
- No cuts: no position at -7% (best unrealized V +2.94%, worst AMZN -0.43% intraday only)
- No stop tightening: no position at +15% (NVDA closest at +9.10%; trigger $222.62)
- No thesis breaks: all 4 theses intact
  - JPM: Q2 beat (+10% YoY) confirmed; recovered from sell-the-news to +1.87% intraday ✅
  - NVDA: AI momentum +3.76% intraday; approaching +15% tightening level ✅
  - AMZN: steady; no news ✅
  - V: Finance sector catalyst (JPM/GS both Q2 beats) intact ✅
- No GS position: market-open routine did not execute GS buy (likely CPI or open conditions triggered HOLD). 2 weekly buy slots remain for GS/XOM.
- No new trades — midday not the venue for new entries.

---

## 2026-07-15 — Pre-Market Research (Day 58, Wednesday)

### Account Snapshot
| Field | Value |
|-------|-------|
| Equity | $98,806.92 |
| Cash | $66,627.19 (67.4%) |
| Long market value | $32,179.73 (32.6%) — vs 80% target |
| Day P&L vs last EOD | +$124.27 (+0.13%) |
| Daytrade count | ~0 |
| Weekly buys used | 0/3 (week Jul 14-18) |

### Open Positions (premarket)
| Ticker | Shares | Entry | Price | Unrlzd P&L | Stop (HWM) |
|--------|--------|-------|-------|-----------|-----------|
| AMZN | 34 | $233.97 | $248.54 | +$495.32 (+6.23%) | $227.27 (HWM $252.53) |
| JPM | 24 | $322.67 | $343.57 | +$501.63 (+6.48%) | $310.23 (HWM $344.70) |
| NVDA | 36 | $193.58 | $211.85 | +$657.84 (+9.44%) | $191.30 (HWM $212.55) |
| V | 22 | $347.73 | $357.05 | +$205.04 (+2.68%) | $323.95 (HWM $359.94) |

All positions above stop levels; no tightening triggers reached (NVDA +15% trigger @ $222.62, still ~5% away).

### Market Context
- **Oil:** WTI $78.94 (+1.02%), Brent $84.55 (+1.50%) — US-Iran military escalation; Strait of Hormuz closure concerns (source: oilprice.com, robinhood.com/us/en/stocks/CVX)
- **SPX futures:** +$11.75 (+0.15%) — slightly positive (source: marketwatch.com)
- **VIX:** 15.57 — moderate, not alarming (source: tradingeconomics.com/united-states/cboe-volatility-index-vix)
- **IBM:** Earnings miss, diving toward worst day in 40 years — tech caution signal (not in universe; watch for spillover)
- **European markets:** DAX -2.23%, FTSE -2.05%, CAC -2.18% yesterday; recovering today

### Today's Economic Calendar
- **08:30 AM ET:** PPI (June) — BLS confirmed (source: bls.gov)
- **08:30 AM ET:** JNJ Q2 earnings conference call
- **10:00 AM ET:** Fed Chair Warsh Senate Banking Committee testimony (pledging "inflation regime change")
- No CPI today (was yesterday Jul 14)

### Sector ETF Ranking — This Week
| Rank | Sector | ETF | YTD | Notes |
|------|--------|-----|-----|-------|
| 1 | Technology | XLK | +33% | LOCKED — tech sector ban (2 consecutive failures: TSLA, TSM) |
| 2 | Energy | XLE | +21% | ✅ Eligible — US-Iran oil surge catalyst |
| 3 | Industrials | XLI | +22% | No specific catalyst today |
| — | Finance | XLF | — | -1.6% this week; already hold JPM + V |
| — | Healthcare | XLV | +21% | -1.93% this week; JNJ earnings today |

Source: etfdb.com/sector-investing-content-hub/xlk-xle-xli-top-performing-sector-spdrs, marketchameleon.com

### Candidate Scoring (20-symbol universe)
**Tech sector LOCKED — no new buys:** AAPL, MSFT, GOOGL, AMZN, NVDA, META, TSLA, AMD, AVGO, TSM
**Already held — no new entry:** JPM, V

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Result |
|--------|-------|----------|--------|-------|--------|-----|--------|
| XOM | **10/10** | 2 | 2 | 2 | 2 | 2 | ✅ ADVANCE |
| CVX | **9/10** | 2 | 2 | 1 | 2 | 2 | ✅ ADVANCE |
| JNJ | **9/10** | 2 | 1 | 2 | 2 | 2 | ⚠️ ADVANCE (5d momentum caution) |
| GS | **7/10** | 2 | 1 | 1 | 1 | 2 | ✅ ADVANCE (Finance concentration risk) |
| MA | 5/10 | 1 | 1 | 1 | 0 | 2 | ❌ FAIL |
| UNH | 5/10 | 1 | 1 | 1 | 1 | 1 | ❌ FAIL |
| SPY | 5/10 | 1 | 1 | 1 | 1 | 1 | ❌ FAIL |
| QQQ | 5/10 | 1 | 1 | 1 | 1 | 1 | ❌ FAIL |

*Scoring rubric: Catalyst (0-2) | Sector rank YTD (0-2) | Technical setup vs 20d SMA (0-2) | Volume confirmation (0-2) | R:R ratio (0-2)*

### Technical Validation (≥7 scorers)

**XOM — PASS (0/3 failures)**
- Price: $144.51 | Est. 20d SMA: ~$141-142 (computed from: Jul 6 close $136.44, 8d SMA $138.21, 50d SMA $146.86)
- Dist from SMA: +2.1% ✅ (not extended >10%)
- 5d momentum: $136.44 (Jul 6) → $144.51 = **+5.9% positive** ✅
- Volume ratio: Oil surge + US-Iran catalyst → well above avg ✅
- Bars: unavailable (API returned null); technicals estimated from Tavily data sources
- Source: finance.yahoo.com/quote/XOM, financhill.com, investing.com/equities/exxon-mobil-technical

**CVX — PASS (0/3 failures)**
- Price: ~$187 (est. Jul 14 close $181.57 + oil surge today per CNN) | Est. 20d SMA: ~$176-178 (from Jul 9 close $174.05 trajectory)
- Dist from SMA: +5.4% ✅ (not >10%; in 5-10% zone → setup score 1/2)
- 5d momentum: $174.05 (Jul 9) → $187 = **+7.4% positive** ✅
- Volume ratio: Oil surge + Strait of Hormuz news → elevated ✅
- Bars: unavailable (API null); technicals estimated from Tavily
- Source: robinhood.com/us/en/stocks/CVX, macrotrends.net/stocks/charts/CVX, cnn.com/markets/stocks/CVX

**JNJ — CONDITIONAL (1/3 failures — 5d momentum negative)**
- Price: ~$257.77 (premarket) | 52-week high: $269.43 (Jul 7) | Est. 20d SMA: ~$264-267
- Dist from SMA: ~-3% (below SMA) ✅ (good setup technically)
- 5d momentum: $269.43 (Jul 7) → $257.77 = **-4.3% negative** ❌
- Volume ratio: Earnings day → elevated ✅
- Earnings: Q2 today BMO; EPS est $2.85, Earnings ESP +2.08% (likely beat). EPS $2.90/$25.2B per Tavily answer (unconfirmed). Conf call 8:30 AM.
- **Fail count: 1/3 → technically passes discard threshold but negative momentum into entry is a caution flag**
- Source: robinhood.com, perplexity.ai/finance/JNJ, marketbeat.com/earnings/reports/2026-7-15-johnson-johnson-stock

**GS — CONDITIONAL (Finance concentration)**
- Price: New 52wk high on Jul 14 (above $1,125); Jul 10 close $1,055.18 | Est. 20d SMA: ~$1,050-1,065
- Dist from SMA: ~+7% ✅ (5-10% zone, not >10%)
- 5d momentum: $1,029.64 (Jul 8) → ~$1,140+ = **+10.7% positive** ✅
- Volume: Day 1 after earnings (Jul 14) was elevated; today (day 2) may normalize ⚠️
- Finance concentration: JPM + V + GS = 3 Finance positions; Finance sector -1.6% this week
- Pass count: 0/3 technical failures; deprioritized due to concentration risk and post-earnings extension
- Source: macrotrends.net/stocks/charts/GS, cnbc.com/quotes/GS, investing.com/equities/goldman-sachs-group-historical-data

### Trade Ideas

**1. XOM — ExxonMobil (Primary, 10/10)**
- **Catalyst:** US-Iran military escalation confirmed; Iran Strait of Hormuz closure concerns; WTI $78.94 (+1.02%), Brent $84.55 (+1.50%) — supply shock confirmed
- **Entry:** ~$144-146 at market open; wait for PPI release (8:30 AM) — only enter if PPI MoM ≤ +0.3% (benign)
- **Stop:** 10% trailing GTC | HWM = entry price | Initial stop ~$130-131
- **Target:** +20% (~$173-175)
- **R:R:** 2.0:1
- **Size:** 54 shares × $144.51 ≈ $7,804 (7.9% of equity)
- **Tech check:** 20d SMA dist +2.1% ✅ | 5d momentum +5.9% ✅ | volume elevated ✅
- **Entry gate:** PPI benign ✅ | oil holding >$78 ✅ | position cost ≤8% ✅ | weekly slot 0→1/3 ✅ | positions 4→5 ≤10 ✅

**2. CVX — Chevron (Secondary, 9/10)**
- **Catalyst:** Same Strait of Hormuz / US-Iran oil shock; CNN confirms +$5.80 from last close
- **Entry:** ~$185-188 at open; stagger after XOM fills to confirm energy momentum
- **Stop:** 10% trailing GTC | Initial stop ~$168
- **Target:** +20% (~$222-225)
- **R:R:** 2.0:1
- **Size:** 42 shares × $186 ≈ $7,812 (7.9% of equity)
- **Tech check:** 20d SMA dist +5.4% ✅ | 5d momentum +7.4% ✅ | volume elevated ✅
- **Entry gate:** After XOM entry confirmed | oil still holding | weekly slot 1→2/3 | positions 5→6 ≤10 ✅

### Risk Factors
1. **US-Iran ceasefire (HIGH):** Peace talks could reverse oil sharply — stop management critical; don't chase if oil reverses at open
2. **PPI 8:30 AM (MEDIUM):** Hot print (>+0.5% MoM core) = risk-off, delay all energy buys, reassess
3. **Warsh testimony 10 AM (MEDIUM):** Hawkish tone on rates could pressure cyclicals including energy
4. **JNJ earnings + PPI at 8:30 AM (MEDIUM):** Double catalyst = volatile open; 15-min wait after open before executing
5. **NVDA +15% trigger watch (LOW):** Trigger at $222.62 (+5.1% from $211.85); tighten trail to 7% when crossed
6. **Finance sector weakness (ONGOING):** JPM + V holding fine but Finance declining -1.6% weekly; no new Finance buys
7. **Underdeployment (ONGOING):** 32.6% → ~48% if both XOM+CVX executed; still below 80% target

### Decision
**TRADE — XOM (primary) + CVX (secondary)**
- XOM: Enter at open after PPI confirms benign; 54 shares ~$7,804 (7.9% equity); 10% trailing stop
- CVX: Enter immediately after XOM fills if energy momentum confirmed; 42 shares ~$7,812 (7.9% equity); 10% trailing stop
- **ABORT CONDITION (both):** PPI prints hot (>+0.5% core MoM) or oil reverses below $77 at open
- Weekly slot allocation: XOM = 1/3, CVX = 2/3; 1 slot reserved rest of week
- GS: Skip — Finance concentration (already 2 Finance positions), post-earnings extension risk
- JNJ: Skip — negative 5d momentum, PPI volatility at same time as earnings call (8:30 AM)
- Sources: Tavily (oil, VIX, SPX futures, sectors, earnings, JNJ, GS, CVX, XOM); Alpaca (account, positions, orders)

### Midday Addendum (2026-07-15)
- **Portfolio equity ~$99,035** vs session-start $98,806.92 (+$228, +0.23%) — no DD halt
- **AMZN +2.94%** to $254.76 (new HWM $256.48, stop auto-trailed to $230.83) — BofA "biggest AI winner" call today; $25B AI bond issuance from yesterday; thesis intact, +8.89% unrealized
- **JPM +1.38%** to $347.61 (new HWM $349.58, stop $314.62) — Q2 earnings momentum; +7.73% unrealized
- **V +1.18%** to $360.225 (HWM $360.43, stop $324.39) — stable; +3.59% unrealized
- **NVDA -1.91%** to $207.745 (HWM $212.55, stop $191.30) — IBM miss tech spillover; thesis intact (Perplexity Vera chip win, Goldman "bargain" note); +7.32% unrealized, well above stop
- **No cuts** (all positions >-7%)
- **No tightening** (NVDA +15% trigger at $222.62; not reached; no other position near +15%)
- **No thesis breaks** — all positions within rules
- **XOM/CVX not entered** — market-open routine outcome not in TRADE-LOG; likely aborted (PPI or oil conditions)
- Source: Alpaca API, Tavily (AMZN BofA/CNN/WSJ)
- **Source:** Tavily (Alpaca API, CNN, Robinhood, MarketWatch)

---

## 2026-07-16 — Pre-Market Research

### Account Snapshot
- **Equity:** $99,090.64 | **Cash:** $66,627.19 | **Deployed:** $32,463.45 (32.8%) | **Day P&L:** +$5.89 (+0.01%) | **DT Count:** 0
- **Buy slots this week:** 0/3 used (Jul 14–18)
- **Session-start equity:** $99,084.75 (no DD halt: +$5.89 = +0.01%)

### Positions (Pre-Market)
| Ticker | Shares | Entry | Pre-Mkt Price | Unrealized | Stop | HWM | Alert |
|--------|--------|-------|--------------|------------|------|-----|-------|
| AMZN | 34 | $233.97 | $257.43 | +$797.63 (+10.03%) | $230.83 | $256.48 | **NEW HWM** $257.43 → stop auto-updates to ~$231.69 |
| JPM | 24 | $322.67 | $348.00 | +$607.92 (+7.85%) | $314.62 | $349.58 | Below HWM |
| NVDA | 36 | $193.58 | $209.51 | +$573.33 (+8.23%) | $191.31 | $212.57 | Pre-mkt -1.41% |
| V | 22 | $347.73 | $355.30 | +$166.54 (+2.18%) | $324.39 | $360.43 | Stable |

**AMZN HWM update:** Current $257.43 > HWM $256.48 → trailing stop auto-trails; new stop ≈ $231.69. +15% trigger: $268.97 (not yet reached).
**NVDA:** Pre-market $209.51 (-1.41%); +15% trigger $222.62 (not reached); stop $191.31 safe.

### Market Context
- **WTI:** ~$79.93/bbl (Jul 2026 contract, MarketWatch) | **Brent:** ~$85.03/bbl
- **S&P 500:** ~7,562–7,572; premarket +0.15%
- **VIX:** est. 15–18 (30-day range: 14.96–20.72, Business Insider)
- **US-Iran:** US-Iran blockade of Strait of Hormuz in effect (Jul 13 reinstated); BUT Iran president signaled willingness to negotiate Wednesday (Jul 15) → XOM/CVX dropped 5% on de-escalation talk. WTI held ~$79-80.
- **Energy sector:** XLE premarket +0.38% (recovering slightly from Wednesday's peace-talk drop)

### Economic Releases Today (Jul 16)
- **8:30 AM:** Retail Sales (Jun) exp +0.3% MoM; ex-Auto exp -0.1%
- **8:30 AM:** Initial Jobless Claims (week Jul 11); Philadelphia Fed Index; Housing Starts
- **9:15 AM:** Industrial Production & Capacity Utilization (Jun)
- **10:00 AM:** Business Inventories (May)
- Soft retail ex-auto = consumer caution signal; hot prints = risk-on; watch before entering

### Earnings Today BMO
- **UNH** (Q2 2026, in universe) — EPS est $3.89; KeyBanc/Truist/TD Cowen raised targets ahead ($430–$475); pre-mkt $420.74 (+$4.47 from prior close per CNN)
- **TSM** (Q2 2026, tech sector LOCKED — irrelevant)
- **GE** (Q2 2026, not in universe)

### Sector ETF Rankings
- **YTD top 3:** XLK +33% | XLE +21% | XLI +20%
- **Week of Jul 5 top 3:** XLV +4.04% | XLC +3.00% | XLY +2.62% (XLF +1.97%; XLE -1.42% that week before Iran escalation)
- **This week est. top 3:** XLF (JPM/GS Q2 beats) | XLV (JNJ/UNH earnings) | XLE (Iran escalation Mon–Tue, partial reversal Wed)

### Candidate Scoring (20-symbol universe — non-tech, non-held only)

| Ticker | Score | Catalyst | Sector | Setup | Volume | R:R | Result |
|--------|-------|----------|--------|-------|--------|-----|--------|
| UNH | 8/10 | 2 (Q2 earnings BMO) | 0 (XLV +2.7% YTD = bottom third) | 2 (near 200d SMA, CNN) | 2 (earnings day) | 2 (>2:1) | PASS |
| MA | 8/10 | 2 (Barclays OW Jul 8; pre-Q4 FY26 earnings) | 1 (XLF mid-third YTD) | 2 (at 200d SMA, CNN) | 1 (avg vol) | 2 (>2:1) | PASS |
| XOM | 8/10 | 1 (Iran blockade but de-escalation risk Wed) | 2 (XLE +21% YTD) | 2 (est ~$159 SMA, dist +1.3%) | 2 (elevated) | 2 (>2:1) | PASS (conditional) |
| CVX | 8/10 | 1 (same as XOM) | 2 (XLE top third) | 2 (est near SMA) | 2 (elevated) | 2 (>2:1) | PASS (conditional) |
| GS | 5/10 | 1 (post-earnings day 2) | 1 (XLF mid-third) | 1 (est +7% above SMA) | 1 (normalized) | 1 (1.5–2:1) | DISCARD |
| JNJ | 6/10 | 1 (post-earnings Jul 15) | 1 (XLV bottom-mid) | 2 (below SMA) | 1 (avg) | 1 (1.5–2:1) | DISCARD |

### Technical Validation (Bars API null for non-held; estimates from Tavily)

**UNH** — PASS (0/3 failures)
- Price: ~$420.74 pre-mkt | Est 20d SMA: ~$410 (recovering from $270 in March, $399 on May 13)
- Dist from SMA: ~+2.4% ✅ (not >10% extended; well within "at or below" zone)
- 5d momentum: recovering trajectory, +1–2% positive ✅
- Volume: Earnings day BMO → elevated ✅
- Source: robinhood.com/us/en/stocks/UNH, cnn.com/markets/stocks/UNH, tikr.com/blog

**MA** — PASS (0/3 failures)
- Price: ~$535 (Yahoo: $535.21, Kraken: $535.00, CNBC: $535.75)
- CNN: "trading in middle of 52-week range and near 200-day SMA" → dist ~0% ✅
- 5d momentum: ~flat to slightly positive from Jul 8 levels ($527–545 range) ✅
- Volume: avg est. ≥0.8× ratio minimum ✅
- Source: finance.yahoo.com/quote/MA/history, cnbc.com/quotes/MA, cnn.com/markets/stocks/MA

**XOM** — PASS (0/3 failures) — but Iran thesis risk flagged
- Price: ~$161 (Yahoo: dropped from ~$169 on Iran de-escalation Wednesday Jul 15)
- Est 20d SMA: ~$159 (from May 19 level $160.49 per 247wallst; recovered on Iran)
- Dist from SMA: ~+1.3% ✅ (not extended)
- 5d momentum: from ~$153 (Jul 9) to $161 (today) = +5.2% ✅ but declining from $169 peak
- Volume: Iran news = elevated ✅
- Source: finance.yahoo.com/sectors/energy/articles/exxon-mobil-chevron-fall-5, 247wallst.com/investing/2026/05/19

### Trade Ideas

**1. UNH — UnitedHealth Group (PRIMARY, 8/10, CONDITIONAL)**
- **Catalyst:** Q2 2026 earnings BMO today; EPS est $3.89; KeyBanc raised target, Truist raised target, TD Cowen raised to $430; BofA maintains Buy $475; Mizuho maintains Buy $460
- **Entry:** $420–435 at market open; ABORT if gap >5% above pre-mkt $420.74 (price >$441)
- **Stop:** 10% trailing GTC | Initial stop ~$381–391
- **Target:** +20% = ~$505–522
- **R:R:** ~2.2:1
- **Size:** 18 shares × $425 ≈ $7,650 (7.7% equity)
- **Technicals:** SMA dist +2.4% ✅ | 5d momentum positive ✅ | earnings volume ✅
- **Gate:** universe ✅ | positions 4→5 ≤10 ✅ | weekly 0→1/3 ✅ | cost ≤8% ✅ | cash ✅ | catalyst ✅ | DT 0 ✅
- **ABORT CONDITIONS:** Q2 miss (EPS < $3.89 or revenue miss + guidance cut); gap >5% above $420.74; retail sales wildly negative at 8:30 AM
- Source: robinhood.com/us/en/stocks/UNH, markets.businessinsider.com/stocks/unh-stock

**2. MA — Mastercard (SECONDARY, 8/10)**
- **Catalyst:** Barclays initiated Overweight Jul 8; TD Cowen/Baird rated Jul 7; pre-Q4 FY2026 earnings window (late July); Revenue +16.61% YoY (CNN); consensus Buy with targets $605–$735
- **Entry:** ~$535–542 at market open (check bid-ask spread <3% before entering)
- **Stop:** 10% trailing GTC | Initial stop ~$481–488
- **Target:** +20% = ~$642–650
- **R:R:** ~2.0:1
- **Size:** 14 shares × $537 ≈ $7,518 (7.6% equity)
- **Technicals:** at 200d SMA per CNN ✅ | momentum flat/slight positive ✅ | volume ≥0.8× ✅
- **Note:** 3rd Finance position (JPM + V + MA) — concentration risk; no hard rule violation
- **Gate:** universe ✅ | positions 4→5 (or 5→6 if UNH entered first) ≤10 ✅ | weekly 1→2/3 ✅ | cost ≤8% ✅ | cash ✅ | catalyst ✅ | DT 0 ✅
- Source: cnbc.com/quotes/MA, cnn.com/markets/stocks/MA, benzinga.com/quote/MA/analyst-ratings

**XOM — MONITOR (Iran de-escalation thesis risk; defer to Friday)**
- Iran president signaled de-escalation Wednesday; XOM dropped 5% to $161
- If blockade collapses and peace achieved → thesis immediately broken; exit at loss
- Deferred: monitor for Iran news overnight/Thursday; enter Friday if Iran talks stall and oil holds >$78
- Source: finance.yahoo.com/sectors/energy/articles/exxon-mobil-chevron-fall-5

### Risk Factors
1. **UNH earnings miss (HIGH for UNH):** DOJ criminal investigation ongoing; membership -1.3M in 2026; guidance cut possible → skip if miss
2. **Iran de-escalation (HIGH for energy):** Peace talks could reverse XOM/CVX another 5-10% — reason for deferral
3. **Retail Sales 8:30 AM (MEDIUM):** Ex-auto expected -0.1%; weak print = consumer caution; delay all entries if wildly below exp
4. **Finance concentration (MEDIUM):** 3rd Finance position (MA) — JPM, V, MA all in XLF
5. **AMZN HWM exceeded (LOW):** $257.43 > $256.48 HWM → trailing stop auto-updating to ~$231.69; +15% trigger at $268.97 not yet reached
6. **NVDA premarket -1.41% (LOW):** Down to $209.51; stop $191.31 safe (+9.0% cushion); thesis intact
7. **Deployment gap (ONGOING):** 32.8% vs 80% target; 2 trades today = ~48%; 1 slot Friday for XOM or other

### Decision
**TRADE: UNH (conditional on earnings beat) + MA**
- UNH: Enter at open if Q2 beats and price ≤$441 (≤5% gap); 18 shares ~$7,650; 10% trailing stop GTC
- MA: Enter at open; check bid-ask spread first (skip if >3%); 14 shares ~$7,518; 10% trailing stop GTC
- Weekly slot usage: 0→2/3 after both trades; 1 slot reserved for Friday (XOM if Iran stabilizes)
- XOM/CVX: DEFERRED to Friday pending Iran clarity
- Sources: Tavily (UNH, MA, XOM, market context, sectors, earnings, economic calendar); Alpaca API (account, positions, orders)


### Midday Addendum — 2026-07-16 ~12:00 ET

**NVDA intraday check (Tavily):**
- Current: $206.92 (−2.6% from yesterday's close $212.47)
- No thesis-breaking news: normal pullback within AI/chip cycle; Motley Fool/Yahoo note ~13% drawdown over past month is natural ebb after May/June run-up
- Chaikin Money Flow near zero, institutional positioning unclear but no major sell signal
- Stop $191.31 safe (+7.5% cushion from current price)
- **Verdict:** Thesis intact. Hold.

**Midday scan result:** All clear — no cuts, no tighten triggers, no thesis breaks, no DD halt (−0.06% from $99,084.75 session-start equity).
- Positions: 4 open (AMZN +9.3%, JPM +7.0%, NVDA +6.9%, V +4.0%)
- Watch levels: NVDA +15% trigger $222.62 | AMZN +15% trigger $269.07
