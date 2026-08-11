# Customer-Churn-Analysis
## Project Description
Analysis of customer churn patterns to identify key factors leading to customer attrition. This project uses Python, SQL, Excel, and Tableau to analyze 440,832 customer records.

## Tools Used
- Python (Pandas, SQLite)
- SQL
- Excel (XLOOKUP)
- Tableau
- Google Colab

## Files Included
- `customer_churn_analysis.ipynb` - Python code (data cleaning, analysis, SQL queries)
- `Customer_Churn_Analysis.xlsx` - Excel report with 5 sheets
- `customer_churn_data.csv` - Full dataset
- `churn_by_subscription.csv` - Churn by subscription type
- `churn_by_contract.csv` - Churn by contract length
- `churn_by_age.csv` - Churn by age group
- `risk_factors.csv` - High-risk customer segments

## Key Findings
- Overall churn rate: 56.71%
- Monthly contracts have 100% churn rate (major issue)
- Support calls > 8: 99.95% churn rate
- Payment delays > 20 days: 100% churn rate
- Churned customers spend $541 vs $750 for retained customers

## Dashboard
Tableau dashboard showing:
- Churn by subscription type
- Churn by contract length
- Churn by age group
- High-risk factors

## How to Use
1. Open `customer_churn_analysis.ipynb` in Jupyter Notebook
2. Review Excel reports for summaries
3. Check Tableau dashboard for visualizations
