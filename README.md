# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data.

The objective is to explore how different market sentiment conditions (Fear, Greed, Extreme Fear, Extreme Greed, and Neutral) influence trading activity, profitability, trade direction, leverage usage, position sizing, and overall trader behavior.

> If the GitHub notebook preview does not load, please use NBViewer:
>
> https://nbviewer.org/github/moizbagwan/PrimetradeAI_Assignment_for_Internship/blob/main/PrimetradeAI_Assignment.ipynb

---

## Datasets Used

### 1. Historical Trader Data

Contains detailed trading information including:

- Account
- Coin
- Execution Price
- Size USD
- Side (BUY / SELL)
- Closed PnL
- Fee
- Leverage
- Timestamp

### 2. Bitcoin Fear & Greed Index

Contains daily market sentiment information including:

- Date
- Sentiment Classification
- Sentiment Score

---

## Project Workflow

### Data Preparation

- Data Loading
- Data Exploration
- Data Cleaning
- Missing Value Handling
- Date Standardization
- Dataset Integration

### Exploratory Data Analysis

- Sentiment Distribution Analysis
- Sentiment-Based Profitability Analysis
- Trading Activity Analysis
- BUY vs SELL Performance Analysis
- Trade Size Analysis

### Advanced Analysis

- Win Rate Analysis by Market Sentiment
- Leverage vs Sentiment Analysis
- Top & Worst Trader Analysis
- Top Trader Sentiment Behavior
- Coin-wise Performance Analysis
- Time-of-Day Analysis
- Outlier Removal & Robust Analysis

### Business Insights

- Trading Strategy Recommendations
- Risk Management Insights
- Sentiment-Aware Trading Observations
- Final Conclusions

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

### Market Sentiment & Profitability

- Extreme Greed generated the highest average profit per trade.
- Fear generated the highest total profit due to increased trading activity.
- Market sentiment showed a measurable impact on trader performance.

### Trading Activity

- Fear periods recorded the highest number of trades.
- Extreme Fear periods showed the lowest trading activity.
- Traders tend to become more active during uncertain market conditions.

### BUY vs SELL Performance

- BUY trades generally performed better during Fear conditions.
- SELL trades generated stronger profitability during Greed and Extreme Greed periods.
- Trade direction effectiveness depends on prevailing market sentiment.

### Trade Size Analysis

- Profitability increased consistently with trade size.
- Very Large trades generated the highest average and total profits.
- Position sizing significantly influenced overall returns.

### Leverage Analysis

- Moderate leverage provided a more balanced risk-reward profile.
- Excessive leverage increased performance volatility and downside risk.
- Sentiment and leverage jointly influenced profitability.

### Trader Performance

- Top-performing traders demonstrated stronger consistency across sentiment conditions.
- Winning traders adapted more effectively to changing market environments.

### Timing & Asset Selection

- Trading performance varied across different trading sessions.
- Certain coins consistently outperformed others under specific sentiment conditions.

---

## Business Insights & Recommendations

The analysis demonstrates that market sentiment significantly impacts trader behavior and profitability.

Key observations suggest that:

- Traders become more active during Fear conditions.
- Strong bullish sentiment creates highly profitable trading opportunities.
- Trade direction should be aligned with prevailing market sentiment.
- Moderate leverage provides a better risk-reward balance than excessive leverage.
- Position sizing plays a critical role in overall trading performance.
- Market sentiment can be used as a supporting signal for trade selection and risk management.

These findings can be leveraged to build sentiment-aware trading strategies and improve trading decision-making.

---

## Repository Contents

```text
PrimetradeAI_Assignment_for_Internship/
│
├── PrimetradeAI_Assignment.ipynb
├── README.md
└── Dataset Files
```

---

## Author

**Abdul Moiz Bagwan**

Data Science | Machine Learning | AI Enthusiast

GitHub: https://github.com/moizbagwan

LinkedIn: [https://www.linkedin.com/in/abdul-moiz-bagwan](https://www.linkedin.com/in/abdul-moiz-bagwan-7a436028a/)
