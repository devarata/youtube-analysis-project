# YouTube Analysis

## Overview
The YouTube Analysis project is dedicated to the secure management, streamlining, and analysis of structured and semi-structured YouTube video data. The primary focus lies on video categories and trending metrics to yield significant insights.

## Project Goals

1. **Data Ingestion**: Create a reliable mechanism to pull data from diverse sources.
2. **ETL System**: The incoming data is in a raw format. We will transform this data into a usable structure.
3. **Data Lake**: With data being pulled from multiple sources, there's a necessity for a centralized repository.
4. **Scalability**: It's imperative that as the volume of our data grows, our system should efficiently scale.
5. **Cloud**: Due to the volume of the data, processing it locally isn't feasible. AWS cloud services will be employed for this project.
6. **Reporting**: Develop a dashboard to offer insights based on the data and the questions posed.

## Services in Use

1. **Amazon S3**: An object storage service known for its scalability, security, and performance.
2. **AWS IAM**: Pertaining to identity and access management, this allows us to securely manage access to AWS services.
3. **QuickSight**: A cloud-native BI service powered by machine learning, enabling detailed insights.
4. **AWS Glue**: This serverless data integration service streamlines data discovery, preparation, and integration.
5. **AWS Lambda**: An event-driven, serverless computing platform that executes code based on event triggers.
6. **AWS Athena**: An interactive query service tailored for S3, allowing data querying without needing to load the data first.

## Dataset Information

The project utilizes a dataset from Kaggle which captures statistics on popular YouTube videos on a daily basis across several months. Each region's data is separated into individual files, with up to 200 trending videos being highlighted daily.

Key Data Points:
- Video title
- Channel title
- Publication time
- Tags
- Views, likes, and dislikes
- Description
- Comment count
- Category_id (associated with a region-specific JSON file)

Dataset can be accessed [here](https://www.kaggle.com/datasets/datasnaek/youtube-new).

---

**Note**: Ensure you've acquired the necessary permissions and complied with terms of service when utilizing datasets and services.
