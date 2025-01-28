# spotify-data-pipeline
Contains code for ETL pipeline for Spotify data using Python in Visual Studio Code, AWS Glue for data transformation, Athena for querying, and S3 for storage. This project showcases cloud-native data processing and analytics.

Spotify Data Pipeline

This repository contains an end-to-end automated data pipeline designed to extract, transform, and analyze data from the Spotify API. By leveraging AWS cloud services and Python, this project demonstrates efficient data engineering practices to process and analyze streaming data.

Features

1. Data Extraction
Integration with the Spotify API to extract data such as tracks, artists, playlists, and more.
Automated data extraction deployed on AWS Lambda for serverless execution.
Configured triggers to schedule regular data extraction automatically.

3. Data Transformation
Developed a Python function for cleaning and transforming raw data into structured formats.
Automated the transformation process with AWS Lambda and event-based triggers.

5. Data Storage
Properly organized and stored data files in AWS S3 buckets for scalability and reliability.

7. Analytics and Querying
Built analytics tables on transformed data files using AWS Glue for schema definition.
Queried data efficiently with AWS Athena to enable advanced analysis and insights.
Architecture Diagram

Setup and Deployment

Clone this repository.
Configure access to the Spotify API by creating a client ID and client secret.
Deploy AWS Lambda functions using the provided Python scripts:
spotify_api_data_extract.py for data extraction.
spotify_transformation_load_function.py for transformation and loading.
Set up triggers for Lambda functions using AWS EventBridge.
Create an S3 bucket and specify the paths for data storage.
Define tables in AWS Glue and query the data with Athena.
Files

data_extract.ipynb – Notebook for Spotify API integration and initial testing.
Spotify Data Pipeline Project.ipynb – Full pipeline demonstration in a Jupyter Notebook.
spotify_api_data_extract.py – Lambda function script for data extraction.
spotify_transformation_load_function.py – Lambda function script for data transformation and loading.
Future Enhancements

Expand data extraction to include additional Spotify API endpoints.
Implement real-time data streaming for near-instant analytics.
Add dashboard visualizations using tools like Tableau or Power BI.
