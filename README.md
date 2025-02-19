## Data Engineering with Reddit data 🚀
This project provides a comprehensive ETL (Extract, Transform, Load) pipeline for ingesting Reddit data into an Amazon Redshift data warehouse.
The pipeline is built using Apache Airflow for orchestration, PostgreSQL as the metadata database, and AWS services including S3, Glue, Athena, and Redshift for data storage and analytics.
# Pipeline:
 1. Extract data from Reddit using its API.
 2. Store the raw data into an S3 bucket from Airflow.
 3. Transform the data using AWS Glue and Amazon Athena.
 4. Load the transformed data into Amazon Redshift for analytics and querying.
  ![DEpipeline](https://github.com/user-attachments/assets/219a8a4c-4385-4465-8704-901611c04131)
 Reddit API: Source of the data.
 Apache Airflow : Orchestrates the ETL process and manages task distribution.
 PostgreSQL: Temporary storage and metadata management.
 Amazon S3: Raw and transformes data storage.
 AWS Glue: ETL jobs.
 Amazon Athena: SQL-based data transformation.
 Amazon Redshift: Data warehousing and analytics.


