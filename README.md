This project involves performing structured data analysis on an ecommerce dataset titled “Amazon Sale Report” using DB Browser for SQLite.

The dataset was first imported into a SQLite database environment, where its structure and contents were examined. Basic data preparation was carried out, including converting text-based numeric fields such as Amount and Qty into usable numeric formats for analysis.

Following the provided guidelines, multiple SQL operations were performed:

1. Basic SQL Queries

Executed SELECT, WHERE, ORDER BY, and GROUP BY queries to explore the dataset, filter records, sort results, and compute summary statistics such as category-wise revenue and monthly sales trends.

2. Aggregate Functions

Used functions like SUM, AVG, and COUNT to calculate total revenue, average order values, top-performing SKUs, and city-level sales performance.

3. Subqueries

Implemented both correlated and non-correlated subqueries to identify SKUs performing above average and to retrieve the most recent status for each order.

4. Join Operations

To perform meaningful joins, the main table was normalized into additional tables (orders, order_items, and products).
INNER JOIN, LEFT JOIN, and a RIGHT JOIN equivalent were used to combine and analyze related data across these tables.

5. Views

Created a reusable analytical view summarizing order-level information, simplifying repeated reporting tasks.

6. Index Optimization

Indexes were added to frequently queried columns to improve query performance and efficiency.

Summary

Overall, this work demonstrates the complete SQL analysis workflow: importing data, preparing it, analyzing it using various SQL techniques, optimizing performance, and generating insights based on ecommerce sales data. The project successfully covers all required SQL components outlined in the task.
