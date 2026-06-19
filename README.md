# Transportation Analytics Lakehouse Platform

## Overview

End-to-end Data Engineering project built on Databricks
using Medallion Architecture.

Features:
- AWS S3 Data Lake
- Auto Loader Streaming Ingestion
- Delta Lake
- Unity Catalog
- Lakeflow Declarative Pipelines
- CDC Processing
- SCD Type 1 Upserts
- Gold Business Metrics
- Dashboarding

------------------------------------------------

## Architecture

[Architecture Diagram]

------------------------------------------------

## Tech Stack

Databricks
PySpark
Delta Lake
Lakeflow Declarative Pipelines
Unity Catalog
AWS S3
SQL

------------------------------------------------

## Data Flow

1. Operational Transportation System
2. Data Extract Service
3. AWS S3 Landing Zone
4. Bronze Layer
5. Silver Layer
6. Gold Layer
7. Dashboards / Genie

------------------------------------------------

## Medallion Architecture

### Bronze
Raw ingestion

### Silver
Validation
Standardization
CDC processing

### Gold
Business KPIs
Aggregations
Reporting

------------------------------------------------

## Data Quality Rules

- Fare must be positive
- Distance must be positive
- Driver rating 1-10
- Passenger rating 1-10
- Trip date after 2020

------------------------------------------------

## Data Model

City Dimension
Calendar Dimension
Trip Fact

------------------------------------------------

## Sample Queries

Top Revenue Cities
Average Driver Rating
Daily Revenue Trends

------------------------------------------------

## Dashboard Screenshots

------------------------------------------------

## Future Improvements

- SCD Type 2
- Data Quality Monitoring
- CI/CD with Databricks Asset Bundles
- Terraform Infrastructure
- Real-time Streaming
