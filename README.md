# Trader Performance vs Market Sentiment Analysis

## Data Science/Analytics Internship Assignment – Primetrade.ai

### Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on the Hyperliquid trading platform. The objective is to identify how market sentiment influences trading behavior and profitability and to suggest actionable trading strategies based on the findings.

---

## Objective

- Analyze the impact of market sentiment on trader performance.
- Compare trading activity during Fear and Greed market conditions.
- Identify behavioral patterns among traders.
- Generate insights that can support better trading decisions.

---

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Features:
  - Date
  - Classification (Fear, Greed, Neutral, Extreme Greed)

### 2. Hyperliquid Historical Trader Dataset
- Features:
  - Account
  - Coin
  - Execution Price
  - Size Tokens
  - Size USD
  - Side (Buy/Sell)
  - Timestamp
  - Closed PnL
  - Leverage
  - Additional trading information

---

## Tools & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

---

## Methodology

1. Loaded both datasets into Google Colab.
2. Performed data exploration.
3. Checked for missing values and duplicate records.
4. Converted timestamps into daily dates.
5. Merged both datasets using the date column.
6. Calculated key trading metrics:
   - Daily Profit/Loss
   - Average Profit/Loss
   - Total Profit/Loss
   - Trade Frequency
   - Market Sentiment Distribution
7. Created visualizations to compare trader performance across different market sentiments.
8. Generated insights and strategy recommendations.

---

## Analysis Performed

- Data Cleaning
- Data Merging
- Daily PnL Analysis
- Average PnL by Market Sentiment
- Total PnL by Market Sentiment
- Market Sentiment Distribution
- Buy vs Sell Analysis
- Data Visualization

---

## Key Insights

- The majority of trades occurred during Fear market conditions.
- Trading performance varied across different market sentiment categories.
- Fear and Greed significantly influenced trader activity.
- Visualizations highlighted clear differences in profitability under various market conditions.

---

## Strategy Recommendations

- Reduce leverage during Fear periods to minimize risk.
- Increase position size cautiously during Greed periods only when supported by strong market signals.
- Monitor market sentiment before entering large trades.
- Combine sentiment analysis with risk management for better trading decisions.

---

## Project Structure

```
Trader_Performance_vs_Market_Sentiment/
│
├── Trader_Performance_vs_Market_Sentiment.ipynb
├── README.md
└── Output Charts
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload both datasets.
3. Run all cells from top to bottom.
4. Review the generated tables, charts, and insights.

---

## Author

**Prathusha H**

Data Science Internship Assignment  
Primetrade.ai
