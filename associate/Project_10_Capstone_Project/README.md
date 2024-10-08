# Project 10: Capstone Project

## Overview

This capstone project integrates the skills and knowledge acquired throughout the Databricks Certified Data Engineer Associate certification preparation. The project involves building a comprehensive data engineering pipeline, from data ingestion to analysis, demonstrating the use of various tools and techniques learned in previous projects.

## Objectives

- Create a complete data pipeline using Databricks and Apache Spark.
- Implement data ingestion, transformation, and analysis processes.
- Utilize Delta Lake for data storage and management.
- Present insights derived from the analysis.

## Available Data Source

Choose a suitable dataset based on your interests or project requirements. Some suggested datasets include:

- [E-commerce Transactions Dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-data)
- [Public Health Data](https://www.kaggle.com/datasets/kaushiksuresh147/healthcare-data)

## Project Structure

- **data_ingestion.py**: Script for ingesting data from the chosen source.
- **data_transformation.py**: Script for transforming the ingested data.
- **data_analysis.py**: Script for performing analysis on the transformed data.
- **final_report.ipynb**: Jupyter notebook summarizing the project findings and insights.

## Getting Started

To run this project, follow these steps:

1. Clone the repository or download the project files.
2. Install the required packages using the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Update the data source paths in the scripts as needed.
4. Run the ingestion, transformation, and analysis scripts in order:
   ```bash
   spark-submit data_ingestion.py
   spark-submit data_transformation.py
   spark-submit data_analysis.py
   ```
5. Open the `final_report.ipynb` notebook to review the insights.

## Reference Materials

- [Building Data Pipelines with Databricks](https://www.databricks.com/solutions/data-pipelines)
- [Data Engineering with Databricks](https://www.databricks.com/solutions/data-engineering)
- [Delta Lake Documentation](https://docs.delta.io/latest/index.html)

## Outcome

By the end of this capstone project, you will have developed a full-fledged data engineering pipeline that demonstrates your ability to integrate various components of data engineering. The final report will showcase your insights and findings, preparing you for real-world data engineering tasks.

## License

This project is licensed under the MIT License. See the [LICENSE](../../LICENSE) file for details.
