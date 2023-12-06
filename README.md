# Covid-19 Health Care Data Engineering Project
## About Project:
To create a datawarehouse of COVID-19 data on Cases & Deaths, Hospital Admissions and more, develop a complete Data Pipeline using Azure Data Factory & Databricks.

## Getting Started
 1. Clone the project repository from [GitHub](https://github.com/rashmi0007/health_data/tree/main/health_testdata) .
 
 2. Above line can be skipped by fetching data from ECDC API. 
 
 3. Developed a Data Pipeline in Azure Data Factory
    
       ◾ Fetched data from [GitHub](https://github.com/rashmi0007/health_data/tree/main/health_testdata) to Azure Blob Storage.
    
![copyActivity](https://github.com/rashmi0007/health_data/assets/87612040/8ec646a1-d639-4f05-8364-58857a7948bc)

![CopySuccess](https://github.com/rashmi0007/health_data/assets/87612040/fe1a4e6d-4aa5-45ab-b93b-c6408fea3849)

        
       ◾ Processed data by applying diverse transformations as per requirements using:
    
           ▪ Used Dataflows in Data Factory
![Hospital_Datafloow](https://github.com/rashmi0007/health_data/assets/87612040/4917c8a6-36b2-4b73-9852-0b99d4360b1e)
-----------------------------------------------------------------------------------------------------------------------------
![admission_hospitalFlowData](https://github.com/rashmi0007/health_data/assets/87612040/8a19714d-17e3-4f7a-8169-5d68e684ed53)
    
           ▪ Pyspark in Azure Databricks to write data in Azure SQL DB.
 
 5. Created Data Lake to store raw and processed data.

 6. Developed a Data Warehouse in Azure SQL DB([DDL Command](https://github.com/rashmi0007/health_data/blob/main/AdditionalDetail/Hospital_DDL.SQL) & [Pyspark_code_in_SQL](https://github.com/rashmi0007/health_data/blob/main/code_to_write_in_SQL_DB.ipynb)) and masked the sensitive data using Pyspark functionality([Pyspark code](https://github.com/rashmi0007/health_data/blob/main/masking_dataWithPyspark_%26_with_SQL.ipynb))
 
 7. To get insights, the data from SQL DB was loaded to Power BI Desktop.
    
![Health_care_report](https://github.com/rashmi0007/health_data/assets/87612040/58a9cd35-494c-4146-ba29-7f78ab39216a)


## Services Used
 ◽ Azure Data Factory (Dataflows, Linked Services, Triggers, Azure Databricks)
 
 ◽ Azure Blob Storage
 
 ◽ Azure Data Lake Storage Gen 2
 
 ◽ Azure SQL DB
    
