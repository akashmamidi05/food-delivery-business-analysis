# Food Delivery Business Performance Analysis

A portfolio project to explore food-delivery order, customer, restaurant, and delivery data and develop business-focused insights.

> **Project status:** Initial dataset and repository structure prepared. Excel analysis, SQL analysis, Python EDA, and the Power BI dashboard are planned work and will be added after implementation and validation. This repository does not yet represent a completed analysis.

## Objectives

- Understand order volume, order value, and revenue patterns.
- Explore customer and restaurant performance.
- Examine cancellations and delivery efficiency.
- Build reproducible analysis using Excel, SQL Server, and Python.
- Present validated findings in a Power BI dashboard and business recommendations.

## Dataset

The included practice dataset is synthetic. It contains four related CSV tables:

| File | Rows | Purpose |
|---|---:|---|
| `customers.csv` | 300 | Customer attributes |
| `restaurants.csv` | 30 | Restaurant and cuisine attributes |
| `orders.csv` | 1,200 | Order-level details and amounts |
| `deliveries.csv` | 1,092 | Delivery timing and ratings |

The source workbook is available at `Excel/Food_Delivery_Analysis_Dataset.xlsx`. A project brief and data dictionary are in `data/raw/`.

## Repository structure

```text
food-delivery-business-analysis/
├── data/raw/                # Original synthetic CSV data and metadata
├── Excel/                   # Workbook and future Excel analysis
├── SQL/                     # SQL Server scripts
├── Python/                  # Python EDA notebook and scripts
├── PowerBI/                 # Power BI report and screenshots
├── documentation/           # Progress log and final business insights
└── README.md
```

## Tools planned

- Microsoft Excel
- Microsoft SQL Server / SQL Server Management Studio (SSMS)
- Python (Pandas, NumPy, Matplotlib)
- Microsoft Power BI

## Data notes

This is synthetic learning data, not production or customer data. The raw files are preserved as supplied. Missing values and other data-quality conditions should be inspected before analysis; do not assume missing values mean zero.

## Planned workflow

1. Inspect and clean the data in Excel.
2. Load the tables into SQL Server and validate relationships.
3. Answer business questions with SQL.
4. Perform exploratory data analysis in Python.
5. Build an interactive Power BI dashboard.
6. Document validated findings, limitations, and recommendations.

## Current limitations

- No business conclusions or KPI results have been validated yet.
- The Power BI dashboard has not been built.
- SQL and Python analysis files are not yet implemented.
- Dataset values are synthetic and should not be presented as real company performance.

## Author

Akash Mamidi
