# Northwind Traders Sales Analytics

## Project Overview
An end-to-end data analytics project using the Northwind Traders specialty-food distribution dataset. The project explores sales performance, customer purchasing behavior, product inventory, employee information, shipping, and supplier analysis.

## Objectives
- Analyze sales revenue and order trends.
- Explore customer distribution and repeat purchasing.
- Evaluate product and category performance.
- Examine inventory levels and product pricing.
- Analyze employee and supplier information.
- Present business metrics through interactive visualizations.

## Tools and Technologies
- **Power BI:** Data modeling, DAX measures, and interactive reporting
- **Python:** Pandas, NumPy, Matplotlib, and Seaborn
- **SQL:** Data querying, joins, and aggregation

## Power BI Report Pages
1. Executive Overview
2. Customer Analysis
3. Product & Inventory
4. Employee Performance
5. Shipping & Supplier Analysis

## Dataset
The Northwind dataset contains eight related tables: Customers, Employees, Orders, Order Details, Products, Categories, Suppliers, and Shippers.

## Project Structure
- `Data/` — source data and SQL scripts
- `Python/` — data validation, cleaning, and EDA scripts
- `Outputs/` — analysis results and charts
- `Reports/` — project reports
- `powerbi/` — Power BI report

## How to Run
1. Install the required Python dependencies listed in `requirements.txt`.
2. Run `python Python/data_validation.py` to inspect data quality.
3. Run `python Python/data_cleaning.py` to prepare the analytical datasets.
4. Run `python Python/northwind_eda.py` to generate EDA results and charts.
5. Open the `.pbix` report in Power BI Desktop to explore the dashboard.

## Purpose
This project demonstrates practical data preparation, exploratory analysis, SQL querying, data modeling, and business intelligence reporting.
