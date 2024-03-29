# Data_Engineering_Youtube_Analysis
Data Engineering Youtube Analysis Project


 # Overview:
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

# Project Goals:
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Scalability — As the size of our data increases, we need to make sure our system scales with it
4. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
5. Reporting — Build a dashboard to get answers to the question we asked earlier


# Services we will be using:
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

# Dataset Used:
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new


# Architecture Diagram:

<img width="1139" alt="Screen Shot 2023-10-26 at 09 40 11" src="https://github.com/surbhiwahie/Data_Engineering_Youtube_Analysis/assets/24772688/e0844ac0-6d0d-445e-af70-408560468230">


# Data lake:

<img width="893" alt="Screen Shot 2023-10-26 at 10 18 15" src="https://github.com/surbhiwahie/Data_Engineering_Youtube_Analysis/assets/24772688/9e523614-dd8d-4166-938e-523b5daeaa1a">

# AWS Glue Catalog
<img width="815" alt="Screen Shot 2023-10-26 at 10 18 36" src="https://github.com/surbhiwahie/Data_Engineering_Youtube_Analysis/assets/24772688/559a2372-9b8d-41f9-b630-ccad3cd221ad">

<img width="799" alt="Screen Shot 2023-10-26 at 10 25 40" src="https://github.com/surbhiwahie/Data_Engineering_Youtube_Analysis/assets/24772688/1a062b19-cd03-44ef-b1b3-8b06a305eae3">


# Data Cleaning 

<img width="1234" alt="Screen Shot 2023-10-26 at 11 01 44" src="https://github.com/surbhiwahie/Data_Engineering_Youtube_Analysis/assets/24772688/3a886ca0-ba85-4147-be7e-863576ac65ed">

