# Zillow Data Analytics ETL Project

   This project demonstrates an end-to-end data engineering pipeline utilizing Apache Airflow to automate the extraction, transformation, and loading (ETL) of real estate property data from the Zillow Rapid API into AWS services.
   
![Architecture](https://github.com/user-attachments/assets/83d831c9-7e5a-43bd-b443-0740ddaf321b)

## Table of Contents

- Project Overview
- Technologies Used
- Usage

## Project Overview

- This project aims to build a robust ETL pipeline that:
- Extracts real estate data from the Zillow Rapid API.
- Loads the data into an Amazon S3 bucket.
- Triggers AWS Lambda functions to transform the data into CSV format.
- Loads the transformed data into another S3 bucket.
- Uses Apache Airflow for orchestration, including monitoring with S3KeySensor.
- Finally, connects Amazon QuickSight to visualize the data stored in Amazon Redshift.

## Technologies Used

- Apache Airflow: An open-source platform for orchestrating and scheduling workflows and data pipelines.
AWS Services:
- Amazon S3: For storing raw and transformed data.
- AWS Lambda: For executing code in response to events, specifically for data transformation.
- Amazon Redshift: A data warehouse service for storing and analyzing large datasets.
- Amazon QuickSight: A business analytics service for visualizing data.
- Python: The primary programming language used for scripting the ETL process.

## Conclusion
   This Zillow Data Analytics ETL project showcases a comprehensive approach to building a robust data pipeline using modern cloud technologies and orchestration tools. By leveraging Apache Airflow for workflow management and AWS services for data storage and analysis, the project effectively automates the extraction, transformation, and loading of real estate data from the Zillow Rapid API.
