# Inventory-Management-
 # Introduction
The Inventory Management System is a crucial tool for managing stock and keeping track of products in a business. In this system, we transition from using file handling to utilizing JSON and dictionaries for data storage. This change allows us to store data in a structured way, making it easier to retrieve and manage product information.
  
  
 ## Billing System Implementation 

This module extends the inventory management system by adding a billing feature. It performs the following tasks:
   .Displays available products in a menu format.
   .Accepts user input (Product ID & Quantity).
   .Calculates and prints the total bill for the selected item.

# Inventory Data File

 This project includes a text/CSV file that stores product details for the Inventory Management System.
    Each entry contains:
  . Product ID (unique identifier)
  . Product Name (item description)
  . Price per unit
  . Quantity available in stock

The file acts as the database for the system. When a user makes a purchase, the program reads from this file, updates the stock, and generates a bill.
