# Credit Card Delinquency Analysis

## Project Overview
This project analyzes customer financial and behavioral data to identify risk factors contributing to credit card delinquency. The objective is to support proactive risk management and collections strategies using data-driven insights.

## Dataset Description
The dataset contains customer demographics, financial indicators, and payment history, including:
- Age, Income, Credit Score
- Credit Utilization and Debt-to-Income Ratio
- Missed Payments and Payment History (Month 1–6)
- Delinquency indicator (Target Variable)

## Exploratory Data Analysis (EDA)
Key steps performed:
- Identified missing values in income and loan balance
- Handled inconsistencies and outliers
- Analyzed correlations between financial variables and delinquency
- Identified early risk indicators

## Data Preprocessing
- Missing values handled using simple imputer
- Categorical variables encoded
- Features scaled where required

## Model Used
- Logistic Regression (Binary Classification)
- Chosen for interpretability and suitability for financial risk modeling

## Key Insights
- High credit utilization and missed payments strongly correlate with delinquency
- Customers with high debt-to-income ratios show increased risk
- Payment history is a critical early warning indicator

## Business Impact
The insights from this analysis can help:
- Prioritize high-risk customers for early intervention
- Optimize collections strategies
- Reduce delinquency rates through data-driven decision-making

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab
- GitHub


