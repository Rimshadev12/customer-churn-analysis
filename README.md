# customer-churn-analysis
Predicting telecom customer churn using ML models (Logistic Regression, Random Forest, XGBoost) with SMOTE, achieving 82% ROC-AUC.

# 📞 Customer Churn Analysis (Telecom Data)

## 📌 Project Overview
This project predicts **customer churn** for a telecom company using machine learning models.  
The goal is to identify **which customers are at risk of leaving** and uncover the key drivers of churn to enable **business retention strategies**.  

---

## 🔑 Key Features
- **Data Preprocessing & EDA:**
  - Handled missing values, categorical encoding, and feature scaling.
  - Analyzed patterns in churn vs. non-churn customers.

- **Modeling:**
  - Trained multiple classification models: **Logistic Regression, Random Forest, XGBoost**.
  - Addressed data imbalance using **SMOTE (Synthetic Minority Oversampling)**.
  - Achieved **82% ROC-AUC** with XGBoost.

- **Insights:**
  - Identified key churn drivers: **contract type, tenure, monthly charges**.
  - Suggested data-driven strategies to reduce churn risk by **10–15%**.

---

## 🛠️ Tech Stack
- **Languages & Tools:** Python, Pandas, NumPy  
- **ML Models:** Logistic Regression, Random Forest, XGBoost  
- **Libraries:** Scikit-learn, Matplotlib, Seaborn  
- **Techniques:** Feature Engineering, SMOTE, ROC-AUC  

---

## 📊 Results & Insights
- Customers with **month-to-month contracts** and **high monthly charges** are more likely to churn.  
- **Tenure** is a strong retention factor: long-term customers are less likely to leave.  
- The **XGBoost model** provided the best performance (**82% ROC-AUC**).  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-analysis.git
