# minor_project_3
# 🚩 RedFlag – SQL-Based Fraud Detection Engine

A SQL-based fraud detection project that identifies suspicious transaction patterns in a fintech payment system using analytical SQL queries. This project simulates the work of a Fraud Analyst by detecting multiple real-world fraud scenarios without using Machine Learning or Python. It was developed as part of **The Unlox Academy Industry-Graded Minor Project**. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

The objective of this project is to analyze approximately **200,000 financial transactions** and detect fraudulent activities using **pure SQL**.

Instead of predictive models, this project relies on SQL techniques such as:

- Filtering
- Aggregation
- GROUP BY
- HAVING
- CASE Statements
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions

The project demonstrates how SQL alone can be used to uncover fraud patterns in payment transactions. :contentReference[oaicite:1]{index=1}

---

## 🛠 Tech Stack

- MySQL 8.x
- SQL
- MySQL Workbench

---

## 📂 Repository Structure

```
RedFlag/
│
├── RedFlag(nandini).sql
├── README.md
└── screenshots/
    ├── query1.png
    ├── query2.png
    └── query3.png
```

---

## 🚨 Fraud Patterns Detected

This project detects the following fraud patterns:

| No | Fraud Pattern |
|----|---------------|
| 1 | Velocity Fraud |
| 2 | Round Amount Clustering |
| 3 | Card Testing |
| 4 | Failed Then Succeeded Transactions |
| 5 | Odd Hour Concentration |
| 6 | Mule Accounts |
| 7 | Refund Abuse |
| 8 | Merchant Collusion |
| 9 | Structuring (Just Under Threshold) |
| 10 | Dormant Then Active Accounts |
| 11 | Velocity Spike Detection |
| 12 | Geographic Impossibility |

These patterns represent common fraud scenarios encountered in digital payment systems. :contentReference[oaicite:2]{index=2}

---

## 📊 Dataset

- Approximately **200,000** transactions
- Six months of transaction history
- Around **14,700 users**
- **800 merchants**
- Transactions across **20+ Indian cities**

Dataset attributes include:

- Transaction ID
- User ID
- Merchant ID
- Amount
- Transaction Time
- Transaction Status
- Payment Mode
- City
- Transaction Type :contentReference[oaicite:3]{index=3}

---

## ✨ SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- CASE WHEN
- DATE()
- HOUR()
- DATE_FORMAT()
- TIMESTAMPDIFF()
- JOINS
- Subqueries
- EXISTS
- CTEs
- Window Functions (LAG, ROW_NUMBER)

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/RedFlag.git
```

2. Open MySQL Workbench.

3. Create or import the **redflag** database.

4. Execute:

```
RedFlag(nandini).sql
```

5. Run each fraud detection query to view suspicious transactions.

---

## 🎯 Project Objectives

- Detect fraudulent transaction behaviour using SQL.
- Identify suspicious users and merchants.
- Practice advanced SQL concepts on a realistic dataset.
- Build an industry-oriented SQL analytics project.

---

## 📸 Sample Output

Add screenshots of your best query results inside the **screenshots/** folder and display them here.

Example:

```
screenshots/
├── velocity_fraud.png
├── merchant_collusion.png
└── geographic_impossibility.png
```

---

## 📚 Learning Outcomes

Through this project I learned:

- Writing production-style SQL queries
- Fraud analytics using SQL
- Query optimization
- Window Functions
- Common Table Expressions
- Business data analysis
- Financial transaction analytics

---

## 👩‍💻 Author

**Sri Sai Nandini**

B.Tech – Artificial Intelligence & Data Science

GitHub: https://github.com/yourusername

---

## ⭐ If you found this project useful, please consider giving it a Star!
