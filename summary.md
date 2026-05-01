# Trader Sentiment Analysis — Summary

---

## Methodology

The analysis was conducted by integrating two datasets: market sentiment (Fear/Greed Index) and historical trader activity.
Data was cleaned, timestamps were standardized, and both datasets were merged at a daily level.

Key steps:

* Handled missing values and ensured data consistency
* Converted timestamps using proper datetime parsing
* Created features such as win rate and trading behavior indicators
* Aggregated metrics by sentiment categories

---

## Key Insights

1. **Higher Profitability During Greed**
   Traders achieve the highest average PnL and win rates during Extreme Greed periods, indicating favorable market conditions and strong momentum.

2. **Riskier Behavior During Fear**
   Trade sizes are significantly larger during Fear periods, suggesting traders take higher risks under uncertain market conditions.

3. **Inefficient Risk Allocation**
   Despite larger trade sizes during Fear, profitability does not increase proportionally, indicating suboptimal decision-making and emotional bias.

---

## Strategy Recommendations

* **Reduce Position Size in Fear**
  Limit exposure during Fear periods to manage downside risk.

* **Leverage Greed Periods**
  Increase participation during Greed phases where market conditions are more favorable.

* **Adopt Sentiment-Aware Trading**
  Adjust position sizing and trading frequency based on market sentiment to optimize risk-reward balance.

---

## 🏁 Conclusion

Market sentiment has a significant impact on both trader behavior and performance.
The findings highlight that traders tend to exhibit emotional biases, especially during Fear periods, leading to inefficient risk-taking.

Incorporating sentiment-based signals into trading strategies can improve decision-making, enhance risk management, and lead to more consistent trading outcomes.

---
