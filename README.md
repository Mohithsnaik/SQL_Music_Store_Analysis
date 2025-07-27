# Project Description: Pizza Sales Analysis Using SQL
## This project demonstrates a comprehensive analysis of pizza sales using SQL, leveraging real-world data to gain actionable insights into business performance. The analysis utilizes four interrelated tables and includes a variety of SQL queries ranging from basic to advanced levels. Key highlights of the analysis include:

Percentage Contribution of Each Pizza Type to Total Revenue

Analyzed the share of each pizza type in the overall revenue, providing insights into the most profitable products.
Top 3 Most Ordered Pizza Types by Revenue per Category

Identified the top-performing pizzas in each category (e.g., vegetarian, non-vegetarian) based on their revenue contribution.
Order Distribution by Hour of the Day

Examined the hourly order patterns to determine peak times for customer orders, aiding in workforce optimization and promotional strategies.
Cumulative Revenue Analysis Over Time

Tracked how revenue accumulates over a specified period, highlighting trends and seasonality in customer spending behavior.
Dataset Overview
The analysis is powered by four key tables:

Orders: Contains details of order_id, order_date, order_time.
Order Details: Holds details about order_details_id, order_id, pizza_id , quantity.
Pizzas: Holds details about pizza_id ,pizza_type_id ,size , price.
Pizza types: Holds details about pizza_type_id, name, category, ingredients.
Techniques and SQL Concepts
This project showcases the use of diverse SQL techniques and concepts, including:

Basic queries: Data extraction, filtering, and sorting.
Aggregations: SUM, COUNT, AVG, and GROUP BY to summarize data.
Window functions: RANK, ROW_NUMBER, and CUME_DIST for advanced insights.
Joins: Combining data across multiple tables for comprehensive analysis.
Subqueries and CTEs: Structuring complex queries for readability and efficiency.
Date and time functions: Analyzing trends based on timestamps.
Dynamic calculations: Metrics like percentage contributions and cumulative totals.
Outcome
The insights derived from this analysis are instrumental in identifying high-performing products, understanding customer behavior, and optimizing operational strategies. This project is a robust example of leveraging SQL for data-driven decision-making in the food and beverage industry.
