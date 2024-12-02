# MS-Fabric-Demo
MS-Fabric-Demo-Project
Customer Churn Prediction: In this project, we will predict whether a predict whether bank customers would churn or not. The project requires Data ingestion and orchestration, Data Cleaning, Data Visualiation and Machine learning Model. The following Microsoft Fabric workload were used for the project delivery:
1. Data Engineering(Data Factory & Synpase Engineering)
2. Data Science
3. Data Analysis(Power BI)

# Project Architecture
Pipeline SetUp
1. Copy data from Blob Storage to the Lakehouse
2. Perform transformations on data using DataflowGen2 and store the transformed data in another Lakehouse
3. Create a Notebook to create a predictive ML model

# Data Engineering
The Dataset for this project was extracted from blob storage using copydata activity, transformed and Loaded into an already created lakehouse using dataflow gen2 that opens up the Power Query online.
On Power query, the lakehouse destination must be specified before publishing.

# Data Science
Spark notebook was created to build the machine learning model after it was connected to the existing lakehouse. 

# Data Analysis(Power BI)
Using the sematic model created in the Lakehouse, generate PowerBI Dashboard to perform analytics.
