# ecommerce-churn-analysis
Logistic regression and K-means clustering to predict and segment e-commerce customer churn using Python

## Overview 

This project analyzes a 5,630-customer e-commerce dataset to understand what drives churn and segment customers by behavior. The analysis covers data cleaning, exploratory data analysis, churn prediction, and unsupervised clustering.

## Methods

- **Data Cleaning:** Evaluated mean vs. median imputation across 7 columns with missing values; applied median imputation to preserve distribution shape
- **Exploratory Data Analysis:** Visualized variable distributions and identified key churn drivers: tenure, complaint history, and product category
- **Logistic Regression:** Built a churn prediction model (87% test accuracy) using a 70/30 train/test split. Identified tenure and complaint history as the strongest predictors
- **K-Means Clustering:** Segmented customers into 3 behavioral clusters based on tenure and cashback amount to identify high risk vs. loyal customer groups

## Key Findings

- Customers who filed a complaint churned at 32% vs. 11% for those who did not
- Churned customers had a median tenure of 1 month vs. 10 months for retained customers
- Mobile Phone and Mobile categories had the highest churn rates (~27%), Grocery had the lowest (~5%)

## Tech Stack

Python, pandas, scikit-learn, matplotlib

## Data Source

[E-Commerce Dataset](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction) — Kaggle
