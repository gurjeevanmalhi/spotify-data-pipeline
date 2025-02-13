# Spotify ETL Data Pipeline | Python & AWS

# Introduction
End-to-end data pipeline leveraging Python and AWS to extract, transform, and analyze Spotify data with seamless automation and cloud scalability.

# Architecture
<img width="1668" alt="ETL Diagram" src="https://github.com/user-attachments/assets/02ba7763-ac51-46ec-8091-7f098dbfcdc5" />

# Technology Used
- Python: Programming language
- AWS Lambda: To automate data extraction and transformation processes.
- AWS S3: For scalable and organized data storage.
- AWS Glue: For schema definition and creating analytics tables.
- AWS Athena: For querying and analyzing transformed data.
- Jupyter Notebook: For prototyping and demonstrating the pipeline functionality.
- Visual Studio Code: As the primary development environment.

# Data Extraction
- Integration with the Spotify API to extract data such as tracks, artists, playlists, and more.
- Automated data extraction deployed on AWS Lambda for serverless execution.
- Configured triggers to schedule regular data extraction automatically.

# Data Transformation
- Developed a Python function for cleaning and transforming raw data into structured formats.
- Automated the transformation process with AWS Lambda and event-based triggers.

# Data Storage
- Properly organized and stored data files in AWS S3 buckets for scalability and reliability.

# Analytics and Querying
- Built analytics tables on transformed data files using AWS Glue for schema definition.
- Queried data efficiently with AWS Athena to enable advanced analysis and insights.

# Setup and Deployment

- Clone this repository.
- Configure access to the Spotify API by creating a client ID and client secret.
- Deploy AWS Lambda functions using the provided Python scripts: spotify_api_data_extract.py for data extraction. spotify_transformation_load_function.py for transformation and loading.
- Set up triggers for Lambda functions using AWS EventBridge.
- Create an S3 bucket and specify the paths for data storage.
- Define tables in AWS Glue and query the data with Athena.

# Files
- data_extract.ipynb – Notebook for Spotify API integration and initial testing.
- Spotify Data Pipeline Project.ipynb – Full pipeline demonstration in a Jupyter Notebook.
- spotify_api_data_extract.py – Lambda function script for data extraction.
- spotify_transformation_load_function.py – Lambda function script for data transformation and loading.

# Future Enhancements
- Expand data extraction to include additional Spotify API endpoints.
- Implement real-time data streaming for near-instant analytics.
- Add dashboard visualizations using tools like Tableau or Power BI.
