# 📈 Unsupervised Learning-Based Trading Strategy

This project explores an unsupervised learning approach to identify stock trading opportunities across the S&P 500 using various financial indicators. By applying clustering techniques, the model identifies groups of stocks with similar behaviors — potentially informing a portfolio or momentum-based trading strategy.

---

## 🧠 Core Idea

Instead of predicting stock prices, this strategy uses **unsupervised learning** (e.g., KMeans) to:
- Group stocks based on technical indicators like RSI, MACD, ATR, Bollinger Bands, and volatility
- Detect patterns and clusters of high/low-risk or overbought/oversold assets
- Help formulate a systematic, data-driven trading strategy

---

## 📁 Features

- ✅ Scrapes real-time S&P 500 tickers from Wikipedia
- ✅ Fetches historical stock data using `yfinance`
- ✅ Computes technical indicators:
  - RSI (Relative Strength Index)
  - Bollinger Bands (bb_low, bb_mid, bb_high)
  - ATR (Average True Range)
  - MACD (Moving Average Convergence Divergence)
  - Garman-Klass Volatility
- ✅ Applies clustering (e.g., KMeans) to categorize stocks
- ✅ Visualizes results with matplotlib

---

## 🧪 Tech Stack

- Python
- NumPy, Pandas, Matplotlib
- yFinance
- pandas-ta (Technical Analysis)
- Statsmodels
- Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/trading-strategy-unsupervised.git
cd trading-strategy-unsupervised
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

> Or manually install:
```bash
pip install yfinance pandas pandas-ta scikit-learn matplotlib statsmodels
```

### 3. Run the notebook

Open `Unsupervised Learning Trading Strategy.ipynb` in Jupyter:

```bash
jupyter notebook
```

---

## 📊 Output & Insights

- Heatmaps and scatter plots of clustered stocks
- Cluster-specific performance behavior
- Mean reversion or breakout detection strategies

---

## 📚 Inspiration

Inspired by strategies used in hedge funds and quant research, this project simulates a data-first approach to stock grouping using machine learning.

---

## ⚠️ Disclaimer

This project is for educational purposes only and does **not** constitute financial advice or trading recommendations.

