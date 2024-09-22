Question: A store wants to track its product sales. The store has a database with product sales data. They want to analyze the sales to find the total sales amount and number of sales for each product per year. Additionally, they want to determine the product with the highest total sales amount.
Tables:
1.
Products: Contains product information.
2.
Sales: Contains sales data.
Table Structures and Data:
1.
Products Table:
o
ProductID (int, Primary Key): Product ID
o
ProductName (nvarchar(100)): Product Name
o
Price (decimal(10, 2)): Product Price
2.
Sales Table:
o
SaleID (int, Primary Key): Sale ID
o
ProductID (int, Foreign Key): Product ID
o
Quantity (int): Quantity Sold
o
SaleDate (datetime): Sale Date
