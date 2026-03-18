# 🎬 IMDB Top 1000 Movies — Excel Analytics Dashboard

A fully interactive, multi-sheet Excel dashboard analyzing **673 top-rated films** from the IMDB Top 1000 list, spanning **1930–2019**.

---

## 📊 Dashboard Overview

| Sheet | Description |
|---|---|
| 📊 Overview Dashboard | KPI cards, genre distribution, rating breakdown |
| 💰 Financial Dashboard | Revenue analysis, correlation, $100M+ club |
| 🔍 Deep Dive Analysis | Directors, stars, runtime, certificates |
| 🎛️ Interactive Controls | Dynamic movie lookup & director stats |
| 📋 Raw Data | 673 movies × 16 fields |
| ⚙️ Helper / Scatter Data | Pre-aggregated chart datasets |

---

## 🔢 Key Metrics

| Metric | Value |
|---|---|
| Total Movies | 673 |
| Year Range | 1930 – 2019 |
| Average IMDB Rating | 7.94 |
| Total Gross Revenue | $53.97 Billion |
| Average Gross per Film | $80.19 Million |
| Movies with $100M+ Gross | 182 |
| Average Runtime | 124 minutes |
| Max Meta Score | 100 |

---

## 🏆 Top Films

**Highest Rated:**
1. The Shawshank Redemption — ⭐ 9.3
2. The Godfather — ⭐ 9.2
3. The Dark Knight — ⭐ 9.0

**Highest Grossing:**
1. Star Wars: Episode VII — $936M
2. Avengers: Endgame — $858M
3. Avatar — $760M

---

## 💡 Key Insights

- **Drama** is the most common genre (26%) but **Action** earns 3× more on average ($160M vs $48M)
- Rating–Gross correlation is only **0.118** — commercial success ≠ critical acclaim
- The **2000s** produced the most top-1000 films (192)
- **Steven Spielberg** leads directors with 13 films in the top 1000
- **182 films (27%)** crossed the $100M gross milestone

---

## 🛠️ Excel Features Used

- `VLOOKUP` / `INDEX-MATCH` for interactive lookups
- `COUNTIF`, `AVERAGEIF`, `SUMIF` for aggregations
- `CORREL` for rating–revenue correlation
- Data Validation dropdowns for interactive controls
- Conditional Formatting for KPI highlights
- Named ranges for clean formula references

---

## 📁 Dataset

- **Source:** IMDB Top 1000 Movies dataset
- **Rows:** 673 films
- **Columns:** Movie Title, Year, Certificate, Runtime, Genre, IMDB Rating, Meta Score, Director, Stars (×4), No. of Votes, Gross Revenue, Runtime (min), Primary Genre

---

## 🚀 How to Use

1. Download `IMDB_Dashboard.xlsx`
2. Open in Microsoft Excel (2016+ recommended)
3. Navigate to **Interactive Controls** sheet
4. Use the dropdown to select any movie or director
5. Explore the three dashboard tabs for visual analysis

---

*Built with Microsoft Excel | Dataset: IMDB Top 1000*
