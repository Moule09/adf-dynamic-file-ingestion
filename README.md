# Azure Data Factory – Dynamic File Ingestion Pipeline

## Project Name
Dynamic File Ingestion using Azure Data Factory

## Description
This project demonstrates a production-ready Azure Data Factory pipeline that dynamically processes multiple files from Azure Data Lake Storage.

## Key Features
- Get Metadata activity to list files in a folder
- ForEach activity to process files dynamically
- Conditional logic to separate CSV and JSON files
- Parameterized datasets to avoid hardcoding file names
- Copies files to separate destination folders

## Pipeline Flow
Get Metadata → ForEach → If Condition → Copy Activity

## Technologies Used
- Azure Data Factory
- Azure Data Lake Storage Gen2

## Author
Moule Mohanraj S
