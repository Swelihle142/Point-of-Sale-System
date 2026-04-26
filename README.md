Overview
This is a Point of Sale (POS) system built using Java (NetBeans IDE) with Swing GUI for the frontend and SQL database for backend data storage.
It is designed to manage sales transactions, products, inventory, and basic reporting in a retail environment.

Technologies Used
Java (JDK)
NetBeans IDE
Java Swing / SwingFX (GUI)
SQL Database (MySQL / SQLite depending on setup)
JDBC (Database connectivity

Features
User login system (admin/cashier roles)
Product management (Add, Update, Delete)
Sales transaction processing
Automatic total calculation
Receipt generation
Inventory tracking
Database integration using SQL
Simple and user-friendly GUI

Database Structure
Users (login credentials and roles)
Products (product details, price, stock)
Sales (transaction records)
Sale_Items (items per transaction)

Setup Instructions
Clone or download the project
Open the project in NetBeans IDE
Import the SQL database file into MySQL / database server

Configure database connection in:
DBConnection.java
