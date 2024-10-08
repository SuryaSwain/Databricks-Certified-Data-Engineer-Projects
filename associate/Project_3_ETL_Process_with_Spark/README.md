# Project 3: ETL Process with Spark

## Overview

This project focuses on creating a complete ETL (Extract, Transform, Load) process using Apache Spark. The objective is to extract data from a sample sales dataset, perform necessary transformations (such as filtering, aggregating, and cleaning), and load the transformed data into Delta Lake for further analysis.

## Objectives

- Extract data from a sample sales dataset.
- Perform data transformations, including filtering, aggregation, and cleaning.
- Load the transformed data into Delta Lake for optimized storage and querying.
- Document the entire ETL process and the transformations applied.

## Available Data Source

- [Sample Sales Data](https://www.kaggle.com/datasets/mkechinov/ecommerce-data)

## Files in This Project

- **etl_pipeline.ipynb**: Jupyter Notebook containing the complete ETL process with detailed explanations.
- **etl_script.py** (optional): A Python script that can be executed to run the ETL pipeline independently.
- **sales_data.csv**: A sample CSV file used for demonstration (if applicable).
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
   jupyter notebook etl_pipeline.ipynb
   ```
4. Follow the instructions in the notebook to execute the ETL process.

## Reference Materials

- [ETL with Spark](https://www.databricks.com/glossary/etl)
- [Delta Lake Documentation](https://docs.delta.io/latest/index.html)

## Outcome

By the end of this project, you will have a functional ETL pipeline that extracts data from the source, applies necessary transformations, and loads the cleaned data into Delta Lake. This will provide you with hands-on experience in building ETL processes using Spark.

## License

This project is licensed under the MIT License. See the [LICENSE](../../LICENSE) file for details.
