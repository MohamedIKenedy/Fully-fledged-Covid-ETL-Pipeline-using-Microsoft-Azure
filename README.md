# Covid-19 Health Care Data Engineering Project
## About Project:
To create a datawarehouse of COVID-19 data on Cases & Deaths, Hospital Admissions and more, develop a complete Data Pipeline using Azure Data Factory & Databricks.

## Getting Started
 1. Clone the project repository from [GitHub](https://github.com/rashmi0007/health_data/tree/main/health_testdata) .
 
 2. Above line can be skipped by fetching data from ECDC API. 
 
 3. Developed a Data Pipeline in Azure Data Factory
    
       ◾ Fetched data from [GitHub](https://github.com/rashmi0007/health_data/tree/main/health_testdata) to Azure Blob Storage.
    
         ![pic12](https://github.com/rashmi0007/health_data/assets/87612040/8bb0eaa6-9d3a-40c6-8d6d-23ac767286d4)

    
       ◾ Processed data by applying diverse transformations as per requirements using:
    
           ▪ Dataflows in Data Factory
    
           ▪ Pyspark in Azure Databrick
 
 5. Created Data Lake to store raw and processed data.

 6. Developed a Data Warehouse in Azure SQL DB and masked the sensitive data using Pyspark functionality
 
 7. To get insights, the data from SQL DB was loaded to Power BI Desktop.

## Services Used
 ◽ Azure Data Factory (Dataflows, Linked Services, Triggers, Azure Databricks)
 
 ◽ Azure Blob Storage
 
 ◽ Azure Data Lake Storage Gen 2
 
 ◽ Azure SQL DB
    
