# Data Warehouse and Analytics Project
This project demonstrates how I built an end-to-end data warehouse using SQL Server, from raw data ingestion to analytical reporting. It follows the Medallion Architecture approach (Bronze, Silver, Gold) to transform raw data into business-ready insights.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview
This project includes:

1. **Data Architecture**: Designed a modern data warehouse using Medallion Architecture (Bronze, Silver, Gold).
2. **ETL Pipelines**: Built SQL-based pipelines to ingest, clean, and transform data.
3. **Data Modeling**: Created fact and dimension tables using a star schema.
4. **Analytics & Reporting**: Developed SQL queries to generate business insights.


---
## 🛠️ Tools Used

- **SQL Server Express** – Data storage & processing  
- **SSMS** – Query execution & database management  
- **Power BI** – Data visualization (optional reporting)  
- **Draw.io** – Architecture & data flow diagrams  

---
## 📘 Project Documentation (Notion)

I documented the complete workflow of this project, including:
- Data Architecture Design  
- ETL Pipeline Implementation  
- Bronze, Silver, Gold Layer Development  
- Data Validation & Testing  

👉 [View full step-by-step project in Notion](https://www.notion.so/SQL-Data-Warehouse-Project-3425e7c8404880fd9502d2f997c9c1ee?source=copy_link)
---
### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

--



## 👨‍💻 Author
Nasrin Khatoon  
CSE Student | Data Engineering & Analytics Enthusiast  

Skills:
- SQL Server
- Data Warehousing
- ETL Pipelines
- Data Modeling
