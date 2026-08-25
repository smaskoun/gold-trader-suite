# 🥇 Gold Trader Suite

A free, private, browser-based position size calculator and performance
tracker built specifically for XAUUSD traders.

**Live demo:** `https://YOURUSERNAME.github.io/gold-trader-suite/`

## Features
- ✅ XAUUSD lot calculator ($100/pip math built-in)
- ✅ Daily loss-limit circuit breaker (auto "STOP TRADING" alert)
- ✅ R-multiple tracking per trade + expectancy stats
- ✅ Equity curve chart
- ✅ Session heatmap — find your most profitable trading hours
- ✅ CSV export backup
- ✅ 100% client-side — data never leaves your device (localStorage)

## Deployment (GitHub Pages)
1. Fork or clone this repo
2. Settings → Pages → Source: `main` branch → Save
3. Done. Live at `https://yourusername.github.io/gold-trader-suite/` in ~1 min.

No build step. No server. No dependencies except Chart.js via CDN.

## Usage
1. Set account balance & risk % in calculator
2. Log every trade with entry/SL prices and hour
3. Watch the circuit breaker — red banner = done for the day
4. Review heatmap weekly; trade only your green hours
5. Export CSV monthly as backup

## Metrics Explained
| Metric | Target |
|---|---|
| Expectancy | > +0.2R |
| Win rate | Strategy-dependent |
| Profit factor ratio | > 1.5 |

## Disclaimer
Trading gold carries substantial risk. This tool is for analysis and
discipline only — not financial advice.
