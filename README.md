# 📈 Bitcoin Sentiment & Trader Performance Analysis

> **PrimetradeAI — Data Science Internship Project**

Data analysis project exploring the relationship between **Bitcoin Fear & Greed sentiment** and **Hyperliquid trader performance** using Python, Pandas, and data visualization.

---

## 📌 Objective

Analyze how market sentiment (measured by the Bitcoin Fear & Greed Index) correlates with trading performance on the Hyperliquid platform, uncovering patterns that could inform trading strategies.

## 📂 Project Structure

```
PrimetradeAI-Data-Science-Internship/
├── Bitcoin_Sentiment_Trader_Analysis Round-0.ipynb   # Main analysis notebook
├── fear_greed_index.csv                              # Fear & Greed Index dataset
├── LICENSE                                           # MIT License
└── README.md
```

## 📊 Datasets

| Dataset | Description | Key Features |
|---------|-------------|-------------|
| **Fear & Greed Index** | Daily Bitcoin sentiment scores (0–100) | `date`, `value`, `classification` (Extreme Fear → Extreme Greed) |
| **Hyperliquid Trader Data** | Trading performance metrics | `account`, `pnl`, `volume`, `win_rate`, `trade_count` |

## 🔍 Analysis Workflow

```
Data Collection → Preprocessing → Exploratory Data Analysis → Visualization → Insights
```

1. **Data Preprocessing** — Handling missing values, type conversions, date alignment
2. **Exploratory Data Analysis (EDA)** — Distribution analysis, correlation studies, trend identification
3. **Visual Analysis** — Sentiment trends, PnL distributions, volume vs. sentiment plots
4. **Key Findings** — Statistical relationships between sentiment and trader behavior

## 🛠️ Tech Stack

- **Python 3.x** — Core language
- **Pandas** — Data manipulation & analysis
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive analysis environment

## 🔑 Key Findings

- Market sentiment shows observable patterns in trader behavior and risk appetite
- Periods of **Extreme Fear** correlate with specific trading volume and PnL patterns
- Sentiment transitions (Fear → Greed) reveal potential leading indicators for performance shifts

> *Open the notebook for detailed charts and statistical analysis.*

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/Krish-raina57/PrimetradeAI-Data-Science-Internship.git
cd PrimetradeAI-Data-Science-Internship

# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook "Bitcoin_Sentiment_Trader_Analysis Round-0.ipynb"
```

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Krish Raina** — [GitHub](https://github.com/Krish-raina57) · [LinkedIn](https://www.linkedin.com/in/krish-raina)

*Built during the PrimetradeAI Data Science Internship (2026)*
