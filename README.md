# 📈 SIGNUM — Algorithmic Trading Terminal

> Live stock market data, 8 trading strategies, 7 time intervals, real candlestick charts.  
> **No API key required.** Powered by Yahoo Finance.

⚠️ Educational use only. Not financial advice.

---

## ✨ Features

- **Live Data** — Yahoo Finance via browser fetch, no key, no limits
- **Any Ticker** — Stocks, ETFs, crypto (BTC-USD), indices (^SPX), forex
- **8 Strategies** — SMA Crossover, EMA Ribbon, RSI Reversion, MACD Momentum, Bollinger Bands, Stochastic RSI, VWAP Mean Reversion, OBV Divergence
- **7 Intervals** — 1D, 5D, 1M, 3M, 6M, 1Y, 5Y
- **Candlestick Charts** — OHLC with volume, buy/sell signal arrows, hover tooltip
- **Indicator Charts** — Strategy-specific: RSI oscillator, MACD histogram, Bollinger Bands, OBV
- **Equity Curve + Drawdown** — Full backtest visualization
- **Trade Log** — Every round-trip with dates, prices, P&L
- **Compare Mode** — All 8 strategies side-by-side on the same data
- **PWA** — Installable, works offline after first load

---

## 🚀 Deploy to GitHub Pages

1. Create a **public** GitHub repo
2. Upload: `index.html`, `manifest.json`, `sw.js`, `README.md`
3. Go to **Settings → Pages → Source → Deploy from a branch → main / (root) → Save**
4. Visit `https://YOUR-USERNAME.github.io/REPO-NAME`

Done. No API key, no config, no build step.

---

## 📊 Strategies

| Strategy | Signal | Best For |
|---|---|---|
| SMA Crossover | 20/50 SMA golden cross | Trending markets |
| EMA Ribbon | 8/21 EMA cross | Faster trend detection |
| RSI Reversion | RSI < 30 / > 70 | Oversold/overbought reversals |
| MACD Momentum | Histogram crossover | Momentum confirmation |
| Bollinger Bands | Band touch | Mean reversion |
| Stochastic RSI | StochRSI < 20 / > 80 | Short-term timing |
| VWAP Mean Rev. | ±2% from VWAP | Intraday-style swings |
| OBV Divergence | OBV vs EMA(10) | Volume-driven momentum |

---

## ⚠️ Disclaimer

Educational and research purposes only. Not financial advice. Backtests are hypothetical — no slippage, commissions, or taxes are modeled. Past performance does not predict future results.

MIT License
