# End-to-End-E-commerce-analysis
A comprehensive data analysis project performing Exploratory Data Analysis (EDA) and SQL-based KPI computation on 50,000+ e-commerce transactions to uncover revenue trends, customer behavior patterns, and regional performance insights.

## Project Overview
This project simulates a real-world e-commerce analytics pipeline - from raw transaction data to actionable business insights. It covers data cleaning, feature engineering, advanced SQL queries and data visualizations using Python.

## Dataset
Source: Synthetically generated (realistic e-commerce transactions)
Size: 50,000 rows × 14 columns
Period: January 2023 – December 2024
File: ecommerce_data.csv
Columns: order_id, customer_id, order_date, category, product_name, region, payment_method, quantity, unit_price, discount_pct, revenue, order_status, rating, delivery_days

## Tech Stack
-  Python
-  Pandas
-  SQL
-  Seaborn
-  Matplotlib
-  Jupyter Notebook

## Key KPIs Computed (SQL)

Total Revenue & Average Order Value (AOV)
Month-over-Month (MoM) Revenue Growth Rate
Category-wise & Region-wise Performance
Customer Retention Rate (Repeat vs One-time buyers)
Top 10 Customers by Lifetime Value (LTV)
Return Rate & Cancellation Rate
Payment Method Preference


## EDA Visualizations

Monthly Revenue Trend (2023–2024)
Revenue by Category & Region
Order Status & Payment Method Distribution
Revenue Distribution & Boxplot by Category
Discount vs Revenue Scatter (colored by Rating)
Category × Region Revenue Heatmap
Day of Week & Quarterly Revenue Trends
Feature Correlation Heatmap
Customer Retention Pie Chart


## Key Insights

Electronics is the top-grossing category contributing the highest share of total revenue
Repeat buyer retention rate exceeds 60%, indicating strong customer loyalty
Weekend orders generate higher average revenue compared to weekdays
Discounts beyond 20% show diminishing returns on revenue
The North region leads in both order volume and total revenue
UPI and Credit Card are the most preferred payment methods


