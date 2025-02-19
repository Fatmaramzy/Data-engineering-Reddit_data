## Data Engineering with Reddit data 
This project provides a comprehensive ETL (Extract, Transform, Load) pipeline for ingesting Reddit data into an Amazon Redshift data warehouse.
The pipeline is built using Apache Airflow with Celery for orchestration, PostgreSQL as the metadata database, and AWS services including S3, Glue, Athena, and Redshift for data storage and analytics.
# Pipeline:
 1. Extract data from Reddit using its API.
 2. Store the raw data into an S3 bucket from Airflow.
 3. Transform the data using AWS Glue and Amazon Athena.
 4. Load the transformed data into Amazon Redshift for analytics and querying.
 
