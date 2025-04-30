# Azure Databricks Retail Analytics Project

This project demonstrates how to build a simple retail analytics pipeline using **Azure Databricks**, including data ingestion, transformation, and dashboard visualization.

## 📊 Objective

To analyze a sample retail product dataset by:
- Creating a SQL Warehouse
- Building a custom schema and table
- Ingesting CSV data
- Visualizing data in a dashboard
- Documenting all steps in a Databricks notebook

## 🧱 Technologies Used
- Microsoft Azure
- Azure Databricks (SQL and Notebooks)
- Delta Lake / DBFS
- GitHub (for version control)

## 📁 Dataset

The file `products.csv` contains sample product data with the following fields:
- `ProductID`
- `ProductName`
- `Category`
- `ListPrice`

This dataset was used to populate the `products` table in the `retail_db` schema.

## 🔧 Steps Performed

1. **Provisioned an Azure Databricks Workspace**
2. **Started a SQL Warehouse**
3. **Created a database**: `retail_db`
4. **Uploaded CSV and created a table**: `products`
5. **Built a dashboard** to visualize product categories with a bar chart
6. **Exported a notebook** with full SQL queries and comments
7. **Uploaded all files to GitHub** (notebook, CSV, screenshots)

## 📸 Screenshots

See the `/screenshots` folder for key steps such as:
- SQL Warehouse setup
- Table creation
- Dashboard visualization

## 📘 Notebook

The Jupyter notebook `Retail_Project.ipynb` contains:
- SQL queries
- Schema setup
- Dashboard query logic
- Comments for reproducibility

## ✅ Status

✅ Completed — Resources cleaned up, and project archived on GitHub.

## 📄 License

This project is for educational and demonstration purposes.
