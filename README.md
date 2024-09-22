Question: A store wants to track its product sales. The store has a database with product sales data. They want to analyze the sales to find the total sales amount and number of sales for each product per year. Additionally, they want to determine the product with the highest total sales amount.

Tables:
1. Products: Contains product information.
2. Sales: Contains sales data

Table Structures and Data:
1. Products Table:
  ProductID (int, Primary Key): Product ID
  ProductName (nvarchar(100)): Product Name
  Price (decimal(10, 2)): Product Price
2.Sales Table:
  SaleID (int, Primary Key): Sale ID
  ProductID (int, Foreign Key): Product ID
  Quantity (int): Quantity Sold
  SaleDate (datetime): Sale Date
