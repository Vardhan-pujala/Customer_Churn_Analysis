# Customer_Churn_Analysis
# 📊 Customer Churn Analysis (Python + Pandas)

## 🔍 Project Overview

This project analyzes **customer churn behavior** using transactional, subscription, and customer demographic data. The goal is to identify patterns behind customer inactivity and churn.

---

## 📁 Dataset Summary

The dataset consists of multiple tables:

* 👥 **Customers:** 300 records
* 📦 **Subscriptions:** 399 records
* 💳 **Transactions:** 216 records
* ❌ **Churn Records:** 100 customers

---

## 🧹 Data Cleaning

* Removed missing values:

  * FirstName: 1 missing
  * LastName: 1 missing
  * Email: 2 missing
  * PhoneNumber: 2 missing
  * JoinDate: 2 missing
  * Status & Region: 1 missing each

* Final cleaned dataset:
  👉 **291 valid customer records**

---

## 📊 Key Analysis & Insights

### 🔹 1. Customer Status Distribution

* Active Customers: ~148
* Inactive Customers: ~143

👉 Almost **50% churn risk**, indicating retention issues

---

### 🔹 2. Churn Overview

* Total churned customers: **100**
* Churn rate ≈ **34%** (100 out of 291)

👉 High churn rate — needs business attention

---

### 🔹 3. Regional Insights

* Customers distributed across:

  * North America
  * Europe
  * Asia

👉 North America shows strong customer base but also churn presence

---

### 🔹 4. Subscription Behavior

* Total subscriptions: **399**
* Multiple subscriptions per customer observed

👉 Indicates:

* Potential upselling
* But also possible churn after subscription period

---

### 🔹 5. Transaction Analysis

* Total transactions: **216**
* Revenue linked with active users

👉 Inactive users show reduced transaction activity

---

## 📈 Visualizations

* Customer status distribution
* Regional customer distribution
* Churn trends
* Transaction patterns

---

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib

---

## 💡 Key Business Insights

* ⚠️ High churn rate (~34%)
* 📉 Inactive customers nearly equal active users
* 🌍 Region-wise churn patterns can help targeted retention
* 💳 Reduced transactions indicate early churn signals

---

## 🚀 Future Improvements

* 🔮 Build churn prediction model (Logistic Regression / ML)
* 📊 Add KPI metrics (Churn Rate, Retention Rate)
* ⏳ Analyze churn over time (cohort analysis)
* 🎯 Identify high-value customers at risk
* 📉 Create dashboard (Power BI / Tableau)

---

## 👤 Author

Pujala Nagavardhan
Aspiring Data Analyst

---

## ⭐ If you found this useful

Give it a ⭐ and feel free to connect!
