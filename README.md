# Stock-Market-Real-Time-Analysis-Using-Kafka

## Introduction
This README file provides an overview of the **Stock Market Kafka Real Time Data Engineering Project**, which involves building an End-To-End Data Engineering solution for processing and analyzing real-time stock market data using Apache Kafka. This project utilizes a variety of technologies, including Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture
![Architecture](https://github.com/kssmp/Stock-Market-Real-Time-Analysis-Using-Kafka/assets/115448106/587ab249-6f6f-4ef5-b65b-eaa4a887df8c)


The architecture diagram above illustrates the high-level design of this project. It showcases how various components interact to collect, process, and analyze real-time stock market data.

## Technology Used
The following technologies are employed in this project:

- **Programming Language**:
  - Python

- **Amazon Web Services (AWS)**:
  1. **S3 (Simple Storage Service)**: Used for storing raw and processed data.
  2. **Athena**: Utilized for querying data stored in S3 using SQL-like syntax.
  3. **Glue Crawler**: Automatically discovers and catalogs data in S3.
  4. **Glue Catalog**: Stores metadata and schema information for data in S3.
  5. **EC2**: Amazon Elastic Compute Cloud instances for running necessary services.

- **Apache Kafka**: Used as the real-time data streaming platform for collecting and distributing stock market data.


## Usage
Once the project is set up and running, you can:

1. Observe real-time stock market data flowing through the Kafka topics.

2. Use AWS Athena to query and analyze the stored data in S3.

3. Extend the project by adding custom data processing and analysis scripts in Python.
