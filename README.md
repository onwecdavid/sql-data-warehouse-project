# Data Warehouse & Analytics Project 🚀
A full **Data Warehouse & Analytics Project** 🏘
This repository showcases an **end-to-end data** warehousing and analytics solution, from building the data warehouse to extracting actionable insights. It is designed as a portfolio project and follows industry best practices in data engineering and analytics.

***

## 🏗️ Data Architecture
There are several types of ***Data Warehouse Architecture*** - (~~```Inmon```~~,~~```Kimball```~~,~~```Data Vault```~~,```Medallion```). In this project, ```Medallion``` Architecture **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](https://github.com/onwecdavid/sql-data-warehouse-project/blob/main/docs/data_architecture.png?raw=true)

1. **Bronze Layer** - Stores raw data directly from source systems. Data is ingested from CSV files into a SQL Server database.  
2. **Silver Layer** - Cleans, standardizes, and normalizes data to ensure consistency and prepare it for analysis.  
3. **Gold Layer** - Contains business-ready, structured data model into a star schema for reporting and analytics.  

## 📰 Project Overview  

This project covers:  

1. **Data Architecture** – Designing a modern data warehouse using the Medallion Architecture (Bronze, Silver, and Gold layers).  
2. **ETL Pipelines** – Extracting, transforming, and loading data from source systems into the warehouse.  
3. **Data Modeling** – Developing fact and dimension tables optimized for analytical queries.  
4. **Analytics & Reporting** – Creating SQL-based reports and dashboards for actionable insights.  

### 🎯 Who Is This For?  

This repository is a great resource for professionals and students looking to showcase expertise in:  

- **SQL Development**  
- **Data Architecture**  
- **Data Engineering**  
- **ETL Pipeline Development**  
- **Data Modeling**  
- **Data Analytics**

***

## Important Links & Tools:

- **[Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
- **[Git Repository](https://github.com/):** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.
- **[Notion](https://www.notion.com/):** All-in-one tool for project management and organization.
- **[Notion Project Steps](https://goofy-sale-e49.notion.site/Data-Warehouse-Project-1a16f060f9e08044a1cec3c3f2b97882):** Access to All Project Phases and Tasks.

***

## 🚀 Project Requirements  

### Building the Data Warehouse (Data Engineering)  

#### 🎯 Objective  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.  

#### 📌 Specifications  
- **Data Sources** – Import data from two source systems (ERP and CRM) provided as CSV files.  
- **Data Quality** – Clean and resolve data quality issues before analysis.  
- **Integration** – Merge both sources into a single, user-friendly data model optimized for analytical queries.  
- **Scope** – Focus on the latest dataset only; historization is not required.  
- **Documentation** – Provide clear documentation to support business stakeholders and analytics teams.  

***

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

For more details, refer to [docs/requirements.md](docs/requirements.md).

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── ETL.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You can use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **David Onwe**, also known as **Kalinytics**. Bridging Data Insights with Business Strategy and technical Speciality, I transform complex data into clear, actionable intelligence to drive informed decisions. Specialize in data analysis and visualization, and translation of insights into business value. Let us unlock your data to help you achieve your strategic objectives.

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davidonwe/)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://davidonwe.netlify.app/)
[![Medium](https://img.shields.io/badge/Newsletter-FF5722?style=for-the-badge&logo=substack&logoColor=white)](https://medium.com/@onwecdavid)
