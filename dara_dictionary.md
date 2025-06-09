# 📘 Data Dictionary: Football Social Media & Business Dataset

This file explains each feature in the dataset used for analyzing trends across 7 top European football clubs (2009–2025).

---

## 🏟️ General Club Information

| Column | Description | Type |
|--------|-------------|------|
| `Club` | Name of the football club | Categorical |
| `Instagram Handle` | Official IG username | Text |
| `Twitter Handle` | Official Twitter username | Text |

---

## 📱 Social Media Metrics

| Column | Description | Type |
|--------|-------------|------|
| `Instagram Followers [2013–2025]` | Yearly IG follower count | Numeric |
| `Twitter Followers [2013–2025]` | Yearly Twitter follower count | Numeric |
| `Total Social Audience` | IG + Twitter followers (combined) | Numeric |
| `YoY Instagram Growth (%)` | Percentage change in IG followers compared to previous year | Numeric |
| `Average Daily IG Posts` | Average number of Instagram posts per day | Numeric |
| `Yearly Instagram Posts [2013–2025]` | Total Instagram posts per year | Numeric |

---

## 🏆 Performance Metrics

| Column | Description | Type |
|--------|-------------|------|
| `Trophies Won [2009–2025]` | Total trophies won by the club in each year | Numeric |
| `UCL Win` | Whether the club won the UEFA Champions League in a given year (1 = yes, 0 = no) | Binary |
| `Star Signing` | Whether the club bought a high-profile player before the season (1 = yes, 0 = no) | Binary |

---

## 💰 Financial Metrics

| Column | Description | Type |
|--------|-------------|------|
| `Revenue [2009–2024]` | Club revenue per year (millions, if applicable) | Numeric |
| `Spending [2010–2025]` | Total club expenditures per year | Numeric |

---

## 📌 Notes

- All year-specific columns are indexed by year from 2009–2025 (where applicable).
- Missing values represent years where data was not publicly available or not applicable.
- Growth percentages are calculated using:  
  `((followers_current_year - followers_last_year) / followers_last_year) * 100`

---

## 📂 Last Updated

- Date: **June 6, 2025**
- Author: Mohammad Yousefizadeh