\# 🛒 E-Commerce Sales \& Customer Analysis Dashboard



\## 📊 Project Overview



This project analyzes e-commerce sales and customer data using Microsoft Power BI.



The goal is to transform raw e-commerce data into an interactive dashboard that helps businesses understand their sales performance, profitability, customer behavior, and product performance.



\## 🎯 Objectives



\- Analyze overall sales and profit performance

\- Understand customer purchasing behavior

\- Identify top-performing products

\- Identify top customers

\- Compare sales and profit across categories

\- Analyze regional sales performance

\- Track sales trends over time

\- Understand customer segment contribution



\## 🛠️ Tools \& Technologies



\- Microsoft Power BI

\- Power Query

\- DAX

\- Data Cleaning \& Transformation

\- Data Visualization



\## 📌 Key KPIs



The dashboard includes:



\- 💰 Total Sales

\- 📈 Total Profit

\- 🛒 Total Orders

\- 👥 Total Customers

\- 📦 Total Quantity



\## 📊 Dashboard Visualizations



\### Sales Analysis

\- Sales by Category

\- Sales by Region

\- Monthly Sales Trend

\- Sales \& Profit by Category

\- Top 10 Products by Sales



\### Customer Analysis

\- Top 10 Customers by Sales

\- Sales by Customer Segment

\- Total Customer Count



\### Profit Analysis

\- Profit by Category

\- Profit by Region

\- Sales vs Profit Comparison



\## 🔄 Data Cleaning



The dataset was cleaned using Power Query.



Steps included:



\- Checked data quality

\- Checked for missing values

\- Verified data types

\- Removed duplicate rows

\- Checked for errors

\- Prepared the dataset for visualization



\## 📈 DAX Measures



Example measures used in the project:



```DAX

Total Sales = SUM('TableName'\[Sales])



Total Profit = SUM('TableName'\[Profit])



Total Orders = DISTINCTCOUNT('TableName'\[Order ID])



Total Customers = DISTINCTCOUNT('TableName'\[Customer ID])



Total Quantity = SUM('TableName'\[Quantity])

