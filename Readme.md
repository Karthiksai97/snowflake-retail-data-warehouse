# Snowflake Retail Data Warehouse Project

## Overview

This project demonstrates an end-to-end data warehouse implementation using Snowflake with a retail dataset. It includes data ingestion, transformation, automation, security, performance optimization, and cost monitoring using core Snowflake features.

## Architecture

```
RAW → STAGE → ANALYTICS
```

## Features Implemented

### Data Setup

* Warehouse creation and configuration
* Database and schema creation (RAW, STAGE, ANALYTICS)
* File format and stage creation
* Data loading using COPY INTO

### Data Modeling

* Raw table creation
* Dimension tables (Customer, Product)
* Fact table (Sales)

### Data Engineering

* Snowpipe (optional setup)
* Streams for change data capture
* Tasks for automated data loading

### Security and Governance

* Role-based access control
* Data masking policy
* Secure data sharing

### Performance Optimization

* Clustering
* Materialized views
* Zero-copy cloning

### Monitoring and Cost Control

* Resource monitor configuration

### Analytics Layer

* Views for reporting
* Materialized views for aggregated reporting

### Data Recovery

* Time travel for historical data access

## Use Cases

* Retail sales analysis
* Customer insights
* Product performance tracking
* Automated data pipeline
* Real-time data ingestion
* Secure data access
* Data sharing across teams
* Cost monitoring and control
* Performance optimization for reporting
* Data recovery and historical analysis

## Technologies Used

* Snowflake
* SQL
* Data Warehousing Concepts

## Dataset

Retail Superstore dataset (CSV format) included in the `data/` folder.

## Project Structure

```
snowflake-retail-data-warehouse/
│
├── data/
│   └── SampleSuperstore.csv
│
├── snowflake_retail_project.sql
└── README.md
```

## How to Run

1. Upload dataset to Snowflake stage
2. Execute SQL script
3. Query analytics tables and views

## Project Highlights

* End-to-end Snowflake data warehouse implementation
* Covers core and advanced Snowflake concepts
* Includes automation, security, and performance optimization
* Production-style data warehouse architecture
