<p align="center">
  <img src="https://github.com/CosimoFaeti/laboratory-data-science/assets/99746565/a42789d6-fb32-47ae-b72d-e9e4ae4dca60" alt="unipi" width="30%">
</p>

# Business Intelligence Process  
This repository contains my project for the *Laboratory of Data Science course* of my Master's degree in Data Science and Business Informatics at Università di Pisa.
The project entails data integration, construction of an OLAP cube, qurying of a OPLAP cube and reporting. Specifically, the tasks entails retrieving data from various sources, 
executing ETL pipelines, and performing data analysis and dashboard creation using Microsoft Visual Studio (SSIS, SSAS, MDX), Python, SSMS, and Power BI.

## Repository Overview
In this repository, in the root level, you can find the pdf version of the report, the data and the code for the implementation of business intelligence process. More specifically:

**LDS_Part1_Group13**:
* LDS_module.py : Created a data mart following the schema assigned. Then extracted data from the file answerdatacorrect.csv and subject metadata.csv and transformed
them according to the pipeline in Assignment 1. Finally, populated the data mart using the processed data.

**LDS_Part2_Group13**:
* Solved three assignments by using Sequel Server Integration Services (SSIS) with computation only on client side. The SSIS project is composed by three SSIS packages that corresponds to each assignment. Used the database created in the previous part.

**LDS_Part3_Group13**:
* Built a datacube by using SQL Server Analysis Services (SSAS) from the data stored in the database (Assignment 0). Then, solved the query of Assignment 1, 2 and 3 using MDX language in Microsoft SQL Server Management. As last step, created two dashboards using PowerBI (Assignment 4 and 5).
