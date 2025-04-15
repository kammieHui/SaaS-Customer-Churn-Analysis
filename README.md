# 📉 SaaS Customer Churn Analysis Dashboard

A Power BI dashboard project analyzing churn patterns for a subscription-based telecom service. Built using a public dataset with near 7,000 customer records.

---

## 📌 Project Objective

Understand which customer profiles are most likely to churn, and uncover key drivers such as contract type, monthly charges, and service features. The goal is to help reduce churn and support retention strategies.

---

## 🗂️ Dataset Information

- **Source**: [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)
- **Size**: 7,043 rows x 21 columns
- **Timeframe**: Historical (no date column included)
- **Target Variable**: `Churn` (Yes/No)

### 🔑 Key Columns:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `Contract`, `PaperlessBilling`, `PaymentMethod`
- `InternetService`, `OnlineSecurity`, `StreamingTV`, etc.
- `MonthlyCharges`, `TotalCharges`, `tenure`

---

## 🎯 KPIs (DAX Measures)

- Total Customers
- Churned Customers
- Churn Rate (%)
- Avg Monthly Charges
- Churned Revenue
- Revenue Loss %

---

## 📊 Dashboard Visuals

| Visual | Description |
|--------|-------------|
| 📊 Bar Chart | Churn Rate by Contract Type |
| 🔁 Donut Chart | Churned vs Non-Churned Customers |
| 📈 Line Chart | Churn Rate by Tenure Group |
| 🧾 Table | Churned Revenue by Payment Method |
| 📍 Map (optional) | Churn by Region (if you simulate location) |
| 🧠 Tooltip Page | Customer segment details (MonthlyCharges, Tenure, Services Used) |

---

## 🔍 Key Insights (To Be Filled After Analysis)

- Customers on **month-to-month** contracts churn more than long-term plans.
- Customers using **electronic checks** are more likely to churn than those using credit cards.
- Higher **monthly charges** combined with **no online security** leads to higher churn.

*(Add more as you analyze)*

---

## 🛠 Tools Used

- Power BI
- DAX
- Excel (for raw data)
- Optional: Python (for additional cohort or ML work)

---

## 📁 Files

- `Telco_Churn_Analysis.pbix`
- `telco_customer_churn.csv`
- `dashboard_preview.png`
- `README.md`

---

## 📚 Learnings (Optional)

- Practiced DAX to calculate churn, revenue loss, and segment behavior.
- Improved dashboard layout planning for stakeholder communication.
- Learned to interpret churn metrics in the context of business operations.

---
