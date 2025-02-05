# Coffee Shop Sales Analysis 📊

## Project Overview

This project focuses on analyzing coffee shop sales data using SQL for data cleaning, transformation, and insights generation. The cleaned and structured data was then visualized using Power BI, creating an interactive dashboard for business decision-making.

## Steps Followed in SQL 🛠️

1. **Data Walkthrough** – Understanding the dataset structure and identifying key columns.
2. **Raw Data File Preparation** – Ensuring the dataset is correctly formatted for import.
3. **Creating Database** – Setting up the MySQL database to store coffee shop sales data.
4. **Importing File** – Loading the dataset into MySQL for analysis.
5. **Cleaning Imported Data** – Handling missing values, duplicate entries, and incorrect formatting.
6. **Changing Data Types** – Modifying date, time, and numeric columns to the correct formats.
7. **Executing SQL Queries for Business Insights** – Extracting meaningful KPIs and trends.
8. **Storing Results** – Preparing the transformed data for visualization.
9. **Preparing SQL Documentation** – Recording all queries and steps taken for future reference.

## SQL Functionalities Used 📌

- **Data Cleaning & Formatting**: STR_TO_DATE, ALTER TABLE, CHANGE COLUMN, UPDATE TABLE
- **Aggregations & Calculations**: SUM, COUNT, AVG, ROUND, MAX, MIN
- **Date & Time Functions**: MONTH, DAY, DAYOFWEEK, HOUR
- **Data Retrieval & Filtering**: SELECT, WHERE, GROUP BY, ORDER BY, LIMIT, ALIAS
- **Advanced Queries**: WINDOW FUNCTIONS, LAG, JOINS, SUBQUERIES
- **Case Handling**: CASE

## SQL Queries Used 🔍

### 1️⃣ Data Cleaning & Formatting
- Converted `transaction_date` and `transaction_time` to proper formats.
- Changed incorrect column names and modified data types.

### 2️⃣ Key Business Metrics
- **Total Sales**
- **Total Quantity**
- **Month-over-Month (MoM) Growth**
- **Total Orders**
- **Sales by Day of the Week**
- **Sales by Product Category**
- **Sales Trend Over Time**

## 📊 Power BI Dashboard

After cleaning and analyzing the data with SQL, I used Power BI to create an interactive dashboard that includes:

- **Sales Trends Over Time** (Daily, Monthly, Hourly Analysis)
- **Product Category & Store Performance Insights**
- **Customer Purchase Behavior & Order Trends**

![DASHBOARD](https://github.com/Parshwa1504/Coffee-Shop-Sales-Analysis/blob/main/Coffee%20Sales%20Analysis%20Dashboard.png)

## 🔹 Key Achievements & Resume Points

- Designed and implemented a SQL-based ETL pipeline to clean, transform, and analyze a coffee shop sales dataset, leveraging advanced SQL queries, window functions, and aggregations to generate key business insights like total sales, order trends, and product performance.
- Developed an interactive Power BI dashboard to visualize key sales metrics, including total revenue, order trends, and quantity sold. Integrated time-based analysis like daily, hourly, and weekday trends, store-wise performance, and product category breakdowns to identify peak sales hours, best-performing items, and regional sales distribution for data-driven decision-making.
