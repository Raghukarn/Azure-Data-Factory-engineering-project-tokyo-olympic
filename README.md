# Azure-Data-Factory-engineering-project-tokyo-olympic

This repository contains the code and resources for setting up an end-to-end data pipeline using Azure Data Factory, Azure Databricks, and Synapse Analytics. The project demonstrates data ingestion, transformation, and analysis using cloud technologies.

### This project involves the following key steps:

#### Storage Setup:

- Create Azure storage accounts.
- Set up containers with directories for raw and transformed data.

#### Data Ingestion:

- Use Azure Data Factory to create a pipeline for data ingestion.
- Copy data from API or source to raw-data folders in Azure.
- Access raw data from a GitHub CSV file URL using HTTP as the source.
- Set up Azure Data Lake Gen 2 Storage Account as the destination.

#### Data Transformation:

- Launch Azure Databricks workspace and create compute services.
- Read files from Azure Data Lake Gen 2 using Spark.
- Transform raw data in Databricks and save the results in the transformed-data folder.
- Set up mounting to connect Databricks and Azure Data Lake Gen 2.

#### Data Analysis:

- Create Synapse Analytics workspace.
- Perform SQL queries to derive insights from the transformed data, such as:
- Top 10 performing countries in the Olympics.
- Number of athletes from each country.
- Average number of male and female participants in each discipline.

#### Prerequisites
- Azure subscription
- GitHub account
