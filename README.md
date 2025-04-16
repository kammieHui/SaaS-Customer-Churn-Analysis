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
- Total Revenue
- Churn Rate (%)
- Avg Monthly Charges
- Median Tenure(Mths) 

---

## 📊 Dashboard Visuals

| Visual | Description |
|--------|-------------|
| 🔁 Donut Chart | Churned vs Non-Churned Customers |
| 📊 Bar Chart | Revenue Loss by Churn|
| 📊 Bar Chart | Contract Type of Churn|
| 📊 Bar Chart | Tenure Length of Churn|
| 📊 Bar Chart | Payment and Billing Preference for Churned Customers |
| 🔁 Donut Chart | Churned Customers Demographic|
| 🔁 Donut Chart | Services Churned|
| 🧠 Tooltip Page| Key Insights |

---

## 🔍 Key Insights (To Be Filled After Analysis)

**🧠 No Dependents = Higher Churn:**
- Only 17% of churned customers have dependents.

**📉 Tenure < 6 Months = Risk Zone:**
- 42% of churn happens within first 6 months.

**🧬Non Senior Citizens = Higher Churn:**
- Around 75% of churn are non-Senior Citizens.

**💸 Electronic Check = Risky:**
- Nearly 46% of churned customers paid via electronic check.

---

## 🛠 Tools Used

- Power BI
- DAX
- Optional: Python (for additional cohort or ML work)

---

## 📁 Files

- [Power BI File](power bi/SaaS Customer Churn Analysis.pbix)
- [pdf](pdf/SaaS Customer Churn Analysis (1).pdf)
- [Data File](data/WA_Fn-UseC_-Telco-Customer-Churn.csv)
- `dashboard_preview.png`
- `README.md`

---

## 📚 Learnings (Optional)

- Practiced DAX to calculate churn, revenue loss, and segment behavior.
- Improved dashboard layout planning for stakeholder communication.
- Learned to interpret churn metrics in the context of business operations.

---
