# FinSight – Financial Analytics Dashboard

## 📊 Project Overview

**FinSight** is an interactive financial analytics dashboard built using **Power BI, DAX, and Power Query**. The dashboard provides business-focused insights into financial transactions, customers, transaction status, fees, tax, and transaction performance.

The project contains two interactive pages:

- **Overview Analysis** – High-level financial KPIs, trends, customer segments, transaction status, states, gender, and transaction types.
- **Transactions** – Detailed record-level transaction analysis.

---

## 🎯 Project Objective

The objective of FinSight is to transform raw financial transaction data into an interactive dashboard that helps business and finance teams understand:

- Overall transaction performance
- Monthly transaction trends
- Customer segment contribution
- Transaction success, failure, and pending status
- State-wise transaction performance
- Transaction type performance
- Fees and tax
- Year-over-year performance

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**

---

## 🔄 Data Preparation

The data was prepared and transformed using **Power Query**.

Key data preparation activities included:

- Data type conversion
- Data cleaning
- Data formatting
- Data consistency checks
- Preparing transaction and customer attributes for analysis

DAX was then used to create calculated measures and KPIs for financial analysis and year-over-year comparisons.

---

## 📈 Dashboard Features

### 1. Overview Analysis

The Overview Analysis page provides a complete summary of financial performance.

### Key Performance Indicators

The dashboard includes KPI cards for:

- **Total Amount**
- **Total Transactions**
- **Average Transaction Value**
- **Total Fees**
- **Total Tax**
- **Year-over-Year comparison**

For the displayed **2025 dashboard view**, the KPIs include:

- Total Amount: **₹1.53M**
- Total Transactions: **190**
- Average Transaction Value: **₹8.07K**
- Total Fees: **₹1.91K**
- Total Tax: **₹343.32**

### Visual Analysis

The dashboard analyzes:

- Monthly transaction trends
- Transaction status
- Customer segments
- State-wise transaction value
- Transaction types
- Gender-wise transaction value

Transaction statuses are categorized into:

- Success
- Failed
- Pending

Customer segments include:

- Retail
- Premium
- SME
- Wealth
- Corporate

---

## 🎛️ Interactive Features

FinSight includes several interactive features for self-service analysis:

- **Year slicer**
- **Occupation slicer**
- **Category slicer**
- **Dynamic Metric selector**
- **Interactive charts**
- **Page navigation**
- **Transaction-level analysis**

The Dynamic Metric selector allows users to change the metric displayed in the analysis.

---

## 📋 Transactions Page

The Transactions page provides a detailed record-level view of the financial data.

The table includes fields such as:

- Transaction ID
- Transaction Date
- Customer Name
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- Total Amount
- Fees
- Tax

This page allows users to move from high-level dashboard insights to individual transaction records.

---

## 🖼️ Dashboard Preview

### Overview Analysis

![FinSight Overview Dashboard](Images/FinSight_Overview.png)

### Transactions Analysis

![FinSight Transactions Dashboard](Images/FinSight_Transactions.png)

---

## 💡 Business Analysis

The dashboard can help answer questions such as:

1. Which customer segments contribute the most transaction value?
2. Which states have the highest transaction activity?
3. How does transaction value change month by month?
4. What proportion of transaction value is successful, failed, or pending?
5. Which transaction types generate the highest amount?
6. How are fees and tax changing compared with the previous year?
7. How does transaction performance vary by customer demographics?

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX
- KPI Development
- Financial Analytics
- Data Visualization
- Interactive Dashboard Design
- Business Analysis
- Dashboard Storytelling

---

## 📂 Repository Structure

```text
finsight-financial-analytics-dashboard/
│
├── README.md
│
├── PowerBI/
│   └── FinSight_Financial_Analytics.pbix
│
├── Images/
│   ├── FinSight_Overview.png
│   └── FinSight_Transactions.png
│
└── Dataset/
    └── financial_transactions.csv
