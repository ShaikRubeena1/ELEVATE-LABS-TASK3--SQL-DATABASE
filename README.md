# ELEVATE-LABS-TASK3--SQL-DATABASE

Retail Sales Data Analysis (SQL Project)


Overview

This project focuses on analyzing a retail sales dataset using SQL. The dataset consists of multiple related tables including sales, customers, channels, and products. The goal is to generate insights about customer purchasing behavior, product performance across sales channels, and average transaction values.

Objective
The main objectives of this analysis include:

Identifying top-performing customers and products based on total revenue.

Analyzing customer purchase patterns such as average line totals and unit prices.

Evaluating channel-specific performance (e.g., "Wholesale", "Distributor").

Filtering key insights like high-value purchases or specific channel activity.

Key SQL Tasks

Total Revenue by Channel, Customer, and Product

Used JOINs across sales, customer, channel, and product tables.

Aggregated total revenue using SUM(LineTotal * OrderQuantity).

Ordered results by total revenue in descending order.

Top 10 Customers by Average Spend

Calculated average LineTotal and UnitPrice per customer.

Highlighted the most valuable customers by average spend.

Average Purchase Amount in Wholesale Channel

Focused on the "Wholesale" sales channel.

Aggregated average LineTotal by channel and product.

Top 5 High-Value Transactions in Distributor Channel

Filtered by ChannelName = 'Distributor' or LineTotal > 5000.

Returned top 5 transactions with the highest LineTotal.

Tools Used
SQL for querying and analyzing data.

DBMS: Any standard SQL-based environment (MySQL, PostgreSQL, SQL Server, etc.)


Dataset Structure
sales: Contains transactional details like LineTotal, OrderQuantity, UnitPrice, ProductIndex, and CustomerIndex.

customer: Holds customer data like CustomerName, CustomerIndex.

channel: Represents sales channels (ChannelName, ChannelIndex).

product: Includes product details such as ProductName, ProductIndex.

Insights Derived
Top customers and their purchasing power.

Best-performing products per channel.

Key channels generating high revenue.

Detection of high-value transactions.

How to Use
Load the dataset into your SQL environment.

Run each query step-by-step as outlined.

Modify filters (e.g., channel names or thresholds) to generate custom insights.
