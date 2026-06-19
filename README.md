# Quick Commerce Performance Analysis — India
EDA on 1 million orders across 8 Indian quick commerce platforms.
## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, SciPy, Jupyter Notebook
## Key Findings
- Zepto is fastest (~9.5 min) but not highest rated
- Blinkit leads in customer satisfaction (avg 3.53/5)
- Swiggy Instamart has highest order value (₹646 avg)
- Delivery speed has near-zero correlation (-0.042) with customer rating
- Discounts do not improve customer ratings
- Haridwar and Jaipur have slowest deliveries (27.5 and 20.5 min)

### Hypothesis Testing
Hypothesis test (t-test, p < 0.0001) confirms delivery speed has no practical impact on ratings — statistically significant but negligible effect size (mean diff = 0.066)
## Charts
![Univariate EDA](univariate_eda.png)
![Bivariate EDA](bivariate_eda.png)
![Insights Dashboard](insights_dashboard.png)

Interactive Plotly charts are embedded directly in the notebook — open `quick_commerce_eda.ipynb` on GitHub to view them rendered.
