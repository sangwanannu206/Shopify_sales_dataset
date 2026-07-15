# Shopify_sales_dataset
SQL and Excel dashboard project analyzing Shopify sales data to generate business insights through KPIs, interactive visualizations, and data-driven reporting. 
📊 Shopify Sales Analytics Dashboard | SQL + Microsoft Excel

An end-to-end Data Analytics project that transforms raw Shopify sales data into actionable business insights using SQL for data analysis and Microsoft Excel for interactive dashboard creation.

📌 Project Overview

This project demonstrates a complete Data Analytics workflow, from querying raw transactional data using SQL to designing an interactive Microsoft Excel Dashboard for business reporting.

The project analyzes Shopify sales performance across multiple business dimensions, including revenue, profit, customer behavior, product performance, payment methods, traffic sources, discounts, and geographical sales distribution.

It is designed to showcase the practical skills expected from an aspiring Data Analyst, including SQL querying, business analysis, KPI reporting, dashboard development, and insight generation.

🎯 Project Objectives
Analyze overall sales performance.
Measure key business KPIs.
Identify top-performing products and customers.
Understand customer purchasing behavior.
Track monthly revenue and profit trends.
Evaluate marketing channels and payment methods.
Generate actionable business recommendations.

🛠️ Tech Stack
Tool	Purpose
PostgreSQL	Data Storage & Analysis
SQL	Data Cleaning & Business Analysis
Microsoft Excel	Dashboard Development
Pivot Tables	Data Summarization
Pivot Charts	Data Visualization
Slicers	Interactive Filtering

📂 Database Schema

The project uses a single sales table:

Table: ecommerce_sales

Columns
Order ID
Order Date
Customer ID
Product ID
Product Category
Product Price
Discount Percentage
Quantity
Customer Country
Traffic Source
Payment Method
Shipping Cost
Product Rating
Return Status
Discounted Price
Revenue
Profit
📊 Business KPIs

The dashboard includes the following Key Performance Indicators (KPIs):

💰 Total Revenue
📦 Total Orders
👥 Total Customers
📈 Total Profit
🛒 Average Order Value (AOV)
🎁 Average Discount
🔍 SQL Analysis Performed

This project contains more than 20 business-driven SQL queries covering descriptive analysis, aggregation, ranking, and window functions.

KPI Analysis
Total Revenue
Total Orders
Total Customers
Total Profit
Average Order Value (AOV)
Product Analysis
Revenue by Product Category
Profit by Product Category
Average Discount by Product Category
Product Category Ranking by Revenue
Product Ratings by Category
Customer Analysis
Top 10 Customers by Revenue
Top 5 Most Profitable Customers
Customer Distribution by Traffic Source
Marketing Analysis
Revenue by Traffic Source
AOV by Traffic Source
Payment Analysis
Orders by Payment Method
Average Profit per Order by Payment Method
Geographic Analysis
Revenue by Country
AOV by Country
Time Series Analysis
Monthly Revenue Trend
Monthly Profit Trend
Month-over-Month Revenue Growth using SQL Window Functions (LAG())
Advanced SQL Concepts Used
Common Table Expressions (CTEs)
Aggregate Functions
Window Functions
ROW_NUMBER()
LAG()
DATE_TRUNC()
EXTRACT()
GROUP BY
ORDER BY
COUNT(DISTINCT)
Ranking
Business KPI Calculations


📈 Excel Dashboard Features

The SQL output was used to build an interactive Excel dashboard featuring:

KPI Cards
Revenue Trend Analysis
Revenue by Traffic Source
Orders by Payment Method
Revenue by Country (Map)
Average Discount by Product Category
Top Customers Analysis
Product Category Revenue Ranking
Interactive Slicers for Filtering

💡 Key Business Insights
Social Media is the highest revenue-generating traffic source.
Revenue remained strong during the first half of the year before declining.
Australia contributes the highest overall revenue.
Electronics is the top-performing product category by revenue.
High-value repeat customers contribute significantly to total sales.
Heavy discounting may increase sales volume but reduce profit margins.

🚀 Business Recommendations
Increase investment in high-performing marketing channels, especially Social Media.
Investigate the decline in revenue after June and launch targeted campaigns during low-performing months.
Expand marketing efforts in underperforming countries to diversify revenue.
Optimize discount strategies to balance revenue growth and profitability.
Develop customer retention programs for high-value customers.
Focus inventory planning on top-performing product categories.

📁 Project Structure
Shopify-Sales-Analytics/
│
├── Dataset/
│   └── ecommerce_sales.csv
│
├── SQL/
│   └── shopify_sales_analysis.sql
│
├── Dashboard/
│   └── Shopify Sales Dashboard.xlsx
│
├── Images/
│   └── Dashboard Preview.png
│
└── README.md

📚 Skills Demonstrated
SQL Query Writing
Business Analysis
KPI Development
Data Aggregation
Window Functions
Data Visualization
Excel Dashboard Design
Interactive Reporting
Data Storytelling
Business Insight Generation

👨‍💻 Author

Annu Sangwan

B.Sc. Computer Science | Aspiring Data Analyst

Skills
SQL (PostgreSQL)
Microsoft Excel
Power BI (Learning)
Python (Learning)
Data Visualization
Business Analytics
