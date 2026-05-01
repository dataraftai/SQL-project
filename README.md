# SQL Portfolio – Data Analysis & Data Cleaning

This repository showcases SQL skills through two real-world projects focused on data analysis and data cleaning. The projects emphasize query writing, data transformation logic, and analytical thinking using structured datasets.

---

## 📌 Overview

# SQL Portfolio – Data Analysis & Data Cleaning

![Portfolio Overview](images/one_language_two_disciplines.png)

This repository showcases full-spectrum data handling capabilities using SQL...
The focus is on using SQL to extract insights, clean raw data, and prepare datasets for analysis.

---

## 🛠️ Tools Used

* SQL (MySQL)
* Relational database concepts
* CSV-based datasets
* Data exploration and transformation techniques

---

## 💡 Key SQL Skills Demonstrated

* JOIN operations across multiple datasets
* Window functions for running totals
* Aggregations (`SUM`, `MAX`, `COUNT`)
* Data cleaning using `CASE` and `COALESCE`
* String manipulation (`SUBSTRING`, `LOCATE`, `SUBSTRING_INDEX`)
* Duplicate detection using `ROW_NUMBER()`
* Schema refinement and column restructuring

---

# 📊 Project 1: COVID-19 Data Analysis

## 🎯 Objective

![Epidemiological Data Flow](images/navigating_global_data.png)

To analyze global COVID-19 trends including cases, deaths, and vaccination progress using SQL queries.

---

## 🧠 Approach

The analysis focuses on:

* Tracking total cases and deaths over time
* Calculating death percentages by country
* Comparing infection trends across regions
* Joining vaccination and case datasets
* Building rolling vaccination totals using window functions

---
## 📌 Architecture Diagram

```
+---------------------+        +-------------------+        +-------------------+
|   Raw COVID Data    | -----> |     SQL Queries   | -----> |   Analytical Insights|
| (WHO, Our World)     |        | Aggregation, JOINs |        | Death rates,      |
|                     |        | Window functions   |        | vaccination stats |
+---------------------+        +-------------------+        +-------------------+

```

**Explanation:**
This diagram represents the flow of data from raw COVID-19 datasets into structured SQL queries that generate key metrics such as infection trends, death rates, and vaccination progress.

---

## 🔍 Key SQL Concepts Used

* Aggregation by country and date
* JOIN between COVID and vaccination datasets
* Window functions for cumulative vaccination tracking
* Filtering and grouping by WHO regions

---

## 📈 Insight Type Produced

This project enables analysis of:

* Country-wise infection levels
* Death rate comparisons
* Vaccination progress over time

---

# 🏠 Project 2: Nashville Housing Data Cleaning

## 🎯 Objective

To clean and transform raw housing data into a structured, analysis-ready format using SQL.

---

## 🧠 Approach

The data cleaning process includes:

* Handling missing property addresses
* Splitting address fields into structured columns
* Standardizing categorical values (Y/N → Yes/No)
* Removing duplicate records
* Dropping unnecessary columns

---

## 📌 Data Cleaning Workflow Diagram

```
+--------------------------+        +--------------------------+        +----------------------+
|  Raw Housing Data        | -----> |  Data Cleaning Steps     | -----> |   Cleaned Housing    |
| (Missing addresses,      |        | (Handle missing data,    |        |   Data (No duplicates|
| unstructured addresses)  |        | split addresses,         |        |  structured columns) |
|                          |        | standardize fields)      |        |                      |
+--------------------------+        +--------------------------+        +----------------------+

```

**Explanation:**
This diagram shows the transformation pipeline applied to raw housing data, converting unstructured records into a clean relational format suitable for analysis.

---

## 🔍 Key SQL Concepts Used

* Self-joins for missing data imputation
* String parsing functions
* Conditional updates using `CASE`
* Duplicate detection using `ROW_NUMBER()`
* Table schema modification using `ALTER TABLE`

---

## 📊 Outcome

The dataset is transformed into a structured format with:

* Clean address fields
* Standardized categorical values
* Reduced duplicate records
* Improved analytical usability

---

## 📎 Important Notes

* This repository does not include raw datasets
* SQL scripts are designed to work with publicly available data sources
* Diagrams represent workflow logic and data transformation steps

---

## 🚀 What This Project Demonstrates

* Ability to design SQL-based data pipelines
* Strong understanding of data cleaning techniques
* Analytical thinking using relational databases
* Structuring raw data into usable formats

---

## 📬 Contact

Open to feedback, collaboration, and  Data Analyst opportunities.

