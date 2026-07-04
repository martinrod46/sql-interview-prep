# SQL Technical Interview Prep

A collection of SQL exercises designed to prepare for **Data Tester**, **Data Analyst**, and **Data Engineering** technical interviews using **DuckDB** and an insurance **star schema** dataset.

---

## 📖 Project Overview

The exercises simulate common SQL scenarios encountered in production environments, including:

- Data validation
- Business rule testing
- Referential integrity checks
- Analytical reporting

The dataset follows a dimensional model consisting of:

- `fact_claims`
- `dim_customers`
- `dim_policies`
- `dim_adjusters`

---

## 📁 Project Structure

```text
sql-interview-prep/
│
├── .gitignore
├── README.md
├── requirements.txt
├── sql_interview_prep.ipynb
│
└── data/
    ├── dim_customers.csv
    ├── dim_adjusters.csv
    ├── dim_policies.csv
    └── fact_claims.csv
```
---

## 🛠️ Skills Practiced

- Multi-table JOINs
- Window Functions
- Aggregations
- Data Validation
- Duplicate Detection
- Referential Integrity Checks
- Business Rule Validation
- Data Quality Testing
- Date Validation
- SQL Problem Solving

---

## 💻 Environment

- DuckDB
- SQL
- Git & GitHub

---


## 🎯 Purpose

This repository documents my hands-on preparation for SQL technical interviews by solving realistic insurance data scenarios that mirror the types of SQL challenges commonly encountered in Data Tester interviews.