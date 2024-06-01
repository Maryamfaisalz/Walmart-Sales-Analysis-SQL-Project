# Walmart-Sales-Analysis-SQL-Project

**Problem Statement:**


The primary objective is to analyze the sales data of a Walmart store to gain insights into various aspects such as sales performance, customer behavior, and product popularity. The aim is to use SQL queries to answer specific business questions that can help in strategic decision-making. The analysis includes understanding sales patterns by day and time, identifying best-selling products, evaluating customer types, and exploring the impact of different factors on sales and revenue.


**Approach:**


To solve these questions, a structured approach was adopted involving several key steps:


**_1) Data Wrangling_**

During this initial phase, the data is examined to detect any NULL or missing values, and strategies for data replacement are implemented to address and substitute these values effectively.

Build a database
Create a table and insert the data.
Select columns with null values in them. Null values are not present in our database because, in creating the tables, NOT NULL was specified for each field, effectively filtering out any null values.

_**2) Feature Engineering:**_


**Time of Day:** A new column time_of_day is added to categorize sales based on the time of day (Morning, Afternoon, Evening).


**Day Name:** A new column day_name is added to store the name of the day for each transaction.


**Month Name:** A new column month_name is added to store the name of the month for each transaction.

_**3) Exploratory Data Analysis (EDA)**_

Conducting exploratory data analysis is essential to address the project's listed questions and objectives.


_Generic Questions:_

Queries are formulated to answer general business questions such as the number of unique cities, the cities in which each branch operates, and the number of unique product lines.

_Product Analysis:_

Several queries are designed to analyze product-related data, including identifying the most common payment method, the best-selling product line, and total revenue by month.
Other queries focus on identifying the month with the largest Cost of Goods Sold (COGS), the product line with the largest revenue, and the city with the largest revenue.

_Sales Analysis:_

The focus shifts to analyzing sales data, including the number of sales made during different times of the day, the customer type bringing the most revenue, and the city with the highest VAT.
Additional queries explore which customer type pays the most in VAT and the number of unique customer types and payment methods.

_Customer Analysis:_

Queries are used to understand customer behavior, such as identifying the most common customer type, the customer type that buys the most, and the gender distribution of customers.
Further queries explore the time of day when customers give the most ratings, the day of the week with the best average ratings, and the day of the week with the best average ratings per branch.


**Questions:**


**Generic Questions**
1) How many distinct cities are present in the dataset?
2) In which city is each branch situated?

**Product Analysis**
1) How many distinct product lines are there in the dataset?
2) What is the most common payment method?
3) What is the most selling product line?
4) What is the total revenue by month?
5) Which month recorded the highest Cost of Goods Sold (COGS)?
6) Which product line generated the highest revenue?
7) Which city has the highest revenue?
8) Which product line incurred the highest VAT?
9) Retrieve each product line and add a column product_category, indicating 'Good' or 'Bad,' based on whether its sales are above the average.
10) Which branch sold more products than average product sold?
11) What is the most common product line by gender?
12) What is the average rating of each product line?

**Sales Analysis**
1) Number of sales made in each time of the day per weekday
2) Identify the customer type that generates the highest revenue.
3) Which city has the largest tax percent/ VAT (Value Added Tax)?
4) Which customer type pays the most VAT?

**Customer Analysis**
1) How many unique customer types does the data have?
2) How many unique payment methods does the data have?
3) Which is the most common customer type?
4) Which customer type buys the most?
5) What is the gender of most of the customers?
6) What is the gender distribution per branch?
7) Which time of the day do customers give most ratings?
8) Which time of the day do customers give most ratings per branch?
9) Which day of the week has the best avg ratings?
10) Which day of the week has the best average ratings per branch?

