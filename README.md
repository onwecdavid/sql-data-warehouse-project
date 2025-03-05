# Data Warehouse & Analytics Project 🚀
A full **Data Warehouse & Analytics Project** 🏘
This repository showcases an **end-to-end data** warehousing and analytics solution, from building the data warehouse to extracting actionable insights. It is designed as a portfolio project and follows industry best practices in data engineering and analytics.

***

# 🏗️ Data Architecture
There are several types of ***Data Warehouse Architecture*** - (~~Inmon~~,~~Kimball~~,~~Data Vault~~,Medallion). In this project, Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](https://github.com/onwecdavid/sql-data-warehouse-project/blob/main/docs/sql_warehouse_data_architecture.png)

1. **Bronze Layer** - Stores raw data directly from source systems. Data is ingested from CSV files into a SQL Server database.  
2. **Silver Layer** - Cleans, standardizes, and normalizes data to ensure consistency and prepare it for analysis.  
3. **Gold Layer** - Contains business-ready, structured data model into a star schema for reporting and analytics.  

