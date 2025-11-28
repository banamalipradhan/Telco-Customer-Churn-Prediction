<p align="center">
  <img src="cover_page/customer_churn.png" width="800" alt="Customer Churn Prediction Cover Page">
</p>

# Customer Churn Prediction using Machine Learning

This project focuses on predicting whether a telecom customer will leave the service (churn) by analyzing their demographic, service usage, and account information. The objective is to help companies identify high-risk customers early and reduce revenue loss through targeted retention strategies.

---

## Problem Statement

Customer churn is a critical challenge in telecom businesses. Losing customers leads to a decline in revenue and higher acquisition costs.  
The main goal of this project is to predict churn in advance so the business can proactively retain customers who are likely to discontinue their services.

---

## Objectives

- Build a machine-learning model to classify customers as Churn or Not Churn
- Identify key churn-driving factors for business decision-making
- Provide actionable recommendations to reduce churn
- Save the best model for deployment use

---

## Dataset Overview

The dataset contains 7,043 customer records with the following categories:

- Customer Profile: gender, senior citizen, dependents
- Services: phone, internet, streaming services, support services
- Account Details: contract type, payment method, tenure
- Billing Information: monthly and total charges
- Target Variable: churn status (Yes/No)

The dataset closely represents a real telecom business environment.

---

## Data Science Workflow

### 1. Data Loading & Initial Checks
- Loaded dataset and reviewed structure
- Identified missing and incorrect data types

### 2. Data Cleaning
- Converted improper data types (e.g., TotalCharges to numeric)
- Handled missing values and formatting errors

### 3. Exploratory Data Analysis
- Investigated patterns related to churn
- Analyzed customer retention behavior

### 4. Feature Engineering
- Encoded categorical variables into machine-readable form
- Created the final feature matrix and target variable

### 5. Train-Test Split
- Divided data into training and testing sets

### 6. Model Building
Models tested:
- Logistic Regression (baseline)
- Random Forest Classifier (best performing)
- Other classification methods considered

### 7. Evaluation
The final model demonstrated:

- Accuracy: approximately 80–85 percent
- Good recall for churn class
- Effective identification of high-risk customers

### 8. Deployment Preparation
- Model saved using Pickle format for future prediction use

---

## Key Business Insights

| Insight | Recommendation |
|--------|----------------|
| Customers with month-to-month contracts churn more | Promote long-term plans and loyalty programs |
| Higher monthly charges increase churn | Offer pricing adjustments or bundled packages |
| Lack of technical support or security services raises churn | Upsell value-added services |
| Lower tenure customers show higher churn | Improve onboarding and engagement |
| Electronic check payment users churn more | Encourage secure digital payment options |

These insights can help business teams design targeted retention strategies.

---

## Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Pickle

## Author
**Banamali Pradhan** — Aspiring Data Analyst  
Transitioning from Pharmaceutical Industry to Data Analytics  
[LinkedIn Profile](https://www.linkedin.com/in/banamali-pradhan)
