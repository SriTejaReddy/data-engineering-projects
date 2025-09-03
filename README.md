# Spark Batch ETL Pipeline

## Overview
An end-to-end ETL pipeline with PySpark to process Google Ads data. 
Transformed raw CSV into clean parquet datasets and loaded them into PostgreSQL for analytics.

## Tech Stack
- PySpark
- PostgreSQL
- Python

## Features
- Extract raw CSV → clean & transform with Spark
- Handle missing values, clean text/numeric fields
- Staging + warehouse layers
- Load to PostgreSQL

## How to Run
```bash
python extract.py
python transform.py
python load.py
