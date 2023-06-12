# YouTube Data Analysis with AWS - ETL Pipeline using Glue

The primary goal of this project is to develop an ETL pipeline that enables data-driven decision-making for business individuals. By securely managing, streamlining, and analyzing structured and semi-structured YouTube videos, the pipeline empowers business professionals to make informed choices based on video categories and trending metrics. This data-driven approach helps optimize business strategies and drive successful outcomes in the dynamic digital landscape.

## Medium Article

You can find the detailed step-by-step guide for this project in the accompanying [Medium article](https://medium.com/@narvekar.amisha/effortlessly-analyze-your-youtube-data-with-aws-a-step-by-step-guide-to-etl-pipeline-using-glue-f98caed05977).

## Project Aim

1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services Utilized
1. **Amazon S3**: We will employ Amazon S3, a highly scalable and secure object storage service, to store and manage our data effectively.
2. **AWS IAM**: With AWS Identity and Access Management (IAM), we can securely manage access to AWS services and resources, ensuring proper authorization and authentication.
3. **QuickSight**: Amazon QuickSight, a cloud-based business intelligence service, will enable us to visualize and explore our data, providing valuable insights for data-driven decision-making.
4. **AWS Glue**: As a serverless data integration service, AWS Glue simplifies the process of discovering, preparing, and combining data for analytics, machine learning, and application development.
5. **AWS Lambda**: By leveraging AWS Lambda, we can execute code without the need for server management, enabling seamless and efficient data processing.
6. **AWS Athena**: Athena serves as an interactive query service for data stored in Amazon S3, allowing us to run queries without the need for data loading or preprocessing.

## Dataset Used
For this project, we will utilize a Kaggle dataset that contains comprehensive statistics (CSV files) on daily popular YouTube videos across various regions. Each region has its own file, providing information such as video title, channel title, publication time, tags, views, likes and dislikes, description, comment count, and category_id, which varies by region. The dataset is available at the following link: [YouTube Trending Videos Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Architecture Diagram
Below is an architecture diagram that illustrates the overall flow and interaction of the various components within our ETL pipeline. 

![Architecture Diagram](architecture.png)



## Getting Started

To get started with this project, follow the steps outlined in the Medium article. It provides a detailed guide on setting up the ETL pipeline using AWS services.

## Contributing

Contributions to this project are welcome! If you find any issues, have suggestions for improvements, or want to add new features, feel free to submit a pull request.
