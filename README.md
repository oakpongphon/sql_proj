# Project Overview: ETL/ELT Pipeline Development in Snowflake and Python

## Context & Objective:
The project involves the design and implementation of an ETL/ELT pipeline using Snowflake and Python, focusing on data transformation and analysis tasks.
The aim is to efficiently extract, load, and transform data from various sources and formats, including CSV, XML, PostgreSQL, and external data from the Snowflake Marketplace.

## Methodology:
### Snowflake Setup
* Created a Snowflake account and set up the necessary environment, including databases, schemas, and virtual warehouses.
* Utilized Python to establish a connection with Snowflake and perform database operations.
###Data Extraction and Loading:
* Automated data extraction from multiple sources: 41 CSV files for purchase order data, an XML file for supplier invoices, PostgreSQL for supplier information, and environmental data from Snowflake Marketplace.
* Implemented data loading techniques, focusing on Snowflake's COPY INTO command for efficiency and transforming data during the load process.
### Data Transformation and Analysis:
* Calculated and compared purchase order totals with supplier invoice amounts.
* Analyzed potential correlations between invoice discrepancies and weather conditions.
* Created materialized views and tables in Snowflake for efficient data retrieval and analysis.
### Python and SQL Integration:
* Utilized Python as the primary tool for executing SQL commands in Snowflake.
* Emphasized the use of SQL for data transformations within Snowflake, minimizing the use of Python for data processing to leverage Snowflake's performance.
### Specific Tasks:
* Extracted and transformed purchase order and supplier invoice data, focusing on data relevance and type conversion.
Joined and analyzed data sets to investigate invoice discrepancies and their potential relation to weather conditions.
Employed Python functions to automate and streamline the ETL/ELT processes, including data staging and transformations.

## Deliverables & Documentation:
Provided a comprehensive Python script encompassing all ETL/ELT tasks with detailed comments for clarity.
Included screenshots of any manual operations performed within the Snowflake GUI.
Ensured the deliverable captured the entire process, from initial setup in Snowflake to the final data analysis steps.
