# EcommerceSalesAnalysis

### Summary of the Two Notebooks

#### **1. `dump_csv_to_sql.ipynb` (Python & SQL)**
- Uses **Python (pandas, MySQL Connector)** to import multiple CSV files into a MySQL database.
- Reads and processes CSV files such as `customers.csv`, `orders.csv`, `sellers.csv`, etc.
- Establishes a **MySQL database connection** and dynamically determines SQL data types from pandas DataFrame.
- Automates **table creation and data insertion** for an **e-commerce dataset**.

#### **2. `SQLQueries.ipynb` (SQL)**
- Contains SQL queries categorized into **Basic, Intermediate, and Advanced** levels.
- **Basic Queries**: Counting orders, listing unique cities, and calculating total sales per category.
- **Intermediate Queries**: Orders per month, product-category revenue analysis, and seller ranking by revenue.
- **Advanced Queries**: Moving average of order values, cumulative sales per month, and customer retention rate analysis.

Together, these notebooks cover **data ingestion (Python + SQL) and analytical SQL queries for e-commerce data**.
