# Telecom-customer-churn-analysis
churn analysis is done of a telecom dataset using python and its libraries like matplotlib, Scikit-learn, Seaborn etc .

---

## Project Overview

Customer churn is a major challenge for telecom companies because losing customers directly impacts revenue. This project analyzes telecom customer data and builds machine learning models to **predict whether a customer is likely to churn**. The goal is to identify high-risk customers and help businesses design **effective retention strategies**. 

---

# Business Problem

Telecom companies lose significant revenue when customers cancel their services.
The objective of this project is to:

* Identify **customers at high risk of churn**
* Understand **key factors influencing churn**
* Support **data-driven retention strategies**

---

# Dataset Information

The dataset contains telecom customer information including demographics, subscription plans, payment methods, and churn status.

**Key dataset details**

* **33 features** describing customer behavior and subscription details
* Includes **demographics, contract type, payment method, monthly charges, and churn label**
* Target variable: **Churn (Yes / No)**

Examples of features:

* CustomerID
* Gender
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Label
* Churn Reason 

---

# Project Workflow

## 1. Data Cleaning

* Removed unnecessary columns
* Handled missing and null values
* Standardized categorical variables
* Created useful feature categories

## 2. Exploratory Data Analysis (EDA)

Key insights discovered:

* **Month-to-month contract customers have ~40% churn rate**
* Customers with **higher monthly charges churn more**
* **Low tenure customers are high-risk**
* **Electronic check users show higher churn**

Visualizations were used to analyze:

* Churn by contract type
* Churn by payment method
* Churn by gender
* Monthly charges vs churn
* Tenure vs churn

---

# Feature Engineering

Steps performed:

* Removed irrelevant features
* Encoded categorical variables
* Converted target variable
* Created new derived features for modeling

---

# Machine Learning Models

Two models were built to predict churn:

### Logistic Regression

Confusion Matrix Results:

* 918 correctly predicted non-churn customers
* 203 correctly predicted churn customers
* 117 false positives
* 171 missed churn cases

### Random Forest

Model comparison:

| Metric          | Logistic Regression | Random Forest |
| --------------- | ------------------- | ------------- |
| Accuracy        | 80%                 | 80%           |
| ROC-AUC         | 0.839               | 0.840         |
| Churn Recall    | 0.54                | 0.50          |
| Churn Precision | 0.63                | 0.68          |

---

# Key Insights

* Month-to-month contracts have **significantly higher churn**
* Customers with **higher monthly charges are more likely to leave**
* **Low tenure customers are the highest risk segment**
* Payment method **electronic check shows higher churn**

---

# Tools & Technologies

**Programming**

* Python

**Libraries**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

**Environment**

* Jupyter Notebook

---

# Project Outcome

* Built a churn prediction model with **~80% accuracy**
* Identified **key churn drivers**
* Generated insights that can help telecom companies **improve customer retention and increase customer lifetime value (CLTV)**.

---

If you want, I can also help you create a **professional GitHub project structure (folders, files, dataset, notebook, README badges)** so your project **looks much stronger to recruiters.**
