# Data Integration Pipelines for NYC Payroll Data Analytics - Udacity Azure Data Pipeline Project

## Project Overview

The City of New York aims to develop a Data Analytics platform on Azure Synapse Analytics to achieve two primary objectives:

1. Analyze the allocation of the City's financial resources and assess the proportion of the budget allocated to overtime.
2. Provide the public with access to data illustrating how the City's budget is spent on salaries and overtime payments for all municipal employees.

As a Data Engineer, your role is to create high-quality data pipelines that are dynamic, automatable, and monitorable for efficient operation. The project also involves collaboration with the city's quality assurance experts who will test the pipelines to identify errors and enhance overall data quality.

## Data Sources

The source data is located in Azure Data Lake and requires processing in a NYC data warehouse within Azure Synapse Analytics. The source datasets comprise CSV files containing Employee master data and monthly payroll data submitted by various City agencies.

## Project Objective

The primary objective of this project is to take source data and construct data flows in Azure Data Factory. These data flows will be responsible for extracting, joining, transforming, and aggregating New York City's payroll data. The processed data will be landed in Azure Synapse Analytics in a suitable schema to facilitate analytics and insights.

## Resources Utilized

This project leverages the following Azure resources:
- Azure Data Lake Gen2
- Azure SQL Database
- Azure Data Factory
- Azure Synapse Analytics

## Data Download

The datasets used for this project can be downloaded from the following link:
[Data NYC Payroll](https://video.udacity-data.com/topher/2022/May/6283aff5_data-nyc-payroll/data-nyc-payroll.zip)

