# Walmart-Sales-Analysis-SQL-Project

**Problem Statement:**


The primary objective is to analyze the sales data of a Walmart store to gain insights into various aspects such as sales performance, customer behavior, and product popularity. The aim is to use SQL queries to answer specific business questions that can help in strategic decision-making. The analysis includes understanding sales patterns by day and time, identifying best-selling products, evaluating customer types, and exploring the impact of different factors on sales and revenue.

**Approach:**


To solve these questions, a structured approach was adopted involving several key steps:

**Database and Table Creation:**


A database named walmartSales is created if it doesn't exist.
A table named sales is created to store sales data with various attributes such as invoice_id, branch, city, customer_type, gender, product_line, unit_price, quantity, tax_pct, total, date, time, payment, cogs, gross_margin_pct, gross_income, and rating.

**Feature Engineering:**


**Time of Day:** A new column time_of_day is added to categorize sales based on the time of day (Morning, Afternoon, Evening).
**Day Name:** A new column day_name is added to store the name of the day for each transaction.
**Month Name:** A new column month_name is added to store the name of the month for each transaction.

**Generic Questions:**

Queries are formulated to answer general business questions such as the number of unique cities, the cities in which each branch operates, and the number of unique product lines.

**Product Analysis:**


Several queries are designed to analyze product-related data, including identifying the most common payment method, the best-selling product line, and total revenue by month.
Other queries focus on identifying the month with the largest Cost of Goods Sold (COGS), the product line with the largest revenue, and the city with the largest revenue.

**Sales Analysis:**


The focus shifts to analyzing sales data, including the number of sales made during different times of the day, the customer type bringing the most revenue, and the city with the highest VAT.
Additional queries explore which customer type pays the most in VAT and the number of unique customer types and payment methods.

**Customer Analysis:**

Queries are used to understand customer behavior, such as identifying the most common customer type, the customer type that buys the most, and the gender distribution of customers.
Further queries explore the time of day when customers give the most ratings, the day of the week with the best average ratings, and the day of the week with the best average ratings per branch.
