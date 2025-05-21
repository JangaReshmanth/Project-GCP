# ELT Data Pipeline with GCP and Airflow
This project demonstrates how to build an ELT (Extract, Load, Transform) data pipeline to process 1 million records using Google Cloud Platform (GCP) and Apache Airflow. The pipeline extracts data from Google Cloud Storage (GCS), loads it into BigQuery, and transforms it to create country-specific tables and views for analysis.

# Description
Medical Research Team receives a global health statistics file containing disease over 1 million records.

# Challanges
* The data is currently provided as a single file containing over 1 million records for all countries.
* Due to confidential nature of the data, It is not feasible to share the entire file with everyone.
* Analysing such a large CSV fule to extract meaningful insights

# Objective
Develop a robust data analytics solution to securely manage and filter this data, 
Ensuring restricted access and enabling efficient analysis of disease withput available treatment or vaccination.

# Features
* Extract data from GCS in CSV format.
* Load raw data into a staging table in BigQuery.
* Transform data into country-specific tables and reporting views.
* Use Apache Airflow to orchestrate the pipeline.
* Generate clean and structured datasets for analysis.

# Workflow
* Extract: Check for file existence in GCS.
* Load: Load raw CSV data into a BigQuery staging table.
* Transform: Create country-specific tables in the transform layer.
* View: Generate reporting views for each country with filtered insights. 
       

# Data Layers
* Staging Layer: Raw data from the CSV file.
* Transform Layer: Cleaned and transformed tables.
* Reporting Layer: Views optimized for analysis and reporting.


