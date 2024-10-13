# Pizza Sales Analysis Project
This project involves a comprehensive SQL analysis of a pizza sales dataset, designed to uncover insights into sales trends, customer behavior, and product performance. By leveraging various SQL queries, the project aims to provide actionable intelligence for business decision-making.

# ER Diagram
![image](https://github.com/Rasmiranjannayak96/Pizza_sales_SQL_Analysis/assets/166718223/27af6493-3709-45d7-b81d-49474f3be66b)


# Dataset Description
The dataset comprises four tables:

# Orders

order_id (Primary Key),
date,
time

# Order Details

order_details_id (Primary Key),
order_id (Foreign Key referencing Orders table),
pizza_id (Foreign Key referencing Pizzas table),
quantity

# Pizza Types

pizza_type_id (Primary Key),
name,
category,
ingredients

# Pizzas

pizza_id (Primary Key),
pizza_type_id (Foreign Key referencing Pizza Types table),
size,
price

# Objectives
# The primary objectives of this analysis are to:

Identify sales trends and patterns over different time periods.
Determine the most popular pizzas and ingredients.
Analyze the impact of pizza size and category on sales and revenue.
Explore customer ordering behavior and preferences.
Provide insights for optimizing product offerings and marketing strategies.

# SQL Queries

**Daily Sales Trend Analysis**: Identify daily sales trends over the past month and highlight any significant outliers.

**Revenue by Pizza Size and Category**: Determine which combination of pizza size and category yields the highest revenue.

**Order Interval Analysis**: Calculate the average time interval between orders and analyze its variation by day of the week.

**Seasonal Popularity**: Examine how seasonal variations affect the popularity of different pizza types.

**Sales Growth Rate**: Identify the top 5 pizza types with the highest sales growth rate over the past year.

**Order Value Comparison**: Compare the average order value between weekdays and weekends.

**Sales Distribution by Time of Day**: Analyze pizza sales distribution by time of day and its implications for staffing needs.

**Ingredient Impact on Sales**: Identify ingredients associated with the highest and lowest average sales and uncover patterns.

**Ingredient Complexity vs. Popularity**: Investigate the relationship between the number of ingredients in a pizza and its popularity.

**Vegetarian vs. Non-Vegetarian Sales**: Compare sales of vegetarian and non-vegetarian pizzas across different time periods.

**Promotional Impact on Peak Times**: Correlate peak order times with promotional events or discounts.

**New Product Introduction**: Analyze how the introduction of a new pizza type affects sales of existing pizza types.

**Customer Segmentation**: Identify the most profitable customer segments based on order size and frequency.

**Customer Retention**: Examine the retention rate of customers ordering specific pizza types and suggest improvement strategies.

**Price Sensitivity Analysis**: Explore how variations in pizza prices affect overall sales volume and revenue.

**Customer Feedback Correlation**: Analyze the impact of pizza size on average customer ratings or feedback (if available).

**Holiday Sales Patterns**: Compare sales distributions during holidays or special events with regular days.

**Repeat Order Analysis**: Identify pizza categories with the highest percentage of repeat orders and derive insights.

**Revenue Contribution Over Time**: Track how the revenue contribution of different pizza types changes over time.

**Common Order Combinations**: Identify the top 10 most common order combinations and their contribution to total sales.

![image](https://github.com/user-attachments/assets/b81982a0-eb80-4cce-a235-1db870a404f5)

