# End-to-End Data Engineering Project using Databricks (FMCG Domain)

## Project Overview
This project demonstrates an end-to-end data engineering pipeline built using Databricks in the FMCG domain.

## Problem Statement
After a company acquisition, FMCG data existed in different formats and systems. The goal was to integrate, clean, and transform raw data into analytics-ready datasets.

## Architecture Used
Medallion Architecture:
- Bronze: Raw data ingestion
- Silver: Cleaned and standardized data
- Gold: Business-ready aggregated data

## Technologies Used
- Databricks
- Apache Spark
- Python
- SQL
- Cloud Storage

## Project Workflow
1. Ingest raw data
2. Store raw data in Bronze layer
3. Clean data in Silver layer
4. Create aggregations in Gold layer
5. Enable reporting and analytics

## How to Run
- Upload notebooks to Databricks
- Execute notebooks in sequence
