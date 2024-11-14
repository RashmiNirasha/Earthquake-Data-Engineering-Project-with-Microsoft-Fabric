# Earthquake-Data-Engineering-Project-with-Microsoft-Fabric

## Prerequisites
- Microsoft Azure Account 
- Microsoft Fabric Account.
- Familiarity with Python, Spark, and basic data engineering concepts.
- Basic Power BI skills.

## Project Overview
Learn to build an end to end data engineering and analysis pipeline utilising Microsoft Fabric’s 
-> Data Factory, 
-> Data Engineering, and 
-> Power BI experiences. 

Ingesting Earthquake events data from [usgs](https://earthquake.usgs.gov/). 

Technologies Used: Python, PySpark, Fabric (Data Engineering, Data Factory, Power BI)

## Create A fabric capacity in Azure Administrator account 
Before we start with this project , we need a facric capacity of F64 or more to work with all the features in fabric portal. To create a capacity, 
- Log into Azure Administartor portal
- Select Microsoft fabric resource 
- ![Alt text](/Images/How_to_make_fabric_Capacity.png)
- Select review and create and wait for deployement. 
- ![Alt text](/Images/capacity.png)


## Getting Started
To get started with this project, downalod the notebooks in the repository and follow the guidance provided in the YouTube tutorial.

## Repository Contents
`Worldwide Earthquake Events API - Bronze Layer Processing`: This notebook focuses on ingesting raw earthquake data from the USGS API. It performs minimal processing to store data in its original format, serving as the foundational layer for further refinement.

`Worldwide Earthquake Events API - Silver Layer Processing`: This notebook enhances the data from the Bronze layer by cleaning, transforming, and consolidating the earthquake data. It prepares the data for more analytical processing.

`Worldwide Earthquake Events API - Gold Layer Processing`: In this final processing stage, the notebook refines the data to create business-ready datasets. These are optimized for high-value insights and are tailored for specific analytical purposes, such as reporting and visualization in tools like Power BI.

## Execution Results
- ![Alt text](/Images/power_bi_report01.png)
- ![Alt text](/Images/power_bi_report02.png)
- ![Alt text](/Images/data_pipeline.png)
- ![Alt text](/Images/power_bi_report_after_pipeline.png)
- ![Alt text](/Images/Final_Project_Structure.png)


Initial Project credit : https://github.com/malvik01/Earthquake-Data-Engineering-Project-with-Microsoft-Fabric/tree/main 


