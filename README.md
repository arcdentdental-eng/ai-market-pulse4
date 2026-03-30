# 📈 AI Market Pulse — Live NSE Stock Analysis

A free, real-time Indian stock market dashboard powered by **TradingView** (live data) and **Claude AI** (smart analysis).

## Features

- **Live Ticker** — NIFTY 50, SENSEX, Bank NIFTY + top stocks scrolling in real-time
- **Market Overview** — Indices and top stocks with live mini charts
- **Top Movers** — Today's biggest gainers and losers on NSE
- **NIFTY 50 Heatmap** — Visual sector-wise performance map
- **Market News** — Live financial news feed
- **Stock Detail** — Tap any stock to see:
  - Live interactive chart with RSI, MACD, Bollinger Bands, Supertrend
  - TradingView's Technical Analysis gauge (Buy/Sell/Hold with oscillators & moving averages)
  - Company financials and profile
- **AI Analysis** — Claude-powered buy/sell recommendations with entry/stoploss/targets (requires Claude API access)
- **Advanced Chart** — Full charting tool, search ANY stock
- **Stock Screener** — Filter Indian stocks by fundamentals & technicals
- **Economic Calendar** — Upcoming market events

## Deploy to GitHub Pages (5 minutes)

### Step 1: Create GitHub Account
Go to [github.com](https://github.com) and sign up (free)

### Step 2: Create Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `ai-market-pulse`
3. Check ✅ **Public**
4. Click **Create repository**

### Step 3: Upload the File
1. Click **"uploading an existing file"** link
2. Drag and drop the `index.html` file
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** tab (top of your repo)
2. Click **Pages** (left sidebar)
3. Under "Source" select **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 5: Access Your App
Wait 1-2 minutes, then visit:
```
https://YOUR-USERNAME.github.io/ai-market-pulse/
```
🎉 **Done! Your live market app is running!**

## About the AI Button

The "Get AI Buy/Sell Recommendation" button calls Claude's API with web search to fetch the latest news and provide trading analysis. This feature requires the Claude API to be accessible from the browser (it works as a free demo from Anthropic's API).

If the AI button doesn't work, you can always ask Claude directly in [claude.ai](https://claude.ai) about any stock — just say "Analyze RELIANCE for me" and Claude will search live and give you a full recommendation.

## Tech Stack

- **TradingView Widgets** — Free, real-time market data
- **Claude API** — AI-powered stock analysis with web search
- **Vanilla HTML/CSS/JS** — No build step, no dependencies
- **GitHub Pages** — Free hosting

## Disclaimer

⚠️ This app is for **educational purposes only**. Not financial advice. Always do your own research and consult a SEBI-registered advisor before making trading decisions.
