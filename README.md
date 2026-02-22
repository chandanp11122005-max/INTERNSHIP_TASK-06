# INTERNSHIP_TASK-06
Objective

To analyze sales data using SQL aggregation functions to calculate:

Monthly revenue

Yearly revenue

Order volume

Top revenue months

Best-performing products

Tools Used

SQLite

DB Browser for SQLite

Dataset

Database: sales_analysis_big.db
Table: online_sales

Columns:

order_id – Unique order identifier

order_date – Date of the order

product_id – Product identifier

amount – Revenue value

Total records: 600+

Analysis Performed

Grouped data by month and calculated total revenue and order count.

Grouped data by year to calculate yearly revenue and yearly order count.

Identified top 5 revenue-generating months.

Calculated average order value per month.

Identified top 10 products by total revenue.

Extracted monthly revenue trend using year-month format.

Identified the highest revenue-generating product overall.

SQL Concepts Used

SUM()

COUNT()

COUNT(DISTINCT)

AVG()

GROUP BY

ORDER BY

LIMIT

Date extraction using strftime()

Outcome

Successfully generated time-based revenue summaries and product-level performance analysis using SQL aggregation techniques.
