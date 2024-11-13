[Intro](./README.md) | [Getting Started](./Getting%20Started.md) | [Tasks](./Tasks.md) | [SQL Basics](./sqlbasics.md)

# Tasks to complete:     

#### Before you continue, be sure you have started the database ([Getting Started](./Getting%20Started.md))

#### For the next task please document your SQL on the [createDB.sql](./createDB.sql) document
1. Creating Databases and Tables
   - Task 1: Create a new database called RelationalTest
   - Task 2: Create the following tables
      - Customers
           - ID
           - FirstName
           - Surname
      - Orders
           - ID
           - OrderDate
           - ProductID
           - CustomerID
           - Quantity
           - OrderValue
      - Products
           - ID
           - ProductName
           - Price
   - Task 3: Identify how you would link the above three tables together and set the primary and foreign keys appropriately
   - Extension: Create the databases and tables for the relational databases you normalised during the normalisation task

([SQL Basics](./sqlbasics.md))

#### For the following tasks please document your SQL on the [mywork.sql](./mywork.sql) document

3. Intro to SQL
   - Run the SQL script for the [Sales Database](./Resources/Sales_db_script%20(MySQL).sql) which can be found in the Resources directory
   - Using the Sales database write SQL for the following queries
      - Show all the details for all the customers
      - Count how many customers live in London
      - Insert yourself as a customer
      - Insert a new order for yourself
      - Update the salesman James Hook as he has now moved to Rome
      - Update the customer Jane Davis to be Jane Black as they have gotten married
      - Delete your order from the order table


4. SQL Queries 1
   - Run the SQL script for the  [Stock Database](./Resources/stock_script%20(MySQL).sql) which can be found in the Resources directory
   - Using the Stpck database write SQL for the following queries
      - Insert a new Supplier into your Database
      - Insert a new Customer
      - Insert a new camera product, supplied by the Supplier inserted above
      - Insert a new Laptop into ‘Products’
      - Insert a new Keyboard into ‘Products’
      - Insert yourself as a Customer
      - Insert a new Order for yourself for one of the new laptops
      - Display the Title, Forename and Surname of the customers in the database
      - Display the name and telephone number of the suppliers in the database
      - Display ALL the information held in the database about the customers
      - Display all the unique Titles of the customers in the database.  Each title should only be shown once in the results.
      - Display all the unique categories of products that we have in the database.  Each category should only be displayed once.
      - Display ALL details of all customers whose credit limit is £1000
      - Display the order number of all orders where more than one item has been ordered.
      - Display the product number and description of all products supplied by the Supplier with Supplier Number 2 ONLY
      - Display how many customers there are in the database
      - Display how many customers have the title ‘Mr’
      - Display how many products there are in the ‘Cameras’ category
      - Display the name and address details of all customers with a credit limit of £2000
      - There is a quality issue with a product.  The company needs to see how many orders there are for the product with Product Number 'AE424747’.  Write this query.
      - Following on from the last query, now display the details (e.g., order number, order date) of the orders for the product with Product Number 'AE424747’.  
      - Display all details of products where the quantity in stock is less than the re-order level
      - Find out how many products there are with a Product Number starting with ‘AF’
      - Display all details of all customers whose surname starts with the letter ‘W’
      - Display the Product Number, Description and Price of all FIREWALL products

5. Recap Activity
   - Using the Sales Database write the following SQL queries
      - (extension) Using a JOIN show all the order details for all customers
      - (extension) Using a JOIN, show all the order details for all customers
      - (extension) Sort the results of the previous query by order date, newest order first!
      - (extension) Using a JOIN, show all order details for all orders placed by Brad Davis
      - (extension) Add to the previous query so that it shows the name of the salesman
      - (extension) Using GROUP BY, display how many orders each salesman is responsible for
