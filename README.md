# investimix
App that empowers users to compare real-time prices and historical trends across Cryptocurrencies, REITs, and Gold—helping investors make smarter choices in a volatile market.
Compare investment performance across Cryptocurrencies, REITs, and Gold using real-time data, intelligent regression analysis, and smart recommendations.

Live Mockup: https://snazzy-heliotrope-23920a.netlify.app/

** Features**
📈 Live Price Charts — Real-time price data for:

5 Cryptocurrencies (Bitcoin, Ethereum, Ripple, Solana, Dogecoin)

2 REITs (Realty Income Corp, Simon Property Group)

Gold (XAU/USD)

🔍 **Interactive Charts**

Timeframe selection: 1W, 1M, 3M, 6M, 1Y

Dual charts: Actual USD and Normalized (indexed to 100)

Linear regression overlays

🤖 **ML-Based Recommendations**

Calculates best investment option using slope, volatility, and ROI

Regression analysis & correlation engine for any 2 assets

💡 Fallback Resilience

Built-in retry mechanisms, fallback mock data, and per-asset error displays

🧠 **Smart UI/UX**

Mobile-responsive

Minimalist, modern dashboard interface with dark mode

**Tech Stack**

Layer -->	Tech

Frontend	--> React, TailwindCSS, ShadCN

Charts	--> Recharts / Chart.js

Data Fetch	-->  Axios + custom retry logic

APIs	-->  CoinGecko, Yahoo Finance, GoldAPI

ML Logic	-->  JS-based regression + correlation

Hosting	-->  Netlify


# Setup & Installation

**Clone the repo**
git clone https://github.com/yourusername/investment-comparison-app.git

cd investment-comparison-app

**Install dependencies**
npm install

**Start local dev server**
npm run dev



Note: Make sure to configure any required API tokens (e.g. GOLDAPI_TOKEN) in your environment variables if working locally.


Project Structure

src/

├── components/         # UI Components (charts, selectors)

├── services/           # Data fetchers for crypto, REITs, gold

├── utils/              # Regression, correlation, helpers

├── hooks/              # Custom data fetching hooks

├── pages/              # Main dashboard layout


API Sources
CoinGecko - https://www.coingecko.com/en/api

Yahoo Finance Chart API - https://query1.finance.yahoo.com/

GoldAPI - https://www.goldapi.io/dashboard









