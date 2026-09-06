# DecodeLabs Project 2 — Exploratory Data Analysis (EDA)

## Project Overview
This project was completed as **Project 2: Exploratory Data Analysis (EDA)** for the DecodeLabs Data Analytics Industrial Training program.

The objective is to explore the dataset and uncover meaningful **patterns, trends, distributions, relationships, and outliers** using descriptive statistics and visual analysis.

## Objectives
- Understand the structure and quality of the dataset
- Calculate count, mean, median, standard deviation, minimum and maximum
- Analyze product performance and monthly trends
- Explore order status, payment method and referral source distributions
- Detect unusually high order values using the IQR method
- Analyze numerical relationships using correlation
- Summarize evidence-based observations

## Dataset Overview
The analysis uses the `Raw Data` sheet from the project workbook.

| Item | Value |
|---|---:|
| Records | 1,200 |
| Columns | 16 |
| Unique Customers | 1,189 |
| Duplicate Rows | 0 |
| Missing Cells | 309 |
| Date Range | 2023-01-01 to 2025-06-30 |

> **Note:** Year-to-year comparisons should be interpreted carefully when a year does not contain a complete calendar period.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, Excel/OpenPyXL.

## EDA Workflow
1. Dataset overview
2. Data quality checks
3. Descriptive statistics
4. Product analysis
5. Monthly trend analysis
6. Category analysis
7. Distribution analysis
8. IQR outlier detection
9. Correlation analysis
10. Visualizations
11. Key observations and conclusion

## Repository Structure
```text
DecodeLabs-Project-2-EDA/
├── README.md
├── requirements.txt
├── data/
│   └── Project_2_EDA_Report_Final.xlsx
└── notebooks/
    └── project2_eda.ipynb
```

## Deliverables
- **Excel report:** organized EDA results, visualizations, data-quality summary, correlation analysis, outlier analysis and raw data.
- **Jupyter notebook:** reproducible Python workflow for the EDA.

## Conclusion
This project demonstrates how exploratory analysis can transform raw order data into meaningful findings about sales performance, trends, order behavior, relationships and unusual observations.
