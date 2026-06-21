# Quick Commerce Performance Analysis — India

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**Dataset:** 1,000,000 Orders · 8 Platforms · 13 Features

---

## Project Overview

Exploratory Data Analysis on 1 million quick commerce orders across 8 Indian platforms — Blinkit, Zepto, Swiggy Instamart, and 5 others. Analysed delivery speed, customer satisfaction, order value, and platform performance to identify what actually drives ratings.

---

## Business Questions Answered

- Does faster delivery lead to higher customer ratings?
- Which platform performs best across speed, rating, and order value?
- Do discounts improve customer satisfaction?
- Which cities have the slowest delivery times?

---

## Key Findings

| Finding | Detail |
|---------|--------|
| Speed ≠ Satisfaction | Pearson r = 0.042 — near-zero correlation between delivery time and rating |
| Fastest Platform | Zepto (~9.5 min avg delivery) — but not highest rated |
| Highest Rated | Blinkit (avg 3.53/5) |
| Highest Order Value | Swiggy Instamart (₹646 avg) |
| Discounts Don't Help | No meaningful improvement in customer ratings with discounts |
| Slowest Cities | Haridwar (27.5 min avg), Jaipur (20.5 min avg) |

---

## Analysis Structure

- **Univariate EDA** — distributions of delivery time, order value, ratings across platforms
- **Bivariate EDA** — correlation analysis, platform vs. rating, speed vs. satisfaction
- **Insights Dashboard** — consolidated visual summary of key findings

---

## Charts

### Univariate EDA
![Univariate EDA](univariate_eda.png)

### Bivariate EDA
![Bivariate EDA](bivariate_eda.png)

### Insights Dashboard
![Insights Dashboard](insights_dashboard.png)

---

## Files

| File | Description |
|------|-------------|
| `quick_commerce_eda.ipynb` | Full EDA notebook with code and outputs |
| `univariate_eda.png` | Distribution plots |
| `bivariate_eda.png` | Correlation and comparison plots |
| `insights_dashboard.png` | Final insights summary |

---

## How to Use

1. Clone the repo or download `quick_commerce_eda.ipynb`
2. Open in Jupyter Notebook or Google Colab
3. Run all cells — no external dependencies beyond standard Python libraries

---

*Part of my Data Analyst portfolio — [LinkedIn](https://linkedin.com/in/ankita-halabanur) · [GitHub](https://github.com/ankita-halabanur)*
