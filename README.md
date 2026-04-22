# 📊 Trader Performance vs Market Sentiment Analysis

## 🔹 Overview

This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance using historical trading data and sentiment data.

The goal is to uncover patterns that can help in making better trading decisions.

---

## 🔹 Datasets Used

1. **Bitcoin Market Sentiment Dataset**

   * Columns: Date, Classification (Fear / Greed)

2. **Historical Trader Data**

   * Includes: Account, Execution Price, Size, Side, Timestamp, Closed PnL, etc.

---

## 🔹 Methodology

* Cleaned data (handled missing values, removed duplicates)
* Converted timestamps to date format
* Merged datasets on date
* Created key metrics:

  * Daily PnL
  * Win rate
  * Trade frequency
  * Average trade size
* Performed analysis based on market sentiment

---

## 🔹 Key Insights

* Traders tend to perform better during **Greed** periods compared to Fear periods.
* Trade size and activity increase during Greed sentiment, indicating higher risk-taking behavior.
* Market participation is higher during Greed phases.

---

## 🔹 Strategy Recommendations

1. During **Fear** periods:

   * Reduce position size
   * Avoid high-risk trades

2. During **Greed** periods:

   * Increase trading activity
   * Apply proper risk management (e.g., stop-loss)

---

## 🔹 Visualizations

* Boxplot: PnL vs Market Sentiment
* Bar Chart: Trade Size vs Sentiment

---

## 🔹 How to Run

1. Clone the repository
2. Open the notebook:

   ```
   DataScience.ipynb
   ```
3. Run all cells

---

## 🔹 Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 🔹 Conclusion

Market sentiment has a significant impact on trader behavior and performance. Understanding this relationship helps in improving trading strategies and managing risk effectively.

---
