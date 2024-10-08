# Project 7: Building a Streaming Data Pipeline

## Overview

This project involves creating a streaming data pipeline using Spark Structured Streaming. The goal is to ingest, process, and store streaming data in real-time, showcasing the capabilities of Spark for handling continuous data streams.

## Objectives

- Set up a simulated streaming data source (e.g., Kafka).
- Build a Spark Structured Streaming application to ingest and process the streaming data.
- Write the processed data to a Delta Table for further analysis.

## Available Data Source

- Use a simulated streaming source, such as [Apache Kafka](https://kafka.apache.org/documentation/).

## Files in This Project

- **streaming_data_pipeline.ipynb**: Jupyter Notebook containing the implementation of the streaming data pipeline.
- **kafka_producer.py**: Python script to simulate a data producer that sends data to Kafka.
- **requirements.txt**: List of required Python packages to run the project.
- **schema_definition.json**: JSON file defining the schema of the streaming data.

## Getting Started

To run this project, follow these steps:

1. Ensure that Apache Kafka is installed and running on your machine.
2. Clone the repository or download the project files.
3. Install the required packages using the following command:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the Kafka producer to simulate streaming data:
   ```bash
   python kafka_producer.py
   ```
5. Open the Jupyter Notebook:
   ```bash
   jupyter notebook streaming_data_pipeline.ipynb
   ```
6. Run the cells in the notebook to start the Spark Structured Streaming job and observe the processing of incoming data.

## Reference Materials

- [Structured Streaming Programming Guide](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
- [Streaming with Databricks](https://docs.databricks.com/structured-streaming/index.html)
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/)

## Outcome

By the end of this project, you will have developed a complete streaming data pipeline that demonstrates the principles of real-time data processing with Spark. You will gain experience in integrating Kafka with Spark and writing data to Delta Tables.

## License

This project is licensed under the MIT License. See the [LICENSE](../../LICENSE) file for details.
