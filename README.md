# Celebal Internship - Data Ingestion Project

This project demonstrates how to ingest data from CSV files into Azure using Azure Data Factory (ADF) and process them using Azure Databricks with Delta Lake and ADLS Gen2.

## Project Structure

- **input_files/**: Contains sample CSV data for customers, sales, and products.
- **adf_pipelines/**: Placeholder folder for ADF pipeline JSON exports.
- **screenshots/**: Placeholder for pipeline execution screenshots.
- **data_ingestion_notebook.ipynb**: Databricks notebook for processing CSVs into Delta tables.
- **project_report.pdf**: A summary report of the entire project.

## Technologies Used

- Azure Data Factory
- Azure Databricks
- Delta Lake
- Azure Data Lake Storage Gen2
- PySpark

## How It Works

1. Upload the sample CSVs to ADLS Gen2.
2. Use ADF to ingest data into staging zones with triggers and fault tolerance.
3. Use Databricks to process and write data to Delta tables.
