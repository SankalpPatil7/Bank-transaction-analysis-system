# Bank-transaction-analysis-system
# 💳 Bank Transaction Analysis System

A Python-based data analytics project that analyzes bank transaction data to generate meaningful financial insights. The system cleans raw transaction records, extracts vendors, categorizes expenses, detects anomalies, and generates a comprehensive spending report using **Python** and **Pandas**.

---

## 📌 Project Overview

Managing personal finances becomes difficult when thousands of bank transactions are stored in raw statements. This project transforms raw transaction data into structured financial insights by performing data cleaning, vendor extraction, spending categorization, trend analysis, and anomaly detection.

The project demonstrates practical applications of **data preprocessing**, **data analysis**, and **rule-based transaction intelligence**.

---

## 🚀 Features

### ✅ Data Cleaning
- Handles inconsistent date formats
- Cleans currency symbols (₹, Rs.)
- Converts transaction amounts into numeric format
- Removes duplicate records
- Standardizes transaction types (Credit/Debit)

### ✅ Vendor Extraction
- Extracts merchant names from transaction descriptions
- Normalizes different merchant name variations
- Uses a rule-based keyword matching approach

Example:

```
UPI-AMAZONPAY@HDFCBANK
Amazon Pay India
AMAZONIN MARKETPLACE

↓

Amazon
```

---

### ✅ Expense Categorization

Automatically categorizes transactions into:

- Shopping
- Food Delivery
- Groceries
- Transport
- Fuel
- Entertainment
- Investment
- Utilities
- Rent
- Personal Transfer

---

### ✅ Spending Analysis

Calculates:

- Total Credit
- Total Debit
- Net Savings
- Savings Rate
- Top Vendors
- Top Spending Categories

---

### ✅ Monthly Spending Trends

- Monthly expense summary
- Month-wise spending analysis
- Spending comparison across months

---

### ✅ Time-of-Day Analysis

Analyzes spending based on:

- Morning
- Afternoon
- Evening
- Night

---

### ✅ Anomaly Detection

Uses **Z-Score Analysis** to detect unusually large transactions.

Examples:

- High-value Amazon purchases
- Large investment transactions
- Unusual shopping expenses

---

### ✅ Spending Archetype

Identifies the user's spending behavior such as:

- Investor
- Shopaholic
- Foodie
- Traveler
- Balanced Spender

Provides a personalized financial recommendation.

---

## 🛠 Technologies Used

- Python 3
- Pandas
- NumPy

---

## 📂 Project Structure

```
bank-transaction-analysis-system/
│
├── Bank_Transaction_Analysis.ipynb
├── transactions.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 📊 Workflow

```
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Vendor Extraction
      │
      ▼
Category Mapping
      │
      ▼
Financial Analysis
      │
      ▼
Monthly Trends
      │
      ▼
Time Analysis
      │
      ▼
Anomaly Detection
      │
      ▼
Spending Archetype
      │
      ▼
Final Financial Report
```

---

## 📈 Sample Output

```
=========================================================
BANK TRANSACTION ANALYSIS REPORT
=========================================================

Total Credit        : ₹509,774.00
Total Debit         : ₹1,678,901.00

Net Savings         : -₹1,169,127.00
Savings Rate        : -229.34%

---------------------------------------------------------

Top Vendor          : Amazon
Top Category        : Shopping

Spending Archetype  : Shopaholic

---------------------------------------------------------

Largest Transaction : ₹85,492.00

Anomalies Detected  : 46

=========================================================
```

---

## 📚 Key Concepts Used

- Data Cleaning
- Feature Engineering
- Rule-Based Text Processing
- Vendor Normalization
- Dictionary Mapping
- Data Aggregation
- GroupBy Operations
- Pivot Tables
- Statistical Analysis
- Z-Score Based Anomaly Detection
- Financial Analytics

---

## 💡 Future Improvements

- Machine Learning based Vendor Classification
- Interactive Streamlit Dashboard
- Power BI Dashboard Integration
- PDF Statement Parsing
- OCR Support for Scanned Statements
- AI-powered Spending Recommendations
- Budget Prediction
- Expense Forecasting

---

## 🎯 Learning Outcomes

Through this project I learned:

- Data preprocessing using Pandas
- Handling inconsistent real-world datasets
- Rule-based transaction classification
- Financial data analytics
- Statistical anomaly detection
- Feature engineering
- Exploratory Data Analysis (EDA)
- Writing reusable Python functions

---

## 👨‍💻 Author

**Sankalp Patil**

Engineering Student | Python Developer | Data Analytics Enthusiast

GitHub: https://github.com/your-github-username

LinkedIn: https://linkedin.com/in/your-linkedin-profile

---

⭐ If you found this project useful, consider giving it a Star!
