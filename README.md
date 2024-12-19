# MS-Fabric
MS-Fabric-Project
Customer Churn Prediction: This project showcases a simple workflow in MS Fabric utilizing bank customer churn data. The project involves Data ingestion and orchestration, Data Cleaning, Data Visualization, and Machine learning models. The following Microsoft Fabric workloads were used for the project delivery:
1. Data Factory & Synapse Data Engineering
2. Data Science
3. Power BI
![image](https://github.com/user-attachments/assets/40e0c264-9670-467b-8b75-af20a4366c0a)

# Project Architecture
![image](https://github.com/user-attachments/assets/89fccec6-f312-4c21-9369-2c463fbc92e6)

Pipeline SetUp
1. Copy data from Blob Storage to the Lakehouse
2. Perform transformations on data using DataflowGen2 and store the transformed data in another Lakehouse
3. Create a Notebook to create a predictive ML model
![image](https://github.com/user-attachments/assets/8c3b39ef-330f-4169-9674-c2cea2c7c8aa)

# Data Engineering
The Dataset for this project was extracted from blob storage using copy data activity, transformed, and Loaded into an already created lakehouse using dataflow gen2 that opens up the Power Query online.
On the Power query, the lakehouse destination must be specified before publishing.
![image](https://github.com/user-attachments/assets/2134063d-37bb-4dc1-9c4b-cb209a2944e5)

# Data Science
Spark Notebook was created to build the machine learning model after it was connected to the existing lakehouse. 
![image](https://github.com/user-attachments/assets/481c3f02-cf49-4709-9c46-b0257cd9b25b)

# Data Analysis(Power BI)
Using the semantic model created in the Lakehouse, generate a PowerBI Dashboard to perform analytics.
![image](https://github.com/user-attachments/assets/9219bfb1-602b-4dac-9c56-56283d63cd1e)

Blog: https://datasciencedojo.com/blog/microsoft-fabric-sales-use-case/
