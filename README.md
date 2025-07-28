# Trader-Behavior-Insights
Integrated historical trading data with the Fear &amp; Greed Index to analyze sentiment impact on market behavior, forming a clean dataset for advanced analytics and future AI-driven predictions.



# 📈 Primetrade AI – Sentiment & Trading Data Integration

Primetrade AI is a data analysis project that merges historical trading data with sentiment metrics from the Fear & Greed Index. The goal is to prepare a clean, unified dataset that can be used for deeper financial insights, market behavior exploration, and AI-driven strategy development.

---

## 📊 Project Objective

To understand how market sentiment influences trading patterns by:
- Cleaning and analyzing raw trading and sentiment datasets
- Converting and aligning timestamps
- Merging both datasets based on overlapping date ranges
- Verifying data quality and preparing for further modeling or visualization

---

## 🗂️ Dataset Overview

### 1. `historical_data.csv`
- Contains raw trading activity with timestamps
- Key features: `Timestamp`, price-related metrics

### 2. `fear_greed_index.csv`
- Contains daily sentiment scores and classifications
- Key features: `timestamp`, `value`, `classification`

---

## 🧼 Data Processing Steps

| Step                 | Description                                     |
| --------------------|-------------------------------------------------|
| ✅ Timestamp Parsing | Converted UNIX and millisecond timestamps       |
| ✅ Null Handling     | Checked and handled missing/duplicate records   |
| ✅ Date Alignment    | Filtered to overlapping date ranges             |
| ✅ Data Merge        | Merged sentiment and trading data on date       |
| ✅ Quality Checks    | Validated merged data for consistency           |

---

## 📌 Key Libraries Used
- `pandas`, `numpy`: Data manipulation
- `matplotlib`, `seaborn`: Visualization
- `missingno`: Missing data visualization
- `datetime`: Time formatting and parsing

---

## 📎 Results & Conclusion

The final dataset merges sentiment and trading activity data on a common date column with no missing values. This integrated view enables:
- Sentiment-driven market analysis
- Correlation study between fear/greed and price behavior
- Foundation for AI/ML modeling in financial prediction

---

## 🚀 Future Work

- Visualize trends using rolling averages and heatmaps
- Apply machine learning for market movement prediction
- Explore lagged features to analyze delayed sentiment impact
- Build real-time sentiment dashboards

---

## 💡 Author
Atharva More  
Data & AI Enthusiast | Ex-Bartender turned Analyst  
📧 Contact: [LinkedIn](www.linkedin.com/in/atharva-more-50717b140) | [GitHub](https://github.com/Atharvmore6666)

---





