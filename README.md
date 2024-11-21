# Retail Sales SQL Analysis Project

## Project Overview
This SQL project focuses on analyzing retail sales data, providing insights into sales performance, customer demographics, and transaction patterns.

## Database Schema
The `retail_sales` table contains the following columns:
- `transactions_id`: Unique identifier for each transaction
- `sale_date`: Date of the sale
- `sale_time`: Time of the sale
- `customer_id`: Unique identifier for each customer
- `gender`: Customer's gender
- `age`: Customer's age
- `category`: Product category
- `quantiy`: Quantity of items sold (Note: there's a typo in the column name)
- `price_per_unit`: Price per unit of the item
- `cogs`: Cost of Goods Sold
- `total_sale`: Total sale amount

## Data Cleaning
The project includes a comprehensive data cleaning process:
- Checks for NULL values in all columns
- Removes any rows with NULL values to ensure data integrity

## Key Analyses Performed

### Sales Overview
- Total number of sales
- Unique number of customers
- Unique product categories

### Detailed Analyses
1. Sales by Date
   - Retrieve sales for specific dates
   - Filter sales by category and quantity

2. Category Performance
- Total sales per category
- Number of orders per category
- Unique customers per category

3. Customer Insights
- Average age of customers by category
- Top 5 customers by total sales
- Gender distribution across categories

4. Temporal Analysis
- Average sales by month
- Identifying best-selling months
- Sales by time of day (Morning, Afternoon, Evening)

## Key SQL Techniques Demonstrated
- Data Cleaning
- Aggregation (SUM, AVG, COUNT)
- Window Functions (RANK())
- Conditional Grouping
- Date and Time Extraction
- Subqueries
- Case Statements

## How to Use
1. Create the `retail_sales` table using the provided schema
2. Import your sales data
3. Run the SQL queries in the script to perform various analyses

## Technologies Used
-  PostgreSQL
