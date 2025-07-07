# Real-Time-Weather-Data-Pipeline-with-AWS-and-Snowflake


This project is all about building a real-time data pipeline that collects weather data from an external API and makes it ready for analysis in Snowflake — all using AWS cloud services. The goal is to make data flow automatically, securely, and efficiently without manual work.


# What This Project Does

- Pulls live weather data from a public Weather API.

- Uses AWS Lambda to process and manage data automatically.

- Stores the data in Amazon DynamoDB with change tracking.

- Streams changes from DynamoDB to Amazon S3.

- Uses Snowpipe to load that data into Snowflake in real-time.

- Makes weather data ready for analysis, dashboards, or business insights.


# Why I Built This

I wanted to explore how cloud technologies can work together to create smart, automated workflows. This pipeline shows how real-time data can be collected, processed, stored, and analyzed without needing to run any servers manually. It’s useful for anything from weather dashboards to climate studies.


# Technologies Used

AWS Lambda – for running code without managing servers

Amazon EventBridge – for scheduling and triggering tasks

Amazon DynamoDB – to store weather data quickly and efficiently

DynamoDB Streams – to detect changes in the data

Amazon S3 – to store processed files

Snowflake & Snowpipe – to load and query the data in real-time

Weather API – as the external data source
