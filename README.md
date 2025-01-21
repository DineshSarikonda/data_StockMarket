📈 Stock Market Kafka Real-Time Data Engineering Project
📖 Introduction
This project demonstrates an End-To-End Data Engineering pipeline for real-time stock market data processing using Apache Kafka and Amazon Web Services (AWS). The primary goal is to build a robust pipeline capable of ingesting, processing, and analyzing real-time stock market data with minimal latency.

🏗️ Architecture
The architecture of this project involves the following components:

Data Ingestion: Use Apache Kafka to stream real-time stock market data.
Data Storage: Store data in AWS S3 for scalability and durability.
Data Cataloging: Use AWS Glue to crawl and catalog the data for querying.
Data Processing: Process data with Glue jobs and Python scripts.
Data Querying: Query the cataloged data using AWS Athena.

🛠️ Technology Used
Programming Language: Python
Amazon Web Services (AWS):
S3 (Simple Storage Service)
Athena
Glue Crawler
Glue Catalog
EC2
Streaming Tool: Apache Kafka
💾 Dataset Used
Dataset: The dataset contains historical stock market data and can be found at:
indexProcessed.csv
While you can use this dataset, the primary focus of this project is on building the data pipeline, so any similar stock market dataset can be used.

🎯 Key Steps in the Project
Kafka Setup:

Set up an Apache Kafka cluster to stream stock market data.
Simulate real-time data ingestion using the given dataset.
Data Storage in S3:

Configure AWS S3 buckets to store raw and processed data.
Write Python scripts to send Kafka streams to S3.
AWS Glue for Data Cataloging:

Use AWS Glue Crawler to catalog raw data stored in S3.
Create Glue jobs to transform and clean the data for analysis.
Data Querying with Athena:

Query the transformed data in the Glue Catalog using SQL in AWS Athena.
Analyze key insights from the stock market data.
📬 Contact
For queries or collaboration:

Email: sarikondadinesh23@gmail.com
GitHub: DineshSarikonda
