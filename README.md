# SQL-Business-Data-Anlysis-Project
A SQL data analysis Project using SQLite to answer 15 business questions and generate insight from trnsactional data.

## Project Overview

This project demonstrates the application of SQL to solve business problems and extract meaningful information from a relational database.

Using SQLite and the business database, I worked on a series of SQL business questions covering customer behavior, product performance, employee productivity, supplier analysis, order management, and sales revenue.

The project focuses on using SQL queries to retrieve, filter, join, aggregate, and analyze data to answer practical business questions and support data-driven decision-making.

## Project Objectives

The primary objectives of this project are to:

- Retrieve relevant information from relational database tables.
- Analyze customer purchasing behavior and order patterns.
- Evaluate product performance and sales quantities.
- Investigate supplier contributions to product sales.
- Measure employee order-handling performance.
- Examine shipping operations and delivery timelines.
- Calculate revenue and other business metrics.
- Identify customers and products without transaction records.
- Translate business questions into SQL queries.
- Develop practical SQL problem-solving skills.

## Tools and Technologies

- **Database:** SQLite
- **Database Management Tool:** DB Browser for SQLite
- **Query Language:** SQL
- **Documentation and Version Control:** GitHub

## Database Overview

The analysis uses a relational database containing business entities and transaction records.

The tables referenced in the project include:

| Table | Description |
|---|---|
| Customers | Customer information and locations |
| Orders | Customer orders and order-related information |
| OrderDetails | Products, quantities, and transaction-level details |
| Products | Product names, prices, and supplier relationships |
| Categories | Product category information |
| Suppliers | Supplier information |
| Employees | Employee information and order responsibilities |
| Shippers | Shipping company information |

These tables provide the data needed to investigate relationships between customers, orders, products, suppliers, employees, and shipping companies.

## Business Questions and Analysis Scope

The project covers 30 SQL questions organized into three sections.

### Section A: Basic SQL Queries

This section focuses on retrieving records, filtering information, and selecting specific columns.

1. Retrieve all customers and their countries.
2. Identify products with a unit price greater than 40.
3. List employees located in London.
4. Retrieve shippers and their phone numbers.
5. Retrieve orders placed in 1997.
6. Identify suppliers located in the USA.
7. Retrieve discontinued products.
8. Identify employees born before 1980.

**Business purpose:**

These queries demonstrate how SQL can retrieve relevant business information using column selection, filtering conditions, and date-based criteria.

### Section B: Joins and Aggregate Analysis

This section explores relationships between database tables and summarizes business activity.

9. Display orders alongside their corresponding customer company names.
10. Retrieve products alongside their category names.
11. List suppliers and the products they supply.
12. Calculate the total number of orders placed by each customer.
13. Calculate the total quantity ordered for each product.
14. Calculate the average unit price of products in each category.
15. Calculate the number of orders handled by each employee.
16. Calculate the number of orders delivered by each shipper.
17. Display orders alongside the full names of the employees who handled them.
18. Calculate total revenue generated from all orders.
19. Count the products supplied by each supplier.
20. Identify customers who have placed more than five orders.

**Business purpose:**

These queries demonstrate how related tables can be combined to investigate customer activity, product performance, employee productivity, supplier relationships, and revenue.

### Section C: Advanced Business Analysis

This section focuses on transaction analysis, business performance, and identifying important operational patterns.

21. Identify customers who have no matching records in the Orders table.

22. Identify products that have never appeared in an order transaction.

23. Determine the customer with the highest cumulative purchase value across all orders, considering quantity and unit price.

24. Identify the product with the highest total quantity sold across all orders, including repeated purchases.

25. Identify orders where the difference between the order date and shipping date exceeds seven days.

26. Determine the product category generating the highest total sales revenue.

27. Rank employees by the number of orders processed and return the top three.

28. Identify the supplier whose products generate the highest total sales revenue.

29. Retrieve the five products with the highest unit prices.

30. Calculate the average freight cost for each shipping company.

**Business purpose:**

These queries investigate purchasing behavior, product demand, sales performance, shipping efficiency, supplier contribution, and employee performance.

## SQL Skills Demonstrated

The questions provide opportunities to apply the following SQL concepts:

### Data Retrieval and Filtering
- SELECT statements
- WHERE conditions
- Column selection
- Filtering by price, location, status, and date

### Table Relationships
- INNER JOIN
- LEFT JOIN
- Table aliases
- Joining related business tables

### Data Aggregation
- COUNT()
- SUM()
- AVG()
- GROUP BY
- HAVING

### Sorting and Ranking
- ORDER BY
- DESC and ASC
- LIMIT
- Ranking employees by order count

### Business Logic and Transaction Analysis
- Identifying unmatched records using NULL checks
- Calculating sales revenue from quantities and unit prices and discount.
- Aggregating repeated product purchases
- Comparing order and shipping dates
- Summarizing freight costs
- Identifying top-performing customers, products, suppliers, and employees


## Analytical Approach

The project follows a structured approach to SQL-based business analysis:

1. **Understand the business question:** Identify the information required and the business objective behind each question.

2. **Explore the database:** Examine the relevant tables, columns, and relationships.

3. **Select the appropriate SQL technique:** Determine whether the question requires filtering, joining, aggregation, sorting, or a combination of techniques.

4. **Write the SQL query:** Translate the business requirement into a query that retrieves or calculates the required information.

5. **Execute and validate:** Run the query and examine the returned records to assess whether the results answer the question correctly.

6. **Interpret the results:** Explain the business meaning of the results and identify potential actions where appropriate.

7. **Document the work:** Organize the questions, SQL queries, and verified findings for future reference.

## Business Value of the Analysis

The questions address several areas of business decision-making.

| Business Area | Potential Value |
|---|---|
| Customer Analysis | Understand customer activity and purchasing patterns. |
| Product Analysis | Identify popular, expensive, and unsold products. |
| Sales Analysis | Measure revenue and compare product performance. |
| Supplier Analysis | Evaluate supplier contributions to product sales. |
| Employee Performance | Compare order-handling activity across employees. |
| Shipping Analysis | Examine shipping delays and freight costs. |
| Inventory Insights | Identify products that have not appeared in order transactions. 


## Key Findings

- The customer with the highest cumulative purchase value. ![The customer with the highest cumulative purchase value](screenshots/Hihgest customer by cumulitve purchase)
- The product with the highest total quantity sold.
- The category generating the highest sales revenue.
- The supplier contributing the highest sales revenue.
- The three employees handling the most orders.
- The orders with shipping delays exceeding seven days.
- The customers without order records.
- The products that have never appeared in an order transaction.


### File Descriptions

- `README.md` — Project overview, business questions, analytical scope, and findings.
- `sql/business_questions.sql` — SQL queries used to answer the business questions.
- `screenshots/` — Selected screenshots showing queries and their results.
- `dataset/` — Database file.

## Conclusion

This project applies SQL to practical business questions involving customers, products, orders, suppliers, employees, and shipping operations.

It demonstrates a structured approach to querying relational databases, combining related tables, summarizing transaction data, and investigating business performance.

By connecting SQL techniques with real business questions, the project supports the development of practical data analysis skills and provides a foundation for more advanced analytical work.

## Author

**David Cosmas**

Data Analyst | SQL | Excel | Power BI

GitHub: https://github.com/Kingdav0002-UI
