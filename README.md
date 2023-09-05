# Data Engineering YouTube ETL Project

## Abstract

Project's objective is to securely manage, streamline, and conduct analysis on both structured and semi-structured YouTube's trending video data, focusing on video categories and trending metrics

## Objective

* Data Ingestion: Develop a robust mechanism for seamlessly ingesting data from diverse sources.
* ETL System: Transform raw data into the required format for analysis and storage.
* Data Lake: Establish a centralized repository to efficiently store data obtained from multiple sources.
* Scalability: Ensure that our system can dynamically scale to handle growing data volumes effectively.
* Cloud Integration: Utilize AWS to process and manage vast datasets that exceed local computing capabilities.

## Data Sources Employed

This dataset encompasses an extensive collection of daily trending YouTube videos, spanning several months. It covers the regions of the United States, Great Britain, Germany, Canada, and France, providing information on up to 200 trending videos per day in each of these regions.
Link: https://www.kaggle.com/datasets/datasnaek/youtube-new


## Services Used
- **Amazon S3** is an object storage service renowned for its manufacturing scalability, data availability, robust security measures, and exceptional performance.

- **AWS IAM** stands for Identity and Access Management, a crucial tool that empowers users to securely manage access to various AWS services and resources.

- **AWS Glue** is a serverless data integration service designed to simplify data discovery, preparation, and aggregation for tasks like analytics, machine learning, and application development.

- **AWS Lambda** is a computing service that enables developers to execute code without the need to create or manage servers.

- **AWS Athena** is an interactive query service tailored for Amazon S3. It enables users to perform queries on data residing in S3 without the necessity to load it into a separate database.

## Transformations; pictorial representsation
![transformation](https://github.com/prajwal-ns/data-engineering-youtube-etl-project/assets/90051040/dd50b919-5ef3-4fae-ba4e-c3d5d9f86eff)

Architecture Diagram

![Data architecture](https://github.com/prajwal-ns/data-engineering-youtube-etl-project/assets/90051040/36d90e72-2eb7-4cd4-90e9-62ae433d0814)







