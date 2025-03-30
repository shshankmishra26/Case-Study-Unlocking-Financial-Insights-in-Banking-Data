# 💼 Power BI Banking Case Study – FinInsight Group

## 📊 Project Title: Unlocking Financial Insights in Banking Data

### 🔍 Overview
This project is a comprehensive banking analysis developed using **Power BI** for **FinInsight Group**, a financial analytics consultancy. The case study explores and visualizes trends using two core datasets:

- **Banking Transactions**
- **Customer Account Details**

The goal is to understand customer behavior, analyze financial health, assess risk, and help banking institutions make data-driven decisions.

---

### 🎯 Objectives

- Analyze customer transaction behavior and trends.
- Understand the relationship between account characteristics and financial health.
- Explore credit score patterns and loan management behavior.
- Build an interactive dashboard for actionable business insights.

---

### 🧾 Datasets Used

#### 📁 Banking Transactions
- `Transaction ID`
- `Account ID`
- `Transaction Type` (Deposit, Withdrawal, Transfer, etc.)
- `Amount`
- `Transaction Date`
- `Branch`

#### 📁 Customer Account Details
- `Account ID`
- `Customer Name`
- `Account Type` (Savings, Current)
- `Balance`
- `Interest Rate`
- `Credit Score`
- `Loan Amount`
- `Region`

---

### 🧹 Data Cleaning & Transformation

- Removed duplicates and handled null values.
- Formatted dates and currency columns.
- Merged datasets on `Account ID`.
- Created derived columns (e.g., `Loan to Balance Ratio`, `Transaction Month`).

---

### 🧱 Data Modeling

- Established relationships using a star schema.
- One-to-many join between `Customer Account Details` and `Banking Transactions`.
- Defined calculated tables and DAX measures.

---

### 📐 Key DAX Measures

- `Total Deposits`
- `Total Withdrawals`
- `Net Transaction Volume`
- `Loan to Balance Ratio`
- `Average Credit Score`
- `MoM Growth` and `YTD Trends`

---

### 📊 Dashboard Features

- **Customer Profile Summary**
- **Transaction Volume by Type & Region**
- **Credit Risk Segmentation**
- **Loan Distribution Insights**
- **Branch Performance Overview**
- Slicers for **Region**, **Account Type**, **Credit Score Band**, and **Date Range**

---

### 📈 Key Insights

- Higher loan-to-balance ratios are linked with lower credit scores.
- Consistent transaction activity correlates with higher account balances.
- Certain regions have clusters of high-risk customers.
- Current accounts show greater transaction activity than savings accounts.

---

### 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Excel (for initial data inspection)

---

### 📁 Repository Structure

