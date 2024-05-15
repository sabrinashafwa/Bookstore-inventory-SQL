This project utilizes SQLite to manage a bookstore's inventory and analyze sales data. It employs SQL queries with various functions to gain valuable insights into the business.

Tools:

SQL (SQLite)
Functionality:

This project provides functionalities to:

- Identify Top 5 Highest Returns:

Leverages aggregate functions like SUM and GROUP BY to calculate the total returns for each product.
Utilizes ORDER BY to sort the results based on the return amount, presenting the top 5 products with the highest returns.
- Real-Time Stock by Product ID:

Employs a simple query to retrieve the current stock level for a specific product identified by its ID.
- Calculate Revenue from Transactions:

Uses aggregate functions like SUM on the transaction table to calculate the total revenue generated.
- Analyze Stock by Product Type:

Implements JOIN and GROUP BY clauses to combine product and inventory tables.
- Groups the results by product type, providing an overview of stock levels for each category.
Track Stock from Each Supplier:

Utilizes JOIN to connect product and supplier tables.
Performs grouping by supplier ID using GROUP BY to show the total stock originating from each supplier
