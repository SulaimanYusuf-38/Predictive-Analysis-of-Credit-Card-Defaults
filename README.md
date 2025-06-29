# 💳 Predictive Analysis of Credit Card Defaults

This project explores a classification problem using a real-world dataset of credit card clients. The goal is to predict whether a customer will default on their next monthly payment based on their demographic and financial history.

## 📌 Objective

To build predictive models that classify clients based on the likelihood of default (`default.payment.next.month`), enhancing the precision of credit risk assessments.

## 🧠 Background

Traditional risk models classify borrowers as "credible" or "not credible" using static thresholds. This project applies data-driven methods to predict individual-level defaults using advanced features such as repayment history, bill amounts, and credit limits.

## 📁 Dataset Description

- **Total records**: 30,000 clients
- **Target variable**: `default.payment.next.month` (1 = default, 0 = no default)
- **Features** include:
  - Demographics: `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`
  - Credit information: `LIMIT_BAL`
  - Payment history: `PAY_0` to `PAY_6`
  - Billing and payment data: `BILL_AMT1–6`, `PAY_AMT1–6`

## 🔍 Methodology

- Data preprocessing and feature exploration
- Exploratory data analysis (EDA) on class imbalance and distributions
- Correlation and outlier analysis
- Model building using:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- Model evaluation using accuracy, precision, recall, and confusion matrix

## 📊 Tools & Libraries

- Python (Jupyter Notebook)
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## ✅ Key Outcomes

- Identified most predictive variables for default risk
- Compared multiple classification models
- Addressed class imbalance and interpretability
- Suggested directions for improving credit screening systems

## 👤 Author

Sulaiman Yusuf Zakaria
Master of Business Analytics  
Macquarie University

---

This project was submitted as **Programming Task 1** for the Business Analytics unit. For academic use only.
