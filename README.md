# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data.

The objective is to explore how different market sentiment conditions (Fear, Greed, Extreme Fear, Extreme Greed, and Neutral) influence trading activity, profitability, trade direction, and overall trader behavior.

---
If the GitHub notebook preview does not load, please use NBViewer:
https://nbviewer.org/github/moizbagwan/PrimetradeAI_Assignment_for_Internship/blob/main/PrimetradeAI_Assignment.ipynb

## Datasets Used

### 1. Historical Trader Data
Contains detailed trading information including:

- Account
- Coin
- Execution Price
- Size USD
- Side (BUY/SELL)
- Closed PnL
- Fee
- Timestamp

### 2. Bitcoin Fear & Greed Index
Contains daily market sentiment information including:

- Date
- Sentiment Classification
- Sentiment Score

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Date Standardization
5. Dataset Integration
6. Sentiment-Based Profitability Analysis
7. Trading Activity Analysis
8. BUY vs SELL Performance Analysis
9. Trade Size Analysis
10. Business Insights & Conclusions

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Findings

### Sentiment and Profitability
- Extreme Greed generated the highest average profit per trade.
- Fear generated the highest total profit due to increased trading activity.

### Trading Activity
- Fear periods recorded the highest number of trades.
- Extreme Fear recorded the lowest trading activity.

### BUY vs SELL Performance
- BUY trades performed better during Fear conditions.
- SELL trades generated higher profits during Greed and Extreme Greed periods.

### Trade Size Analysis
- Profitability increased consistently with trade size.
- Very Large trades generated the highest average and total profits.

---

## Business Insights

The analysis demonstrates that market sentiment significantly impacts trader behavior and profitability.

Key observations suggest that:

- Traders become more active during Fear conditions.
- Strong bullish sentiment creates highly profitable trading opportunities.
- Trade direction should be aligned with prevailing market sentiment.
- Position sizing plays a crucial role in overall trading performance.

These findings can be used to build sentiment-aware trading strategies and improve risk management decisions.

---

## Repository Contents

```text
README.md
PrimetradeAI_Assignment.ipynb
```

---

## Author

**Abdul Moiz Bagwan**

Data Science & Machine Learning Enthusiast