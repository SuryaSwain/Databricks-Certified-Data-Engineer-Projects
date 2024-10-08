# Project 9: Data Quality Checks

## Overview

This project focuses on implementing data quality checks on incoming datasets using PySpark. The goal is to ensure the integrity, accuracy, and completeness of data before it is processed and analyzed.

## Objectives

- Validate the quality of incoming data using various checks.
- Implement logging mechanisms to track data quality issues.
- Use the NYC taxi dataset for practical demonstrations of data quality checks.

## Available Data Source

- [NYC Taxi Dataset](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page): A dataset containing trip records for NYC taxis.

## Files in This Project

- **data_quality_checks.py**: Python script containing the implementation of data quality checks.
- **requirements.txt**: List of required Python packages to run the project.
- **nyc_taxi_data.csv**: Sample CSV file of the NYC taxi dataset for testing the quality checks.

## Getting Started

To run this project, follow these steps:

1. Clone the repository or download the project files.
2. Install the required packages using the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data quality checks script:
   ```bash
   spark-submit data_quality_checks.py
   ```

## Reference Materials

- [Data Quality in Spark](https://databricks.com/glossary/data-quality)
- [Data Validation with PySpark](https://towardsdatascience.com/data-validation-in-pyspark-9cc95c0eb00)
- [Working with DataFrames in PySpark](https://spark.apache.org/docs/latest/api/python/user_guide/pyspark.sql.html)

## Outcome

By the end of this project, you will have implemented various data quality checks on the NYC taxi dataset. You will gain practical experience in validating data and logging issues, which is crucial for maintaining data integrity in data engineering workflows.

## License

This project is licensed under the MIT License. See the [LICENSE](../../LICENSE) file for details.
