<p align="center">
  <img src="cover_page/customer_churn.png" alt="Churn Project Cover" width="800">
</p>

# 📌 Customer Churn Prediction using Machine Learning

This project focuses on predicting whether a customer will leave (churn) based on historical telecom customer data. By identifying churn-prone customers early, companies can implement targeted retention strategies and reduce revenue loss.

---

## 🔍 Problem Statement

Customer churn is a major challenge for subscription-based businesses. Losing customers not only impacts revenue but also increases the cost of acquiring new customers.  
The goal is to **predict churn in advance**, so the company can take action to retain customers who are at higher risk of leaving.

---

## 🎯 Objective

Build a machine-learning model that:

✔ Classifies customers into **Churn vs No Churn**  
✔ Identifies key factors that drive churn  
✔ Supports business teams in proactive decision-making

---

## 📊 Dataset Overview

A structured dataset with **7,043 telecom customers** containing:

- **Customer profile** (gender, senior citizen, dependents)
- **Service usage** (phone, internet, streaming services)
- **Account details** (contract type, payment method, tenure)
- **Billing information** (monthly & total charges)
- **Churn flag** → Target variable (Yes/No)

The dataset reflects real business-like telecom environments.

---

## 🧠 Workflow & Approach

The project follows a complete **end-to-end ML pipeline**:

1️⃣ Data Loading & Cleaning  
2️⃣ Missing value handling (`TotalCharges` conversion)  
3️⃣ Exploratory Data Analysis (EDA) for insight discovery  
4️⃣ Feature Encoding for categorical attributes  
5️⃣ Train-Test Split  
6️⃣ Model Training (multiple models tested)  
7️⃣ Performance Evaluation  
8️⃣ Model Saving using Pickle for future predictions  

This makes the solution **usable and deployment-ready**.

---

## 📈 Model Results

Multiple classification models were tested.  
The **Random Forest Classifier** performed the best with:

| Metric | Result |
|--------|--------|
| Accuracy | **80–85%** |
| Recall (Churn class) | Good (model captures most churn cases) |

✔ Effective for churn detection rather than guessing imbalance  
✔ Good balance between interpretability & performance

---

## 💡 Key Business Insights

✔ **Month-to-month customers** churn the most → Promote long-term plans  
✔ **Higher monthly charges** increase churn → Offer pricing adjustments  
✔ Customers **without Tech Support / Online Security** churn more → Upsell support services  
✔ **Long-tenure** customers are more loyal → Reward loyalty  
✔ Certain **payment methods** show higher churn → Improve payment experience

🔹 These insights help business teams reduce churn through **targeted retention campaigns**.

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-Learn  
- Jupyter Notebook  
- Pickle for model storage  



