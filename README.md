# REST API to Synapse Analytics Data Engineering End to End Project
In this Project of data engineering, i have used a free fake api data to be copied from rest api source to synapse analytics. The first step which i did is i copied the data from rest api source to azure blob storage using azure data factory. Then for some transformation i used azure databricks for adding one more column into the rest api dataset for which i mount azure blob storage on azure databricks using python notebook. After transformation i write back the transformed file back to azure blob storage in same .csv format. And then i loaded this .csv file in azure synapse analytics having dedicated sql pools using azure data factory polybase technology. so mainly there are 3 step which i performed in this such as 

- copy rest api data to azure blob storage in which i used schedule trigger

- transformation using azure databricks notebook in which i used a storage event trigger 

- copying transformed data to synapse analytics using azure data factory polybase technology in which i used a storage event trigger

The following Azure services has been used in this project.

1. Azure Data Lake
2. Azure synapse (dedicated sql pool)
3. Azure Data Factory
4. azure databricks

The Following is google drive video link of whole project implementation:
