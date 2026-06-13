# Week 3 Assignment: SQL Analysis Using Subqueries, CTEs, and Window Functions

## Objective

The objective of this assignment is to analyze the Superstore dataset using advanced SQL concepts such as Subqueries, Common Table Expressions (CTEs), and Window Functions. The project focuses on customer sales analysis, ranking, and business insights generation.

## Dataset

* Dataset: Superstore Dataset
* Records: ~9995 rows
* Source: Kaggle Superstore Dataset

## Technologies Used

* MySQL 8.0
* Jupyter Notebook
* Python
* Pandas
* SQLAlchemy

## Tasks Performed

### Data Setup

* Imported the dataset into `superstore_raw`.
* Created the following tables using `SELECT DISTINCT`:

  * `customers`
  * `orders`
  * `products`

### SQL Analysis

* Identified orders with sales greater than average sales using Subqueries.
* Found the highest sales order for each customer.
* Calculated total sales per customer using CTEs.
* Identified customers with above-average sales.
* Ranked customers based on total sales using Window Functions.
* Assigned row numbers to orders within each customer using `ROW_NUMBER()`.
* Identified the top 3 customers based on total sales.

### Final Combined Analysis

* Combined JOINs, CTEs, and Window Functions to display:

  * Customer Name
  * Total Sales
  * Customer Rank

### Customer Sales Insights (Mini Project)

* Top 5 customers
* Bottom 5 customers
* Customers with only one order
* Customers with above-average sales
* Highest order value per customer

## Key Insights

* A small group of customers contributes a significant portion of total sales.
* Several customers placed only one order, indicating opportunities for customer retention.
* Above-average customers generate substantially higher revenue than average customers.
* Window Functions enabled efficient ranking and customer performance analysis.
* Combining JOINs, CTEs, and Window Functions provided deeper business insights.
