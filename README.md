# 📂 **Uber Data Pipeline and Data Modeling Project**

## 📚 *Introduction*
This project aims to build an automated data pipeline for processing Uber data, including data ingestion, transformation, storage, and querying for analytics and visualization. The pipeline leverages Google Cloud services, including Cloud Storage, BigQuery to automate the ETL process, ensuring scalability and efficiency.

### ⚙️ *Methodology*
Data Storage: Google Cloud Storage (GCS), BigQuery
Data Processing: BigQuery SQL, Apache Airflow (Cloud Composer)
Programming Languages: Python, SQL

### 🔄 *Project Workflow*
![Airflow DAG](https://github.com/ZhihongMai/End-to-End-Uber-Data-Engineering/blob/main/Airflow.png)
The data pipeline follows a structured ETL (Extract, Transform, Load) process:
1. Data Ingestion: Collecting raw taxi trip data from external sources.
2. Data Modeling: Structuring the data into a star schema for optimized querying.
3. Data Transformation: Cleaning, transforming, and standardizing data.
4. Data Storage: Loading processed data into a relational database.
5. Data Querying: Enabling analytical queries on the processed data.
6. Pipeline Automation: Scheduling and orchestrating tasks using Apache Airflow.

### 🗂️ *Schema Design* ![Data Model](https://github.com/ZhihongMai/End-to-End-Uber-Data-Engineering/blob/main/Data%20Model.png)

## 📝 *Summary*
This project demonstrates how to build an end-to-end Uber data processing pipeline on Google Cloud, automating ETL workflows and storing the cleaned data in BigQuery for efficient querying and analysis. It is designed to support business intelligence, reporting, and decision-making, with scalability and automation at its core
