# PrimetradeAI-Data-Science-Internship
Data analysis project exploring the relationship between Bitcoin Fear &amp; Greed sentiment and Hyperliquid trader performance using Python, Pandas, and data visualization.
# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project explores the relationship between Bitcoin market sentiment and trader performance using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The objective is to identify patterns between market sentiment (Fear/Greed) and trading outcomes, helping uncover insights that can contribute to smarter trading strategies.

---

## Datasets

### 1. Bitcoin Fear & Greed Index
Features:
- Date
- Classification (Fear, Greed, Extreme Fear, Extreme Greed)

### 2. Hyperliquid Historical Trader Data
Features:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Closed PnL
- Fee
- Timestamp
- Direction

---

## Project Workflow

### Data Preprocessing
- Loaded and cleaned both datasets
- Converted timestamps to datetime format
- Extracted dates from trade timestamps
- Merged trading data with sentiment data

### Exploratory Data Analysis
- Profitability analysis across sentiment classes
- Trade size analysis
- Long vs Short performance comparison
- Win rate analysis
- Top trader analysis
- Coin-wise profitability analysis
- Fee analysis
- Correlation analysis

### Visualizations
- Average PnL by Sentiment
- Trade Count by Sentiment
- Long vs Short Profitability
- Trade Size Analysis
- Win Rate Analysis
- Top Coins by Profit
- Fee Analysis
- Correlation Heatmap
- PnL Distribution Boxplot

---

## Key Findings

- Market sentiment significantly influences trader behavior.
- Trade profitability varies across Fear and Greed periods.
- Long and Short positions perform differently under different market conditions.
- Trade size and win rates exhibit sentiment-dependent patterns.
- Certain coins consistently generate higher profits.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Repository Structure

```
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebook/
│   └── ROUND_0.ipynb
│
├── images/
│   └── charts
│
└── README.md
```

---

## Author

Krish Raina

B.Tech CSE | Data Science & Machine Learning Enthusiast

GitHub: https://github.com/Krish-raina57
