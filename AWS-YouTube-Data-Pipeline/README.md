# AWS YouTube Data Engineering Pipeline

## 📌 Project Overview
An end-to-end Data Engineering project that ingests, stores, transforms, and prepares YouTube trending video statistics for analytics using AWS cloud services.

## 🛠️ Technologies Used
- **AWS:** Amazon S3, AWS Glue, AWS Lambda, Step Functions
- **Analytics & Monitoring:** Amazon Athena, Glue Data Catalog, CloudWatch, SNS
- **Programming:** Python, PySpark, SQL
- **Data Formats:** CSV, JSON, Parquet

## 🔄 Pipeline Workflow
1. Ingest YouTube statistics and category reference data.
2. Store raw data in the Amazon S3 Bronze layer.
3. Clean and transform data using AWS Glue and Lambda.
4. Store processed data in the Silver layer in Parquet format.
5. Catalog and query data using AWS Glue Data Catalog and Amazon Athena.
6. Orchestrate workflows and monitor failures using Step Functions, CloudWatch, and SNS.

## 📂 Project Structure
- `data/` — Input CSV and JSON files
- `data_quality/` — Data quality checks
- `Glue_jobs/` — AWS Glue ETL scripts
- `lambda/` — Lambda processing functions
- `Script/` — Data upload scripts
- `step_function/` — Workflow orchestration configuration
- `youtube_api_integstion/` — YouTube API integration

## 🎯 Objective
To gain practical experience in cloud-based data ingestion, ETL processing, data quality, workflow orchestration, and data lake architecture.

## 🚧 Project Status
In Progress

## 👨‍💻 Author
**Rushikesh Taralkar**

- GitHub: [RushikeshTaralkar007](https://github.com/RushikeshTaralkar007)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/rushikesh-taralkar-89b363313/)
