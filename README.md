# 📊 Finance Analytics Dashboard — Power BI

## 📌 Project Overview

An interactive Finance Analytics Dashboard built using Power BI to analyze financial transactions and present key business insights through interactive visuals.

## 🎯 Project Objectives

- Analyze total transaction amounts
- Track total number of transactions
- Calculate average transaction value
- Analyze fees and taxes
- Compare transaction performance by state
- Analyze customer segments and gender
- Identify monthly transaction trends
- Analyze transaction status and transaction types

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

## 📊 Dashboard Features

### KPI Metrics
- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax

### Visualizations
- Monthly Transaction Amount
- Total Amount by Transaction Status
- Total Amount by State
- Customer Segment-wise Amount
- Total Amount by Gender
- Transaction Type Analysis

### Interactive Filters
- State
- Customer Segment
- Transaction Status
- Gender

## 🧮 DAX Measures

```DAX
Total Amount = SUM(Transactions[Transaction_Amount])

Total Transactions = COUNT(Transactions[Transaction_ID])

Average Transaction Value = AVERAGE(Transactions[Transaction_Amount])

Total Fees = SUM(Transactions[Fees])

Total Tax = SUM(Transactions[Tax])
