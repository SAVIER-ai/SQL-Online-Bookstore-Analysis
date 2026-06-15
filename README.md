# 📚 SQL Online Bookstore Analysis

## Overview

This project focuses on analyzing an online bookstore database using SQL. The objective is to extract meaningful business insights related to sales performance, customer purchasing behavior, inventory management, and revenue trends.

The project demonstrates practical SQL skills through real-world business questions and analytical queries ranging from basic data retrieval to advanced revenue analysis using subqueries and window functions.

---

## Technologies Used

* SQL
* MySQL

---

## Database Schema

The database consists of three tables:

### Books

Stores information about books available in the bookstore.

**Key Columns**

* Book_ID
* Title
* Author
* Genre
* Price
* Stock
* Published_Year

### Customers

Stores customer information.

**Key Columns**

* Customer_ID
* Name
* Email
* Phone
* City
* Country

### Orders

Stores order transactions.

**Key Columns**

* Order_ID
* Customer_ID
* Book_ID
* Quantity
* Total_Amount
* Order_Date

---

## SQL Concepts Demonstrated

### Basic SQL

* SELECT
* WHERE
* ORDER BY
* DISTINCT
* LIMIT

### Aggregations

* COUNT()
* SUM()
* AVG()
* GROUP BY
* HAVING

### Joins

* INNER JOIN
* LEFT JOIN

### Advanced SQL

* Subqueries
* Nested Queries
* Window Functions
* ROW_NUMBER()
* SUM() OVER()

---

# Key Analyses Performed

## Basic Analysis

1. Retrieve all books in a specific genre.
2. Find books published after a specific year.
3. List customers from a specific country.
4. Show orders placed during a specific month.
5. Calculate total stock available.
6. Identify the most expensive book.
7. Find customers ordering multiple quantities.
8. Retrieve high-value orders.
9. List all available genres.
10. Find books with the lowest stock.
11. Calculate total revenue generated.

---

## Intermediate Analysis

1. Calculate total books sold for each genre.
2. Find average book price by genre.
3. Identify customers with multiple orders.
4. Find the most frequently ordered books.
5. Retrieve the top-priced books within a genre.
6. Calculate total books sold by each author.
7. Identify cities with high-spending customers.
8. Find the customer with the highest spending.
9. Calculate remaining stock after fulfilling orders.

---

## Advanced Analysis

### Customer Spending Analysis

Identify customers whose total spending exceeds the average spending of all customers.

### Top-Selling Books by Genre

Rank books within each genre and retrieve the top-performing titles based on quantity sold.

### Multi-Genre Customer Analysis

Identify customers who purchased books from more than one genre.

### Cumulative Revenue Analysis

Calculate running revenue totals over time using SQL window functions.

### Unsold Inventory Analysis

Identify books that have never appeared in any order.

---

## Sample Business Questions Answered

* Which genres generate the most sales?
* Who are the highest-value customers?
* Which books sell the most copies?
* Which books have never been sold?
* How does cumulative revenue grow over time?
* Which customers purchase across multiple genres?
* How much inventory remains after sales?

---

## Skills Demonstrated

* Relational Database Analysis
* Data Cleaning and Exploration
* Business-Oriented SQL Queries
* Customer Behavior Analysis
* Sales Analysis
* Revenue Analysis
* Inventory Analysis
* Window Functions
* Subqueries and Nested Queries

---

## Learning Outcomes

Through this project, I strengthened my understanding of:

* SQL query writing
* Database relationships
* Data aggregation techniques
* Analytical problem solving
* Window functions and ranking
* Business reporting concepts
* Customer and sales analytics

---
## Project Screenshots

### Customers Spending Above Average

<img src="screenshots\spending_above_average.png" width="250">

### Top 3 Books by Genre

<img src="screenshots\Top_3_booksbygenre.png" width="250">

### Cumulative Revenue Analysis

<img src="screenshots\Cumulative_revenue_analysis.png" width="250">

### Unsold Books

<img src="screenshots\Books_never_ordered.png" width="250">
---

## Author

**Sai Verma**

Aspiring Data Analyst | Business Analyst

GitHub: https://github.com/SAVIER-ai

LinkedIn: https://www.linkedin.com/in/sai-verma7
