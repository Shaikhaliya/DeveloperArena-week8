# Customer Churn Business Analysis

## Project Overview

This capstone project performs an end-to-end business analysis of customer churn data.

The objective of the project is to identify customer characteristics associated with churn and provide data-driven recommendations to improve customer retention.

The analysis includes data validation, data cleaning, exploratory data analysis, statistical testing, confidence interval analysis, and business recommendations.

---

## Business Problem

Customer churn can negatively impact business growth and revenue.

This project aims to answer the following business question:

> What factors are associated with customer churn, and how can the business use these insights to improve customer retention?

---

## Project Objectives

- Validate and clean customer data
- Analyze customer churn patterns
- Perform exploratory data analysis
- Compare churn across customer groups
- Perform correlation analysis
- Conduct hypothesis testing
- Calculate confidence intervals
- Develop actionable business recommendations
- Create a customer retention implementation plan

---

## Dataset

The project uses a customer churn dataset containing:

- **Rows:** 500
- **Columns:** 9

### Features

- CustomerID
- Tenure
- MonthlyCharges
- TotalCharges
- Contract
- PaymentMethod
- PaperlessBilling
- SeniorCitizen
- Churn

---

## Project Structure

```text
DeveloperArena-Week8/
│
├── data/
│   ├── customer_churn.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   └── 3_analysis.ipynb
│
├── reports/
│
├── presentation/
│
├── README.md
└── requirements.txt
Analysis Workflow
1. Data Cleaning

The dataset was checked for:

Missing values
Duplicate records
Data types
Numerical value ranges
Categorical data consistency

Results:

No missing values found
No duplicate records found
Dataset successfully validated
Cleaned dataset saved for further analysis
2. Exploratory Data Analysis

The project includes the following visualizations:

Customer Churn Distribution
Churn Rate by Contract Type
Churn Rate by Payment Method
Monthly Charges Distribution
Customer Tenure Distribution
Tenure vs Monthly Charges
Correlation Heatmap
Key Findings
Overall Churn
Overall churn rate: 10.6%
Total churned customers: 53 out of 500
Contract Type
Month-to-month churn rate: 20.59%
One-year churn rate: 4.30%
Two-year churn rate: 6.94%

Month-to-month customers had the highest observed churn rate.

Customer Tenure
Average tenure of non-churned customers: 40.15
Average tenure of churned customers: 6.00

Customer tenure showed a statistically significant difference between churned and non-churned customers.

Monthly Charges
Average monthly charges of non-churned customers: 111.72
Average monthly charges of churned customers: 129.77

The difference in monthly charges was statistically significant.

Payment Method
Credit Card churn rate: 13.48%
Electronic Check churn rate: 11.04%
Bank Transfer churn rate: 6.92%
Total Charges

No statistically significant difference in Total Charges was found between churned and non-churned customers.

Statistical Analysis
Hypothesis Test 1: Tenure vs Churn

Result: Statistically Significant

The analysis found a significant difference in customer tenure between churned and non-churned customers.

Hypothesis Test 2: Monthly Charges vs Churn

Result: Statistically Significant

Monthly charges showed a significant difference between churned and non-churned customers.

Hypothesis Test 3: Total Charges vs Churn

Result: Not Statistically Significant

Total charges did not show a statistically significant difference between churned and non-churned customers.

Confidence Interval

The 95% confidence interval for average Monthly Charges was:

109.08 to 118.19

Business Recommendations
1. Focus on Early Customer Retention

Develop onboarding programs and engagement strategies for new customers.

2. Encourage Longer-Term Contracts

Provide incentives for month-to-month customers to move toward longer-term contracts.

3. Review Pricing Strategies

Evaluate pricing and service value for customers with higher monthly charges.

4. Improve Customer Payment Experience

Investigate payment-related customer experience and potential friction points.

5. Develop a Churn Monitoring System

Monitor:

Customer tenure
Monthly charges
Contract type
Payment method
Other customer risk indicators
Implementation Plan
Phase 1

Identify high-risk customers.

Phase 2

Launch targeted retention campaigns.

Phase 3

Monitor churn and retention metrics.

Phase 4

Continuously improve retention strategies using new customer data.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
Installation

Install the required libraries:

pip install -r requirements.txt

Run the notebooks in the following order:

1_data_cleaning.ipynb
2_eda.ipynb
3_analysis.ipynb
Conclusion

This project demonstrates an end-to-end business analysis workflow, from raw data validation to exploratory analysis, statistical testing, and actionable business recommendations.

The findings suggest that customer tenure, contract type, and monthly charges are important variables associated with churn in this dataset.

The project demonstrates how data analysis can help businesses transform raw data into meaningful insights and practical decision-making strategies.



## Step 2 — Save it


File name:


```text
README.md