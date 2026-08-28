# 🚩 RedFlag — Fraud Detection & Analysis using SQL

> **An SQL-based data analytics project for identifying suspicious transaction patterns and potential financial fraud.**

## 📌 Project Overview

**RedFlag** is a data analytics project developed using **MySQL** to analyze financial transaction data and identify suspicious patterns that may indicate fraudulent activity.

The project focuses on using SQL not just for basic data retrieval, but for **real-world fraud detection, behavioral analysis, aggregation, and risk identification**.

The analysis covers **12 different fraud/suspicious transaction patterns** using advanced SQL techniques.

---

## 🎯 Objectives

* Identify suspicious transaction behavior.
* Detect high-risk financial transaction patterns.
* Analyze transaction frequency, amount, timing, and account behavior.
* Use SQL to extract actionable insights from transactional data.
* Apply advanced SQL concepts to a real-world analytical problem.
* Understand how data-driven rules can support fraud detection.

---

## 🛠️ Technologies Used

| Technology           | Purpose                                       |
| -------------------- | --------------------------------------------- |
| **MySQL**            | Database management and SQL analysis          |
| **SQL**              | Data querying and fraud-pattern detection     |
| **CTEs**             | Structuring complex queries                   |
| **JOINs**            | Combining related transaction/account data    |
| **Subqueries**       | Nested analytical conditions                  |
| **EXISTS**           | Checking suspicious related records           |
| **Window Functions** | Transaction sequence and behavioral analysis  |
| **LAG()**            | Detecting rapid/previous transaction behavior |
| **ROW_NUMBER()**     | Ranking and identifying transaction patterns  |
| **Aggregations**     | Summarizing transaction activity              |

---

## 🔎 Fraud Patterns Analyzed

The project investigates multiple suspicious behaviors, including:

1. **High-Value Transactions**
2. **Rapid Successive Transactions**
3. **Duplicate Transactions**
4. **Dormant Account Activity**
5. **Cross-Border Transactions**
6. **Unusual Transaction Behavior**
7. **Structuring / Smurfing**
8. **Repeated Suspicious Activity**
9. **Abnormal Transaction Frequency**
10. **Suspicious Account Behavior**
11. **Unusual Merchant/Transaction Patterns**
12. **Multiple Risk Indicators**

Each pattern is investigated using SQL-based rules and analytical queries.

---

## 🧠 SQL Concepts Demonstrated

This project demonstrates practical implementation of:

```sql
SELECT
WHERE
GROUP BY
HAVING
ORDER BY
CASE
JOIN
EXISTS
Subqueries
Common Table Expressions (CTEs)
Aggregate Functions
Window Functions
LAG()
ROW_NUMBER()
```

The queries were designed to transform raw transaction records into meaningful fraud-risk indicators.

---

## 📊 Project Workflow

```text
Raw Transaction Data
        ↓
Data Understanding
        ↓
SQL-Based Analysis
        ↓
Fraud Pattern Identification
        ↓
Risk Indicators
        ↓
Actionable Insights
```

---

## 💡 Key Insights

The analysis demonstrates how seemingly normal transactions can reveal suspicious behavior when analyzed collectively.

For example:

* A single high-value transaction may not necessarily indicate fraud.
* Multiple high-value transactions from the same account can become a stronger risk indicator.
* Rapid transactions within a short time period can indicate abnormal activity.
* Previously inactive accounts showing sudden activity can require additional investigation.
* Multiple transactions sharing suspicious characteristics can reveal structured fraud patterns.

This highlights the importance of **behavioral and contextual analysis rather than relying on a single transaction attribute**.

---

## 📁 Project Structure

```text
RedFlag/
│
├── RedFlag_Rishitha.sql
├── RedFlag_Project_Solution.pdf
├── RedFlag_Project_Brief.pdf
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Install MySQL

Use **MySQL Workbench** or any MySQL-compatible environment.

### 2. Create the database

```sql
CREATE DATABASE redflag;
USE redflag;
```

### 3. Import the transaction dataset

Load the provided transaction data into the appropriate table.

### 4. Execute the SQL script

Open:

```text
RedFlag_Rishitha.sql
```

Run the queries sequentially in MySQL Workbench.

### 5. Analyze the results

Each query corresponds to a different suspicious/fraudulent transaction pattern.

---

## 📈 What I Learned

Through this project, I strengthened my understanding of:

* Advanced SQL querying
* Data analysis using relational databases
* Fraud detection logic
* Transactional data analysis
* CTEs and window functions
* Analytical thinking and pattern recognition
* Converting real-world problems into SQL-based solutions

Most importantly, this project helped me understand how **SQL can be used as an analytical tool for solving real-world business and financial problems.**

---

## 🚀 Future Improvements

Possible future extensions include:

* Building a fraud-risk scoring system.
* Connecting the SQL database to **Power BI**.
* Creating interactive fraud-monitoring dashboards.
* Automating suspicious transaction alerts.
* Applying machine learning for fraud classification.
* Comparing rule-based detection with ML-based approaches.

---

## 👩‍💻 Author

**Rishitha Poornima S.**

CSE — Artificial Intelligence & Data Science

Interested in **Data Analytics, SQL, AI & Data Science**.

---

## ⭐ Project Highlights

**12 Fraud Patterns**
**Advanced SQL Analysis**
**MySQL Database**
**CTEs & Window Functions**
**Data-Driven Fraud Detection**

> **Turning transactional data into meaningful insights and identifying potential risks through SQL.**

---

## 📜 License

This project was created for educational and learning purposes.

