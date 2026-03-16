# Monday-Coffee-Sales-Analysis-SQL-Project-

Project Overview

This project analyzes coffee sales data across multiple cities using MySQL. The objective is to understand customer behavior, product demand, market potential, and sales trends to support data-driven business decisions.
The analysis includes sales performance, customer segmentation, city-level market potential, and growth trends using advanced SQL queries.
The database consists of four main tables: City, Customers, Products, and Sales.
Relational modeling with primary and foreign keys ensures data integrity.
Database schema and queries are included in this repository.

Tools & Technologies

1. MySQL
2. SQL (Joins, CTEs, Window Functions)
3. Data Modeling (ERD)
4. Aggregation & Business Metrics

Business Problems Solved

The project answers several real-world business questions:

1️. Coffee Consumer Estimation
Estimated coffee consumers in each city assuming 25% of the population consumes coffee.

2️. Total Revenue Analysis
Calculated total revenue from coffee sales in Q4 2023 across cities.

3️. Product Demand Analysis
Identified number of units sold per coffee product.

4️. Average Sales per Customer
Measured average spending per customer in each city.

5️. Market Size vs Current Customers
Compared:
  Estimated coffee consumers
  Current unique customers

6️. Top Selling Products by City
Used window functions (DENSE_RANK) to identify top 3 products per city.

7️. Customer Segmentation
Identified unique coffee-buying customers per city.

8️. Sales vs Rent Analysis
Compared average sales per customer with average rent per customer.

9️. Monthly Sales Growth
Calculated month-over-month sales growth using LAG() window function.

10. Market Potential Analysis
Identified top cities for business expansion based on:
Total revenue
Rent
Customer count
Estimated coffee consumers

The SQL queries used to perform these analyses are included in the repository.

# Key Insights
1. Pune generated the highest revenue with relatively low rent per customer.
2. Delhi showed the largest estimated coffee consumer base.
3. Jaipur had a high number of customers with low rent per customer.
