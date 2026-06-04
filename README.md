# 🐼 Pandas Complete Handbook

> A Beginner-Friendly to Intermediate-Level Pandas Handbook with Real-World Business Analytics Examples

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-orange)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-brightgreen)

---

## 📖 Overview

This repository contains a comprehensive **Pandas Complete Handbook** designed to help learners master data analysis using Python and Pandas.

The handbook follows a practical learning approach using a real-world business dataset (`sales_dataset.csv`) and covers everything from basic DataFrame operations to advanced analytical techniques.

Whether you are:

* A student learning data analytics
* Preparing for data analyst interviews
* Building your first portfolio projects
* Transitioning into data science
* Strengthening your Pandas fundamentals

this handbook provides structured explanations, practical examples, and hands-on exercises.

---

## 🎯 Learning Outcomes

After completing this handbook, you will be able to:

✅ Load and inspect datasets efficiently

✅ Select, filter, and manipulate data

✅ Handle missing values and data cleaning tasks

✅ Perform advanced string operations

✅ Transform datasets using apply(), map(), and assign()

✅ Build aggregations using groupby()

✅ Create pivot tables and cross-tabulations

✅ Merge and join multiple datasets

✅ Analyze time-series data

✅ Apply rolling and window functions

✅ Rank, sort, and filter large datasets

✅ Perform statistical analysis

✅ Optimize Pandas performance and memory usage

---

## 📚 Topics Covered

### 1. Data Loading & Inspection

* read_csv()
* read_excel()
* head()
* tail()
* info()
* describe()
* shape
* dtypes
* memory_usage()

### 2. Indexing & Selection

* loc
* iloc
* at
* iat
* Column Selection
* MultiIndex Basics

### 3. Filtering & Boolean Operations

* Boolean Masks
* query()
* isin()
* between()
* str.contains()

### 4. Data Cleaning & Missing Values

* isnull()
* notnull()
* fillna()
* dropna()
* duplicated()
* drop_duplicates()
* Data Type Conversion

### 5. String Operations

* str.upper()
* str.lower()
* str.contains()
* str.extract()
* str.replace()
* Regular Expressions

### 6. Data Transformation

* apply()
* map()
* assign()
* cut()
* qcut()
* get_dummies()

### 7. Groupby & Aggregation

* Split-Apply-Combine
* agg()
* transform()
* filter()
* Named Aggregations

### 8. Pivot Tables & Crosstabs

* pivot_table()
* crosstab()
* stack()
* unstack()

### 9. Merging & Joining

* merge()
* join()
* concat()
* SQL-style Joins

### 10. Time Series Analysis

* to_datetime()
* dt Accessor
* resample()
* shift()
* diff()
* pct_change()

### 11. Rolling & Window Functions

* rolling()
* expanding()
* ewm()
* cumulative calculations

### 12. Sorting & Ranking

* sort_values()
* sort_index()
* rank()
* nlargest()
* nsmallest()

### 13. Statistical Analysis

* mean
* median
* standard deviation
* quantiles
* correlation
* covariance
* skewness
* value_counts()

### 14. Advanced Pandas

* pipe()
* method chaining
* melt()
* memory optimization
* export to CSV
* export to Excel
* export to JSON

---

## 💡 What Makes This Handbook Different?

Unlike many theoretical Pandas tutorials, this handbook focuses on:

### Real-World Business Dataset

You learn using a realistic sales analytics dataset containing:

* Orders
* Customers
* Products
* Revenue
* Profit
* Discounts
* Sales Channels
* Customer Ratings

### Interview-Oriented Questions

Each chapter includes:

* Practical Questions
* Detailed Solutions
* Business-Oriented Scenarios
* Analytical Thinking Exercises

### Portfolio-Friendly Examples

The examples simulate real tasks performed by:

* Data Analysts
* Business Analysts
* Reporting Analysts
* BI Developers
* Junior Data Scientists

---

## 🗂 Dataset Structure

The examples use a sales dataset containing fields such as:

| Category          | Examples                           |
| ----------------- | ---------------------------------- |
| Orders            | order_id, order_date               |
| Products          | product_id, product_name           |
| Customers         | customer_id, customer_name         |
| Sales             | quantity, unit_price               |
| Revenue           | revenue, profit, cogs              |
| Marketing         | discount_pct                       |
| Operations        | status, return_reason              |
| Customer Insights | rating                             |
| Geography         | region                             |
| Sales Channels    | Online, Direct, Reseller, In-Store |

---

## 📈 Skills Developed

By working through this handbook, you will develop skills in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Business Analytics
* KPI Analysis
* Revenue Analysis
* Customer Analytics
* Time-Series Analysis
* Data Transformation
* Data Wrangling
* Statistical Analysis

---

## 🛠 Prerequisites

Install the required packages:

```bash
pip install pandas numpy matplotlib
```

Optional:

```bash
pip install openpyxl
```

For Excel support.

---

## 🚀 Who Should Use This Handbook?

### Students

Build a strong foundation in data analytics.

### Aspiring Data Analysts

Practice industry-style analytical tasks.

### Business Analysts

Learn data manipulation and reporting workflows.

### Python Learners

Apply Python skills to real datasets.

### Interview Preparation

Review commonly used Pandas techniques and analytical patterns.

---

## 📁 Repository Structure

```text
Pandas-Complete-Handbook/
│
├── pandas_handbook.pdf
├── sales_dataset.csv
├── README.md
│
└── examples/
    ├── data_loading.py
    ├── filtering.py
    ├── groupby_examples.py
    ├── pivot_tables.py
    ├── time_series.py
    └── advanced_operations.py
```

---

## ⭐ Recommended Learning Path

Follow chapters in order:

1. Data Loading & Inspection
2. Indexing & Selection
3. Filtering & Boolean Operations
4. Data Cleaning
5. String Operations
6. Data Transformation
7. Groupby & Aggregation
8. Pivot Tables
9. Merging & Joining
10. Time Series Analysis
11. Window Functions
12. Sorting & Ranking
13. Statistics
14. Advanced Pandas

---

## 🎓 Ideal For Portfolio Building

This handbook can be used alongside:

* SQL Projects
* Data Analytics Projects
* Business Analysis Projects
* Power BI Dashboards
* Excel Analytics Projects
* Python EDA Projects

to create a complete analytics portfolio.

---

## 🤝 Contributing

Suggestions, improvements, and corrections are welcome.

Feel free to open an issue or submit a pull request.

---

## 📜 License

This project is intended for educational and learning purposes.

---

### If this handbook helped you learn Pandas, consider giving the repository a ⭐
