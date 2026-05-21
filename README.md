# SQL-Data-Cleaning-KPI-Trend-Analysis-Visualization
# Sales Data Analysis with SQL and Python

A beginner-friendly end-to-end data analysis project that demonstrates how to extract, clean, analyze, and visualize business data using **SQL, Python, Pandas, SQLite, and data visualization libraries**.

This project simulates a real-world sales dataset and walks through a complete analytics workflow, including **data cleaning, KPI generation, trend analysis, and visualization**.

---

## Project Overview

The project creates an in-memory SQL database containing messy sales data and performs a full data analysis process.

The workflow includes:

1. Creating a SQL database using SQLite
2. Extracting sales data with SQL queries
3. Cleaning missing and inconsistent data
4. Generating business KPIs
5. Identifying monthly sales trends
6. Visualizing insights using charts

This project demonstrates practical skills commonly used in:

- Data Analysis
- Business Analysis
- Entry-level Data Engineering

---

## Features

✅ SQL database creation with SQLite

✅ Data extraction using SQL queries

✅ Data cleaning and preprocessing

✅ Missing value handling using median imputation

✅ Text standardization and duplicate removal

✅ KPI generation:
- Revenue
- Profit
- Profit Margin
- Average Revenue

✅ Trend analysis by month

✅ Data visualization:
- Revenue trend line chart
- Profit by customer bar chart

---

## Technologies Used

- Python
- SQLite
- Pandas
- Matplotlib
- Seaborn

---

## Project Workflow

```text
Raw Data
    ↓
SQL Query
    ↓
Data Cleaning
    ↓
KPI Creation
    ↓
Trend Analysis
    ↓
Visualization
    ↓
Business Insights
```

---

## Data Cleaning Process

The project handles common real-world data quality issues:

- Missing values (`NaN`)
- Extra spaces in text
- Inconsistent capitalization
- Duplicate records
- Missing customer names

Cleaning techniques used:

```python
str.strip()
str.lower()
fillna()
dropna()
drop_duplicates()
```

---

## KPI Metrics

The following business KPIs are calculated:

### Total Revenue
Measures overall sales performance.

### Total Profit
Calculated as:

```text
Profit = Revenue - Cost
```

### Profit Margin

```text
Profit Margin = Profit / Revenue × 100
```

### Average Revenue
Measures average customer sales performance.

---

## Trend Analysis

Monthly revenue trends are analyzed to identify business performance changes over time.

Example insight:

> February generated the highest revenue performance, while March showed a decline, indicating possible seasonal variation or reduced sales activity.

---

## Visualizations

### Monthly Revenue Trend
A line chart used to identify revenue movement over time.

### Profit by Customer
A bar chart comparing profitability across customers.

---

## Example Business Insight

Example analytical findings from the project:

> Revenue increased from January to February, while profit contribution varied significantly by customer. High-profit customers may represent valuable target segments for future business strategies.

---

## Skills Demonstrated

This project showcases practical beginner-to-intermediate analytics skills:

- SQL querying
- Data cleaning
- Exploratory data analysis (EDA)
- KPI creation
- Trend analysis
- Data visualization
- Business insight generation
- Problem-solving with Python

---

## Future Improvements

Potential upgrades for this project:

- Connect to a real SQL database
- Add advanced SQL joins
- Create an interactive dashboard using Power BI
- Automate reporting pipeline
- Add forecasting and predictive analysis
- Export reports to Excel or PDF

---

## Learning Purpose

This project was built as part of a learning journey into:

**Data Analysis → Business Analytics → Data Engineering**

It serves as a foundation for more advanced analytics and data pipeline projects.
