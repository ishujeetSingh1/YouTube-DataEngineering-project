# YouTube-DataEngineering-project

## Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube video data based on the video categories and the trending metrics.

# Project Objectives

1. Data Acquisition — Establish a mechanism to gather information from diverse origins.
2. ETL Pipeline — Convert incoming raw data into the appropriate format, given its current state.
3. Data Reservoir — Create a centralized repository within a data lake to accommodate data from multiple origins.
4. Scalable Architecture — Design the system to seamlessly expand in response to growing data volume.
5. Cloud Integration — Utilize cloud infrastructure, specifically AWS, to process extensive data volumes impractical for local machines.
6. Reporting Infrastructure — Develop a dashboard facilitating insights into previously posed inquiries.

# Services Scheduled for Utilization

1. Amazon S3: Amazon S3 represents an object storage solution delivering extensive scalability, ensured data presence, robust security, and optimal performance.

2. AWS IAM: This pertains to identity and access management within AWS, enabling secure administration of access to AWS resources and services.

3. QuickSight: Amazon QuickSight stands as a cloud-oriented, machine learning-driven business intelligence (BI) service, boasting scalability, serverless operation, embeddable features, and cloud-native design.

4. AWS Glue: A serverless service focused on data integration, AWS Glue streamlines the tasks of data discovery, preparation, and amalgamation, serving analytics, machine learning, and application development purposes.

5. AWS Lambda: Lambda denotes a computing service affording developers the ability to execute code sans the necessity for server creation or management.

6. AWS Athena: Athena serves as an interactive inquiry platform tailored for S3, eliminating the need for data loading as information resides within S3.

# Utilized Dataset

Within this Kaggle dataset, you will find statistical information (stored in CSV files) regarding frequently viewed YouTube videos spanning numerous months. Each day witnesses the emergence of a potential 200 trending videos across various locations. The dataset is segmented into distinct files for each region, encompassing details such as video titles, channel titles, time of publication, tags, view counts, appreciation and dissatisfaction indicators, descriptions, and comment quantities. Additionally, a category_id field, unique to each region, is integrated within the JSON file associated with the particular area.

https://www.kaggle.com/datasets/datasnaek/youtube-new

# Architecture Diagram

![architecture](https://github.com/ishujeetSingh1/YouTube-DataEngineering-project/assets/142827400/35a0b6c7-cbbe-4bd9-9743-3f049252231c)
