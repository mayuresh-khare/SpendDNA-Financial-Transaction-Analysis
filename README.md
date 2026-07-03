# 💳 SpendDNA - Financial Transaction Analysis

> A Python & Pandas based Data Analytics project that transforms raw bank transaction statements into meaningful financial insights by extracting vendors, categorizing expenses, analyzing spending patterns, detecting anomalies, and identifying financial behavior.

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Project Objectives](#-project-objectives)
- [Features Implemented](#-features-implemented)
- [Dataset Information](#-dataset-information)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Key Insights](#-key-insights)
- [Project Structure](#-project-structure)
- [Installation & Usage](#-installation--usage)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

# 📌 Project Overview

SpendDNA is a financial transaction analysis project developed using **Python** and **Pandas**.

The project processes six months of raw bank transaction data and converts it into meaningful business insights through data cleaning, vendor extraction, expense categorization, monthly trend analysis, anomaly detection, and spending behavior analysis.

This project demonstrates practical applications of Data Analytics techniques commonly used in banking and fintech industries.

---

# 🎯 Project Objectives

- Clean and preprocess bank transaction data.
- Extract vendor names from transaction descriptions.
- Categorize transactions into meaningful expense groups.
- Analyze monthly income and expenses.
- Detect unusually large transactions.
- Identify spending behavior patterns.
- Generate business insights from financial data.

---

# ✨ Features Implemented

## ✅ Feature 1 – Transaction Parser

- Loaded and cleaned transaction data
- Removed duplicate records
- Converted dates into datetime format
- Verified missing values

---

## ✅ Feature 2 – Vendor Extraction

Extracted merchant names such as:

- Amazon
- Swiggy
- Zomato
- Uber
- Ola
- Blinkit
- Flipkart
- Starbucks
- BookMyShow
- Zerodha
- BMTC
- BESCOM
- and many more.

---

## ✅ Feature 3 – Expense Categorization

Transactions were classified into categories including:

- 🍔 Food Delivery
- 🛒 E-Commerce
- 🚖 Transport
- ⚡ Utilities
- ⛽ Fuel
- ☕ Cafe
- 🏠 Housing
- 🎬 Entertainment
- 🥬 Groceries
- 💸 Personal Transfer
- 📈 Investment
- 🍽 Restaurant

---

## ✅ Feature 4 – Spending Overview

Calculated:

- Total Income
- Total Expenses
- Net Savings
- Savings Rate
- Top Spending Vendors

---

## ✅ Feature 5 – Monthly Trend Analysis

Analyzed:

- Monthly Income
- Monthly Expenses
- Monthly Savings
- Highest Spending Month

---

## ✅ Feature 6 – Time Analysis

Analyzed transactions by:

- Morning
- Afternoon
- Evening
- Night

Identified the highest spending time period.

---

## ✅ Feature 7 – Anomaly Detection

Detected unusually large expense transactions (greater than ₹20,000) for financial review.

---

## ✅ Feature 8 – Spending Archetypes

Generated spending personality based on expense distribution.

Example:

🛍️ **Shopaholic**

---

# 📂 Dataset Information

The dataset contains bank transaction records from **January 2024 to June 2024**.

Each transaction includes:

| Column | Description |
|---------|-------------|
| Date | Transaction Date |
| Time | Transaction Time |
| Description | Bank Description |
| Type | Debit / Credit |
| Amount | Transaction Amount |
| Balance | Account Balance |
| Mode | Payment Mode |
| Ref | Reference Number |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

# 🔄 Project Workflow

```text
Raw Bank Statement
        │
        ▼
Data Cleaning
        │
        ▼
Vendor Extraction
        │
        ▼
Expense Categorization
        │
        ▼
Monthly Analysis
        │
        ▼
Time Analysis
        │
        ▼
Anomaly Detection
        │
        ▼
Spending Archetypes
        │
        ▼
Business Insights
```

---

# 📊 Key Insights

From the analysis:

- 💰 Monthly salary remains approximately **₹85,000**.
- 🛒 E-Commerce contributes the largest share of spending.
- 📅 June recorded the highest monthly expenditure.
- ☀️ Afternoon is the highest spending period.
- 🛍 Amazon is the top spending vendor.
- 🚨 Only two high-value expense transactions exceeded ₹20,000.
- 👤 Spending personality identified as **Shopaholic**.

---

# 📁 Project Structure

```text
SpendDNA-Financial-Transaction-Analysis/

│
├── SpendDNA.ipynb
├── bank_transactions.csv
├── README.md
└── requirements.txt
```

---

# 💻 Installation & Usage

Clone this repository

```bash
git clone https://github.com/mayuresh-khare/SpendDNA-Financial-Transaction-Analysis.git
```

Move into the project folder

```bash
cd SpendDNA-Financial-Transaction-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
SpendDNA.ipynb
```

Run all cells.

---

# 🚀 Future Improvements

- Interactive Dashboard using Streamlit
- Data Visualization using Matplotlib
- Automatic PDF Report Generation
- AI-powered Financial Assistant
- Spending Forecast using Machine Learning
- Budget Recommendation System

---

# 👨‍💻 Author

**Mayuresh Khare**

Computer Engineering (AI & DS)

Python | SQL | Data Analytics | AI

GitHub:
https://github.com/mayuresh-khare

---

## ⭐ Support

If you found this project helpful, consider giving this repository a ⭐ on GitHub.

It motivates me to build more projects and improve my skills.
