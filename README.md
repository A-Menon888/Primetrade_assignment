# Trader Performance vs Market Sentiment

## Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

The goal is to understand how market emotions influence trading outcomes and identify patterns that can improve decision-making.

---

## Datasets Used
- Historical trader data (Hyperliquid)
- Bitcoin Fear & Greed Index

---

## Key Steps
- Data cleaning and preprocessing
- Timestamp alignment and dataset merging
- Feature engineering (profitability indicators)
- Exploratory data analysis (EDA)

---

## Key Insights
- Traders are most profitable during **Greed** phases.
- **Extreme Greed** shows higher win rates but lower profits per trade.
- Larger trade sizes are observed during **Fear** and **Extreme Greed**, indicating emotional trading.
- A **contrarian pattern** emerges:
  - Buying performs better during Fear
  - Selling performs better during Greed

---

## Output
The full analysis, visualizations, and code are available in for furthur verification:
- `task.ipynb`

---

## Conclusion
Market sentiment clearly affects how traders behave. Even though traders win more often in extreme conditions, they don’t necessarily make more money. What matters more is how much they make on winning trades, not just how often they win.
---
