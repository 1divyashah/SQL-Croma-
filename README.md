Description

In the world of e-commerce, product management is a critical aspect of any business. To keep track of inventory and sales, companies use databases to store information about their products. One common way of storing this information is through the use of SQL (Structured Query Language), a programming language designed for managing and manipulating relational databases.
In our case study from one of the stores of Croma-The Electronics Megastore, we have two tables: ‘Product Inventory’ and ‘Manufacturer’. The ‘Product Inventory’ table has four columns: ‘Product_Code’, ‘Product_Name’, ‘Product_Price’, and ‘Manufacturer_Code’. The ‘Manufacturers’ table, on the other hand, has two columns: ‘Manufacturer_Code’ and ‘Manufacturer_Name’. Both the tables are connected through the ‘Manufacturer_Name’ column, which serves as a foreign key in the ‘Product Inventory’ table and a primary key in the ‘Manufacturers’ table.
Let's take a closer look at the ‘Product Inventory’ table:

Description of Product Inventory Table:

• Product_Code:  A unique identifier assigned to each product in the inventory to differentiate it from other products.
• Product_Name: The name of the product that allows for easy identification and management of the inventory.
• Product_Price: The cost of the product in the inventory in Indian Rupees, which is an essential piece of information for tracking expenses and revenue.
• Manufacturer_Code: A unique identifier assigned to each external supplier or vendor that provides products for the inventory, allowing for efficient tracking of each supplier or vendor's products.

Description of Manufacturers Table:

• Manufacturer_Code: A unique identifier assigned to each external supplier or vendor to differentiate it from other suppliers or vendors.
• Manufacturer_Name: The name of each external supplier or vendor, which is an essential piece of information for managing relationships with them and tracking their products in the inventory.
