# Telco Customer Churn Survival Analysis

A comprehensive survival analysis project examining customer churn patterns in the telecommunications industry using statistical modeling and machine learning techniques.

## Project Overview

This project applies survival analysis techniques to the Telco Customer Churn dataset to understand customer retention dynamics and identify key factors influencing churn. By analyzing the timing and probability of customer churn, we develop actionable insights for targeted retention strategies.

**Dataset Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## Objectives

- Investigate the timing and patterns of customer churn
- Identify key factors that influence customer retention
- Develop data-driven insights for customer retention programs
- Build predictive models to estimate churn probability over time

## Methodology

### 1. Data Preparation & Exploratory Data Analysis (EDA)
- **Dataset**: 7,043 customers with 21 attributes
- **Data Cleaning**: Removed 11 records with missing TotalCharges values
- **Feature Engineering**: Reduced to 10 most significant predictors (9 categorical, 1 continuous)
- **Statistical Testing**: Chi-Square tests to identify significant categorical associations

### 2. Survival Analysis Techniques

#### Nonparametric Analysis
- **Kaplan-Meier Estimator**: Survival function estimation for different customer segments
- **Log-Rank Test**: Statistical comparison of survival curves between groups

#### Semi-Parametric Modeling
- **Cox Proportional Hazards Model**: Multivariate analysis of churn risk factors
- **Schoenfeld Residuals**: Validation of proportional hazards assumption

## Key Findings

### Customer Retention Drivers

**Positive Impact (Lower Churn)**:
- Longer contract terms (especially 2-year contracts)
- Higher tenure with the company
- Tech support services
- Online security and backup services
- Automatic payment methods

**Negative Impact (Higher Churn)**:
- Month-to-month contracts
- Fiber optic internet service
- Higher monthly charges
- Electronic check payments
- Lack of support services

### Statistical Insights

- **Tenure-TotalCharges Correlation**: 0.83 (strong positive)
- **MonthlyCharges-TotalCharges Correlation**: 0.65 (moderate positive)
- **Survival Probability**: ~75% customer retention at 40 months

## Technologies & Tools

- **R** (primary analysis environment)
- Survival analysis packages (`survival`, `survminer`)
- Statistical modeling and visualization libraries
- Data manipulation tools

## Business Recommendations

Based on our analysis, telecommunications companies should:

1. **Promote Long-Term Contracts**: Incentivize 1-year and 2-year contracts to reduce churn
2. **Enhance Fiber Optic Services**: Address quality/satisfaction issues with fiber optic offerings
3. **Expand Support Services**: Increase availability of tech support, online security, and backup services
4. **Encourage Automatic Payments**: Promote automatic payment methods over manual options
5. **Target High-Risk Segments**: Focus retention efforts on customers with short tenure and high monthly charges

## Contributors

- Zakaria Bouhia
- Eya Midouni
- Maryam Teymouri
- Oubeid Gharbi

## Project Timeline

**Completion Date**: August 12, 2024

## License

This project is available under the MIT License.

## References

- IBM Telco Customer Churn Dataset


---

**Note**: This project was developed as part of a survival analysis study to demonstrate practical applications of statistical modeling in customer retention analytics.
