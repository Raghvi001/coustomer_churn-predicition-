# Customer Churn Prediction

## Overview
Built a complete machine learning pipeline to predict whether a 
telecom customer will churn (leave the service) or stay.
Performed end-to-end analysis on 7043 customers including 
data cleaning, exploratory data analysis, feature engineering 
and comparison of three ML algorithms.

**Dataset:** IBM Telco Customer Churn (Kaggle)
**Best Result:** (will update after model building)

---

## Business Problem
Customer churn is one of the biggest challenges for telecom 
companies. Acquiring a new customer costs 5 times more than 
retaining an existing one. This project builds a model that 
identifies at-risk customers BEFORE they leave, allowing the 
company to intervene with targeted offers or support.

---

## Dataset
- Source: IBM Telco Customer Churn Dataset (Kaggle)
- Size: 7043 customers, 20 features
- Target: Churn (Yes = customer left, No = customer stayed)
- Class balance: 73.5% No churn, 26.5% Churn (imbalanced)

---

## Features
### Numerical Features
| Feature | Description |
|---------|-------------|
| tenure | Number of months with the company |
| MonthlyCharges | Amount charged per month |
| TotalCharges | Total amount charged (fixed from object to float) |

### Categorical Features
| Feature | Description |
|---------|-------------|
| Contract | Month-to-month, One year, Two year |
| InternetService | DSL, Fiber optic, No internet |
| TechSupport | Has tech support or not |
| PaymentMethod | How the customer pays |
| PaperlessBilling | Uses paperless billing or not |
| gender | Male or Female |
| SeniorCitizen | Is a senior citizen or not |
| Partner | Has a partner or not |
| Dependents | Has dependents or not |
| PhoneService | Has phone service or not |
| MultipleLines | Has multiple lines or not |
| OnlineSecurity | Has online security or not |
| OnlineBackup | Has online backup or not |
| DeviceProtection | Has device protection or not |
| StreamingTV | Streams TV or not |
| StreamingMovies | Streams movies or not |

---

## Project Structure
