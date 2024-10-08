# Project 2: Data Ingestion from CSV Files

## Overview

This project focuses on building a data ingestion pipeline to load data from multiple CSV files into a single Spark DataFrame using PySpark. The goal is to demonstrate the process of reading CSV files efficiently while handling errors and logging any issues that arise during the ingestion process.

## Objectives

- Create a Spark session and read multiple CSV files into a DataFrame.
- Implement error handling during the ingestion process.
- Log any issues encountered during the data loading.
- Display the schema and a sample of the loaded data for validation.

## Available Data Source

- [Global Temperature Data](https://datahub.io/core/global-temp)

## Files in This Project

- **data_ingestion_pipeline.ipynb**: Jupyter Notebook containing the complete data ingestion process.
- **data_ingestion_script.py** (optional): A Python script that can be used to execute the data ingestion pipeline independently.
- **data_sample.csv**: A sample CSV file used for demonstration (if applicable).
- **requirements.txt**: List of required Python packages to run the project.

## Getting Started

To run this project, follow these steps:

1. Clone the repository or download the project files.
2. Install the required packages using the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook data_ingestion_pipeline.ipynb
   ```
4. Follow the instructions in the notebook to execute the data ingestion pipeline.

## Reference Materials

- [Spark DataFrame API](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/index.html)
- [Handling Errors in PySpark](https://spark.apache.org/docs/latest/api/python/user_guide/sql/optimization.html#handling-errors)

## Outcome

By the end of this project, you should have a working data ingestion pipeline that successfully loads multiple CSV files into a single DataFrame, along with appropriate error handling and logging mechanisms.

## License

This project is licensed under the MIT License. See the [LICENSE](../../LICENSE) file for details.