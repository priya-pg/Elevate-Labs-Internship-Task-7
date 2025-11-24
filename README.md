# Elevate-Labs-Internship-Task-7

This task demonstrates the creation and analysis of a simple Sales database using SQLite, SQL queries, and Python for visualization.

## Database Structure

A single table named sales was created with the following fields:


Column	                                           and (Description)
- sale_id	                                           (Auto-increment primary key)
- product_id	                                       (Product identifier)
- product_name                                       (Name of Product)
- customer_id	                                       (Customer identifier)
- quantity_sold	                                     (Units sold in the transaction)
- unit_price	                                       (Price per unit)
- total_revenue	                                     (Automatically generated as quantity_sold * unit_price)
- sale_date	                                         (Date of sale)
- region	                                           (Sales region)


The total_revenue column is a computed field, meaning it is automatically calculated by the database.

## Sample Data

Multiple rows of realistic sales transactions were inserted into the table to allow aggregation and testing of SQL queries.

## Example SQL Queries

To analyze the dataset, the following types of queries were executed:

- Total revenue and quantity sold per product

- Sales performance by region

These queries help understand product performance and geographic demand.

## Data Visualization

- Python (with pandas and matplotlib) was used to:

- Connect to the SQLite database

- Execute SQL queries

- Convert results into a DataFrame

- Plot a bar chart showing revenue by product

- Axis labels were rotated and spaced for readability.

## Libraries Used

sqlite3


pandas


matplotlib
