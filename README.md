# Retail Risk & Operational Optimization Analytics

Statistical analysis of retail operations data to identify the key drivers of
business risk, combining Excel dashboarding with IBM SPSS regression and
hypothesis testing to support data-driven retail decision-making.

## Overview

This project analyzes retail operational data to identify the key factors
influencing business risk, using Microsoft Excel and IBM SPSS Statistics. A
dataset of 15,000 retail observations was examined to evaluate pricing,
inventory, customer behavior, and operational performance through dashboard
reporting and statistical analysis. The project demonstrates how descriptive
and inferential analytics can support data-driven decision-making in retail
operations.

## Repository Structure

```
risk-and-operational-optimization/
├── README.md
├── retail_store_product_sales_dataset.csv   # Raw retail observations (15,000 records)
├── retail_analysis_workbook.xlsx             # Excel analysis, KPIs, and PivotTables
├── analysis.sav                              # SPSS dataset
└── analysis_report.pdf                       # Statistical analysis report
```
## Dataset

The dataset contains 15,000 synthetic financial transaction records
used to analyze patterns associated with fraudulent transactions.

**Source:** Kaggle  
**Dataset:** Retail Store Product Sales Dataset Analysis   
**License:** CC0: Public Domain

**Link:** [Click Here](https://www.kaggle.com/datasets/ranaghulamnabi/retail-store-product-sales-dataset-analysis)

## Tools & Methods

**Microsoft Excel**
- Interactive dashboard development
- Key performance indicator (KPI) calculation
- PivotTables for operational summaries
- Chart-based visualization of trends and business reporting

**IBM SPSS Statistics**
- Descriptive statistics and assumption testing
- Correlation analysis
- Multiple linear regression modeling
- One-Way ANOVA for group comparisons
- Chi-Square Test of Independence for categorical associations

## Key Findings

- **Customer sentiment and return rate** were the strongest factors influencing retail risk.
- The **multiple linear regression model explained 43.4%** of the variation in retail risk score, indicating moderate predictive capability.
- **Retail risk differed significantly across stock categories** (One-Way ANOVA).
- The relationship between stock status and risk category was **statistically significant but showed a very weak association** (Chi-Square Test of Independence).
- Overall, customer experience and inventory management emerged as important levers for reducing operational risk.

## Conclusion

This project demonstrates how Microsoft Excel and IBM SPSS Statistics can be
integrated to transform retail data into actionable business insights.
Through dashboard development and statistical modeling, the analysis
identified key operational factors associated with retail risk and provided
evidence-based insights that can support inventory management, pricing
strategies, and customer-focused decision-making.

## How to Explore This Project

- **Dashboard & KPIs:** open `excel/retail_analysis_workbook.xlsx` in Microsoft Excel.
- **Full statistical results:** `spss/analysis_report.pdf` can be read with any PDF viewer — no SPSS license required.
- **Raw SPSS files:** `spss/analysis.sav` (dataset) and `spss/analysis.spv` (output) require IBM SPSS Statistics to open.
- **Source data:** see `data/README.md` for a description of the underlying dataset.
