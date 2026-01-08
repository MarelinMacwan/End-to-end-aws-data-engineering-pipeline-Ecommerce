# End-to-End AWS Data Engineering Pipeline

## Project Overview
This project implements an end-to-end cloud-based data engineering pipeline to ingest, transform, and warehouse e-commerce data for analytics and reporting.

## Business Use Case
Analyze e-commerce sales performance, customer behavior, and product trends using a scalable AWS data pipeline.

## Architecture
![Architecture Diagram](diagrams/architecture.png)

## Tech Stack
- Python
- AWS S3
- AWS Glue / Airflow
- AWS Redshift
- SQL

## Data Pipeline
1. Raw data ingestion to S3
2. Data cleaning and transformation
3. Star schema modeling
4. Data loading into Redshift
5. Analytics queries

## Data Modeling
- Fact table: orders
- Dimension tables: customers, products, date

## Analytics & Insights
- Total revenue by month
- Top-selling products
- Customer purchase trends

## Improvements
- Incremental loads
- Data quality checks
- Cost optimization
