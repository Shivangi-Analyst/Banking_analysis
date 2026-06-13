# Bank Customer Churn Analysis 🏦

## Project Overview
End-to-end data analysis project to identify 
why bank customers are leaving and predict 
high-risk customers using Python, MySQL, and Power BI.

## Problem Statement
A bank is losing 20.37% of its customers annually.
This project analyzes customer data to find key 
churn drivers and help the bank take preventive action.

## Tools Used
- Python (Pandas, Scipy)
- MySQL
- Power BI
- Jupyter Notebook

## Dataset
- Source: Kaggle
- Records: 10,000 customers
- Features: 12 columns

## Project Structure
- data/ — Raw dataset
- notebooks/ — Python analysis
- sql/ — MySQL queries
- outputs/ — Cleaned data
- dashboard/ — Power BI file

## Key Findings
1. 20.37% overall churn rate
2. Customers aged 44+ are at highest risk
3. High balance customers (₹91K avg) are leaving
4. Germany has 32% churn vs 16% in France/Spain
5. Female churn (25%) is higher than Male (16%)
6. Customers with 3-4 products show 82-100% churn
7. Inactive members churn at 26.85% vs 14.27%

## Analysis Performed
- Exploratory Data Analysis (EDA)
- Hypothesis Testing (T-Test & Chi-Square)
- SQL Business Queries
- Interactive Power BI Dashboard

## Dashboard Pages
- Page 1: Executive Summary
- Page 2: Risk Analysis
- Page 3: Customer Deep Dive
- Page 4: Hypothesis Testing Results

## Statistical Testing Results
| Factor | Test | P-Value | Result |
|--------|------|---------|--------|
| Age | T-Test | 1.24e-186 | Significant |
| Balance | T-Test | 1.27e-32 | Significant |
| Credit Score | T-Test | 0.0067 | Weak |
| Gender | Chi-Square | 2.24e-26 | Significant |
| Country | Chi-Square | 3.83e-66 | Significant |

## Business Recommendations
- Launch retention program in Germany
- Offer priority banking to 44+ customers
- Re-engage inactive members immediately
- Limit product pushing to max 2 products
- Create female-specific banking schemes

## Author
Shivangi sachdeva
