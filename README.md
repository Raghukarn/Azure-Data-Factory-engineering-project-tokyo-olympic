# Azure-Data-Factory-engineering-project-tokyo-olympic

This repository contains the code and resources for setting up an end-to-end data pipeline using Azure Data Factory, Azure Databricks, and Synapse Analytics. The project demonstrates data ingestion, transformation, and analysis using cloud technologies.

![Architecture project image](https://github.com/Raghukarn/Azure-Data-Factory-engineering-project-tokyo-olympic/assets/119719960/d6fa101e-18db-4965-8529-07413703c38d)

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

#### Avg entries by gender per discipline
![avg entries per gender](https://github.com/Raghukarn/Azure-Data-Factory-engineering-project-tokyo-olympic/assets/119719960/dc4b95c6-b47f-453a-9e4e-f1d09658904e)

#### #Athletes participated per country
![athletes per country](https://github.com/Raghukarn/Azure-Data-Factory-engineering-project-tokyo-olympic/assets/119719960/57c5ddfc-040c-41cc-814b-7d98de64cf82)

#### Top 10 countries by medal count
![Top 10 Countries by medals](https://github.com/Raghukarn/Azure-Data-Factory-engineering-project-tokyo-olympic/assets/119719960/5a5d3704-c916-4fad-91d3-bf7146c000dc)



