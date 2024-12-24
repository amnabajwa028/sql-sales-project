# SQL Sales Management Project

## 📌 Project Overview
This project simulates a retail sales management system, tracking the sales of various wines and spirits across multiple locations. It includes SQL scripts for creating tables, inserting data, and querying essential business metrics like total revenue, gross profit, and inventory management.

## 🗂️ Project Structure
sql-sales-project/
├── create_tables.sql     # SQL script to create database tables
├── insert_data.sql       # Script to populate tables with sample data
├── queries.sql           # Contains analytical queries for sales insights
└── README.md             # Project documentation

## 📊 Key Features
- **Database Design**: Normalized schema with `Products`, `Sales`, and `Locations` tables.
- **Inventory Management**: Tracks initial and remaining inventory.
- **Revenue Calculation**: Computes total and average monthly revenue per location.
- **Gross Profit Analysis**: Calculates profit margins based on cost and retail price.
- **Dynamic Queries**: Adapts to retail price changes for profit projections.

## 🛠️ Technologies
- **Database**: Oracle SQL  
- **Tools**: ERD Design Tools (Used: Lucid Chart)  

## 🚀 How to Use
1. Clone the repository:
https://github.com/yourusername/sql-sales-project.git

2. Run the `create_tables.sql` script to set up the database.
3. Use the `insert_data.sql` script to populate the tables with data.
4. Execute `queries.sql` to calculate revenue, profit, and inventory metrics.

## 📝 Future Improvements
- Automate inventory updates after sales.
- Add stored procedures for automated reporting.
- Develop views for easier data visualization.

