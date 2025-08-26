📊 Power BI Project:
Sales Analysis for Electro Hub

📌 Overview

This project is a Power BI Sales Dashboard designed for Electro Hub, a retail company with diverse product categories including Electronics, Footwear, Clothing, Home Appliances, Accessories, Kitchenware, Bags, and Personal Care.

The dashboard transforms raw transactional data into actionable insights by answering key business questions related to sales performance, profitability, discounts, and customer behavior.

It demonstrates my skills in data cleaning, modeling, DAX, and interactive dashboard design to support data-driven decision-making.

🎯 Business Questions Answered

🔝 What are the Top and Bottom 5 products by sales, profit, and quantity?

📈 How are sales trends performing daily, monthly, quarterly, and yearly?

💹 What is the relationship between sales and profit?

🔄 How do sales, profit, and quantity compare between two user-selected time periods?

🎁 What is the average discount offered across categories?

🛒 How many unique orders were placed?

🧭 How are sales distributed geographically (by city)?

📑 Can we explore detailed order-level sales data with interactive filters?

🛠 Dataset & Data Model
The data was sourced from an Excel workbook and structured into:

dim_customers → Customer details

dim_product → Product & pricing information

dim_promotion → Discounts and promotions

sheet_three (Fact Table) → Transactional sales data

**Data Transformations in Power Query:**

Merged fact & dimension tables

Created calculated columns: Total Sales, Discount Value, Net Sales, Profit (10% margin)

Added unique Order ID via index column

Replaced nulls and fixed data types

**Relationships:**

One-to-many relationships between fact table and dimension tables

Active & inactive relationships to support time-based comparisons

📊 **Dashboard Features**
Top/Bottom Products → Bar charts for quick product performance insights

Sales Trends → Line charts with drill-down (day → month → quarter → year)

Sales vs Profit → Scatter plot showing correlation between revenue & profitability

Period Comparison → Side-by-side charts for user-selected date ranges (DAX with USERELATIONSHIP)

Discount Analysis → Average discount by promotion category

Order Volume → KPI card showing unique orders

Detailed Order Data → Interactive table with slicers for customer, product, promotion, and date

Geographic Sales → Map visualization with city-level insights

⚙️ **Tools & Skills Used**
Power BI Desktop (data modeling, dashboard design)

Power Query Editor (data cleaning & transformations)

DAX (custom measures, CALCULATE, USERELATIONSHIP, TopN)

Data Visualization (interactive reports, drill-through, formatting)

🚀 **Business Impact**
This dashboard enables Electro Hub to:

Quickly identify high-performing and underperforming products

Monitor sales & profit trends across timeframes

Optimize discount strategies

Compare different business periods for better planning

Track regional sales performance for targeted campaigns

Empower stakeholders with self-service, drill-down analysis
 
