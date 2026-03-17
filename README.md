# Customer Churn Prediction

## 🚀 Project Highlights
- End-to-end machine learning pipeline
- Feature engineering & selection
- Handling imbalanced data
- Threshold optimization
- Model comparison (Logistic vs Random Forest)

## Project Overview
This project aims to predict customer churn for a telecom company using machine learning techniques.
The goal is to identify customers who are likely to leave the service and help the business take proactive actions to retain them.
This problem is important because customer retention is more cost-effective than acquiring new customers.

## Dataset
IBM Telco Customer Churn Dataset
The dataset contains customer demographics, service usage, and billing information for a telecom company.

## Project Workflow
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Encoding
- Model Building (Logistic Regression, Random Forest)
- Threshold Optimization

## Models Used
- Logistic Regression (baseline)
- Random Forest (final model)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Business focus: Recall optimization for churn detection

## Feature Engineering
- Created a binary feature: `IsMonthToMonth` to capture high-risk customers
- Evaluated new features and removed weak or redundant ones
- Focused on behavior-based features instead of purely raw variables

## Results

| Model | Recall | Precision | F1 |
|------|--------|----------|----|
| Logistic Regression | 0.79 | 0.50 | 0.61 |
| Random Forest | 0.79 | 0.54 | 0.64 |

The Random Forest model provided better overall performance while maintaining strong recall.
