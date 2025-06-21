# 🌧️ Rainfall Trends in India Analysis with Python

This project explores more than a century of India's rainfall data to uncover historical trends, seasonal behaviors, anomalies, and forecast future patterns. By using modern data science techniques, we draw insights essential for agriculture, climate science, and disaster management.

## 📊 Overview

Rainfall significantly influences India's agriculture, economy, and water resources. This analysis:
- Visualizes rainfall trends from 1901 to 2015
- Identifies extreme drought or wet years
- Detects seasonal and monthly patterns
- Applies anomaly detection using machine learning
- Forecasts future rainfall using Prophet

---

## 🗂️ Dataset

- Source: [Rainfall Data India 1901–2015](#)
- Fields include:
  - Monthly rainfall (Jan–Dec)
  - Seasonal aggregates: `Jan-Feb`, `Mar-May`, `Jun-Sep`, `Oct-Dec`
  - Annual totals

---

## 📌 Key Analyses

### 📈 Annual Rainfall Trends
- Plotted 1901–2015 rainfall against historical mean
- Detected significant year-to-year variability without a strong upward/downward trend

### 📆 Monthly & Seasonal Patterns
- July & August = highest average rainfall
- June–September (monsoon) = over 70% of annual rainfall

### 🌍 Climate Change Assessment
- Applied 10-year rolling averages
- Observed slight post-1960 decline in rainfall levels

### 🚨 Drought & Extreme Years
- Used statistical thresholds to classify extreme rainfall years
- Identified major droughts (e.g., 2002, 2009) and excessive rain years (e.g., 1917, 1990)

### 🧠 Anomaly Detection
- Used **Isolation Forest** to flag anomalous years/months
- Visualized annual/monthly outliers

### 📊 Correlation Analysis
- Monsoon (`Jun-Sep`) rainfall shows **0.93 correlation** with annual rainfall
- Other seasons have weaker correlations

### 🤖 Clustering
- KMeans grouped years into `Dry`, `Normal`, and `Wet` categories

### 🔮 Forecasting with Prophet
- Predicted next 20 years of rainfall
- Model shows stable but slightly declining future trends

---

## 🧰 Tech Stack

### 🖥️ Language
- Python 3.8+

### 📚 Libraries & Tools
| Library            | Purpose                                              |
|--------------------|------------------------------------------------------|
| `pandas`           | Data manipulation                                    |
| `numpy`            | Numeric operations                                   |
| `plotly`           | Interactive charts and trends                        |
| `scikit-learn`     | Machine learning (KMeans, IsolationForest)           |
| `prophet`          | Time series forecasting                              |
| `matplotlib`, `seaborn` | Visualizations and statistical plots             |
| `Jupyter Notebook` | Interactive analysis and plotting                    |

---
## 🔮 Results Summary

| Insight                     | Value                                |
|----------------------------|--------------------------------------|
| Highest Correlated Season  | Jun–Sep (r = 0.93)                    |
| Most Rainfall Month        | July                                 |
| Key Drought Years          | 1905, 1965, 2002                      |
| Key Wet Years              | 1917, 1990                            |
| Forecast Outlook (to 2035) | Slight declining trend                |
| Anomaly Detection          | Isolation Forest flagged outliers    |
| Year Grouping              | KMeans: Dry / Normal / Wet            |

---

## 📌 Future Work

- 🌐 Integrate spatial rainfall data by Indian states  
- 🔄 Add support for live rainfall API feeds  
- 🌡️ Compare with temperature trends & ENSO cycles  
- 🧠 Train LSTM-based models for long-term forecasting  

---

## 👤 Author

**Om Aditya**  
🎓 B.Tech @ IIT Jodhpur | Finance, Trading & ML Enthusiast  
🚀 Exploring climate data, AI modeling, and real-world analytics  

- 🔗 [LinkedIn – omaditya8](https://www.linkedin.com/in/omaditya8)  
- 💻 [GitHub – Rohanom](https://github.com/Rohanom)


