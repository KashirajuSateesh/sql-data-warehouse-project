# Data Warehouse and Analytics project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project. It highlights industry best practices in data engineering ana analytics.

---

## Project Requirements 🚀

### Building the Data Warehouse (Data Engineering)

#### Objective
Building a modern data warehouse with SQL server. including ETL process, data modeling and analysis

#### Specifications
- **Data Sources**: Import data from two soutce systems (ERO and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis
- **Integration**: Combine both sources intlo a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on latest dataset only
- **Documentation**: Provide clear documentation of the data miodel to support both business stakeholders and analytics teams.

#### Architecture
<img width="831" alt="Datawarehouse_Architecture" src="https://github.com/user-attachments/assets/08018d06-334e-4766-ae2c-13431ad689ec" />

- **Bronze Layer**: Stores raw data exactly as received from source systems like CRM and ERP, typically in CSV format. It performs no transformations and loads data using full batch processing.

- **Silver Layer**:  Holds cleaned and standardized data. It applies transformations such as data cleaning, standardization, normalization, and enrichment, making the data more consistent and ready for further processing.

- **Gold Layer**: Contains business-ready data used for reporting and analytics. It applies business logic, aggregations, and data integration, and organizes the data into structures like star schemas or flat tables for easy consumption by BI tools, SQL queries, and machine learning.

---

## 💥 About me 

Hi there! I am **Sateesh Kashiraju**. I am an IT professional experienced in Full-Stack development. I am here to learn different set of technologies and gain knowledge in various fields.


