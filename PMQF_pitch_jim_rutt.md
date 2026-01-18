# PMQF — Prediction Market Quant Fund

## The Opportunity in One Sentence

We've built production-grade data infrastructure to identify consistently profitable traders in prediction markets—now we're deploying capital to capture systematic edge in a $1B+ market that's still immature enough to exploit.

---

## The Problem: Sensemaking Has Failed

The epistemic commons has collapsed. The networks we built to upgrade humanity's collective intelligence have instead become engines of manipulation, polarization, and coordinated lying.

Every day, billions flow through financial markets. But when someone lies about a company's prospects or a political outcome, the cost is diffuse and the accountability is zero. Bullshitters are winning.

Prediction markets change the equation. They create skin in the game for beliefs. When you make a claim, you have to back it with capital. When you're wrong, you pay. This is the infrastructure for epistemic accountability that our civilization desperately needs—but it's still nascent, still inefficient, and still waiting for serious operators to build on it.

---

## What PMQF Is

PMQF is a quantitative trading fund focused on prediction markets—specifically Polymarket (crypto-based, $1B+ volume) and Kalshi (CFTC-regulated).

We're not forecasters making directional bets. We're market-makers and systematic traders adapting established quantitative finance methods to a market with the microstructure of early crypto exchanges—thin liquidity, behavioral biases, and structural inefficiencies that sophisticated operators can exploit.

**Our edge is infrastructure.** Over five years, we've built:

- A cloud-based data warehouse ingesting real-time prediction market data (17M+ events)
- Complete historical backfill of Polymarket trading activity
- DBT transformation layer with 290+ passing tests
- Trader profiling system identifying 3,685+ unique wallets
- Research framework that has produced 15+ completed backtests
- Working API clients and order book tracking for live execution

This infrastructure lets us do what others can't: systematically identify market inefficiencies, profile trader behavior, and deploy capital with quantitative discipline.

---

## The Thesis: Follow the Tacit Knowledge

Our research has uncovered a striking finding: prediction markets are well-calibrated in aggregate, but individual traders exhibit persistent skill.

When markets price an event at 85%, it resolves YES roughly 82.3% of the time—close to efficient. But dig into trader-level data and the picture changes. A subset of traders achieves 89%+ win rates over hundreds of trades. Their edge isn't luck—it's tacit knowledge about sports outcomes, political dynamics, or domain-specific signals that aggregate into price discovery.

Our core strategy: identify these consistently profitable traders through on-chain analysis, copy their positioning, and capture their alpha without requiring our own forecasting edge. Backtests show 73% ROI in sports markets.

We're also developing market-making strategies (Avellaneda-Stoikov framework adapted for binary outcomes), cross-platform arbitrage (Polymarket vs. Kalshi), and momentum detection systems.

---

## What We've Proven

### Data Infrastructure (Operational)
| Metric | Status |
|--------|--------|
| Events ingested | 17M+ |
| DBT model tests passing | 290+ |
| Unique traders profiled | 3,685+ |
| Data sources integrated | 6 (Gamma, CLOB WebSocket, Data API, Kalshi REST, blockchain) |
| Cloud services deployed | 5 (Cloud Run on GCP) |

### Research Completed
| Study | Finding |
|-------|---------|
| Market calibration | 85% prices → 82.3% resolution (4.35¢ error) |
| Longshot bias | Extreme prices overconfident (β=0.83) |
| Trader skill persistence | High-volume winners achieve 89% win rates |
| Copy-trading backtest | 73% ROI in sports markets |
| Moneyball V4 market-making | +0.05% returns in 22-hour paper test |

### Execution Capability (Built but not production)
- Rust-based real-time order book tracking
- Python API clients for both platforms  
- Paper trading bots operational
- Order placement demos working

---

## The Team

**Charlie Awbery — Strategy, Capital, Operations (Proposed: 60%)**  
Coach, systems thinker, organizational designer. Background in economics and anthropology. Manages narrative, investor relations, and overall coordination. Married to David Chapman (Meaningness, metarationality).

**Taha — Engineering & Infrastructure (Proposed: 30%)**  
Backend systems, trading infrastructure, algorithm implementation. Responsible for translating quantitative ideas into robust, scalable systems.

**Christian — Quantitative Research (Proposed: 10%)**  
Mathematical and financial expertise. Modeling, algorithm design, theoretical correctness. Hedge-fund-level quant methods.

---

## Why This Matters Beyond Returns

Prediction markets are the purest existing mechanism for collective intelligence. Every price is a probability estimate backed by capital. Every trade is a statement of belief with skin in the game.

If we can demonstrate that prediction markets work—that they can be traded professionally, that they produce accurate forecasts, that they reward truth-telling—we help build the infrastructure for a society that can coordinate around reality instead of narrative.

The opposite of what SBF did at FTX. Building slowly, with integrity. Honorable ways to profit that also make the world better.

This is Game B economics: using market mechanisms to fund truth-seeking infrastructure.

---

## The Ask

**$500K seed round** from aligned investors.

Use of funds:
- Live trading capital (~$200K)
- 12 months operational runway
- Infrastructure scaling
- Legal/compliance setup

We're not looking for maximum capital. We're looking for investors who understand what we're building and why it matters—people who see prediction markets not just as a trading opportunity but as infrastructure for epistemic accountability.

---

## Current Status

| Phase | Status |
|-------|--------|
| Data infrastructure | ✅ Operational |
| Research & backtesting | ✅ 15+ studies complete |
| Execution capability | ✅ Built, not deployed |
| Live trading | ⏳ Ready to deploy with capital |
| Legal structure | ⏳ Under evaluation |

**Next milestone:** First live trading deployment with systematic capital allocation.

---

## Contact

Charlie Awbery  
[email]  
[phone]

Introduction via Andrew Blevins / The Jim Rutt Show

---

*This document reflects actual work completed as of January 2026. We operate a "no bullshit zone"—everything stated here is grounded in what exists, not what we hope to build.*
