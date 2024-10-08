# Project 2: Complex ETL Pipelines with Delta Lake

## Overview
This project focuses on designing and implementing complex ETL (Extract, Transform, Load) pipelines using Delta Lake in Databricks. The goal is to efficiently process data from various sources, apply necessary transformations, and load the data into Delta Lake for optimized storage and querying.

## Objective
The primary objective of this project is to build an ETL pipeline that demonstrates the capabilities of Delta Lake, including ACID transactions, schema enforcement, and time travel. This will be accomplished by extracting data from multiple formats, transforming the data as required, and loading it into a Delta Lake table.

## Available Data Source
- **Sales Transactions Dataset**: The [Sales Transactions Dataset](https://www.kaggle.com/datasets/irfanasrullah/sales-transactions-dataset) will be used for this project, which includes various sales data in CSV format.

## Project Description
In this project, we will carry out the following tasks:

1. **Data Extraction**:
   - Load data from multiple formats (CSV, JSON) into Databricks.
   - Explore different data ingestion methods, such as file streaming and batch loading.

2. **Data Transformation**:
   - Clean and preprocess the data to handle missing values, incorrect data types, and duplicates.
   - Apply transformations to derive new metrics and enrich the dataset, such as calculating total sales per region, categorizing products, etc.

3. **Loading into Delta Lake**:
   - Create a Delta Lake table to store the transformed data.
   - Implement schema enforcement to ensure data integrity and quality during the load process.

4. **Utilizing Delta Lake Features**:
   - Leverage Delta Lake's ACID transactions to handle concurrent writes.
   - Explore time travel features to query historical versions of the data and demonstrate rollback capabilities.

5. **Optimization**:
   - Apply optimization techniques such as data compaction and Z-Ordering to improve query performance on the Delta Lake table.

## Expected Outcomes
- A complete Databricks notebook showcasing:
  - Successful data extraction from multiple formats.
  - Detailed transformation steps and intermediate datasets.
  - A well-structured Delta Lake table with effective data management features.
  - Performance improvements demonstrated through query optimizations.

## Reference Materials
- [Delta Lake Documentation](https://docs.delta.io/latest/index.html)
- [ETL Processes with Delta Lake](https://databricks.com/glossary/etl)
- [Building ETL Pipelines with Delta Lake](https://www.databricks.com/blog/2020/05/19/building-etl-pipelines-with-delta-lake.html)
- [Data Quality and Delta Lake](https://www.databricks.com/glossary/data-quality)

## Requirements
- **Databricks Account**: Ensure you have access to a Databricks workspace.
- **Libraries**: Ensure that necessary libraries (e.g., `pyspark`, `delta-spark`) are available in the Databricks environment.

## Running the Project
1. **Data Preparation**:
   - Download the Sales Transactions Dataset and upload it to Databricks.
   - Create the necessary folders and structure in the Databricks File System (DBFS) for organization.

2. **Databricks Notebook Execution**:
   - Open the Databricks notebook created for this project.
   - Execute the cells in order to load the data, apply transformations, and create the Delta Lake table.

3. **Querying and Optimization**:
   - Perform sample queries on the Delta Lake table to validate data integrity and performance.
   - Implement optimization techniques and measure improvements.

## Contributions
Contributions to enhance this project are welcome! Please feel free to:
- Open issues for any bugs or feature requests.
- Submit pull requests with enhancements or additional features.
- Share your experiences or insights from implementing this project.

## License
This project is licensed under the MIT License - see the [LICENSE](../../LICENSE) file for details.
