# Superstore Sales Dashboard

A dashboard analyzing 4 years of retail sales data (9,994 orders, 2014–2017) using Python and Plotly. Built as a resume/portfolio project targeting data science and business management roles.

---

## Dashboard Preview

Open `superstore_dashboard.html` in any browser for the full interactive dashboard.

---

## Key Features

- **Executive KPI Summary** — 6 metrics: Revenue, Profit, Margin, Orders, Avg Order Value, Ship Days
- **Pareto 80/20 Analysis** — which 20% of products drive 80% of revenue
- **Revenue & Profit Margin by Category** — donut chart + horizontal bar chart
- **Regional Sales vs Profit comparison** — grouped bar chart by region
- **Monthly Revenue Trend** — with 3-month rolling average overlay
- **Customer Cohort Retention Heatmap** — 13-period cohort analysis
- **Sales Target Gap Analysis** — 10% YoY growth tracking across all months
- **RFM Customer Segmentation** — Champions, Loyal, At Risk, Lost, Potential
- **Discount Elasticity Analysis** — how discount levels impact profit margins
- **Business Recommendations** — 6 evidence-based actions with priority levels

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Revenue | $2,297,201 |
| Total Profit | $286,397 |
| Overall Margin | 12.47% |
| Technology Margin | 17.40% (highest category) |
| Furniture Margin | 2.49% (barely profitable) |
| Orders with 31%+ discounts | -91.5% avg margin |
| Monthly target hit rate | 26/48 months hit the 10% YoY growth target |
| West Region | Highest profit margin at 14.94% |

---

## Tech Stack

- **Python 3**
- **pandas** — data loading, cleaning, aggregation
- **numpy** — numerical operations
- **plotly** — interactive chart generation and HTML export
- **zipfile** — reading the compressed dataset

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd superstore-sales-dashboard
   ```

2. **Install requirements**
   ```bash
   pip install pandas numpy plotly
   ```

3. **Download the dataset**

   Download `Sample - Superstore.csv.zip` from Kaggle and place it in the root folder:
   [https://www.kaggle.com/datasets/vivek468/superstore-dataset-final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

4. **Run the notebook**

   Open `superstore_analysis.ipynb` in Jupyter and run Blocks 1 through 4 in order.

5. **View the dashboard**

   Open `superstore_dashboard.html` in any browser.

---

## Project Structure

```
├── Sample - Superstore.csv.zip   # Raw dataset (download from Kaggle)
├── superstore_dashboard.html     # Output: interactive dashboard
├── superstore_analysis.ipynb     # Jupyter notebook (all analysis code)
└── README.md                     # This file
```

---

## Business Concepts Used

- **RFM Segmentation** — Recency, Frequency, Monetary scoring for customer classification
- **Pareto Principle (80/20 Rule)** — identifying high-value sub-categories driving revenue
- **Cohort Analysis** — tracking customer retention over 13 monthly periods
- **Discount Elasticity** — measuring profit margin sensitivity to discount levels
- **KPI Dashboarding** — executive-level summary metrics for business performance
- **Sales Target Tracking** — measuring actual vs. target performance with 10% YoY growth goal

---

## Author

Built as a portfolio project.
