Full-Spectrum Snowflake Warehouse for Business Intelligence using DBT
This repository is home to the "Full-Spectrum Snowflake Warehouse for Business Intelligence" project, an initiative designed to leverage the Chinook Database to build a robust Data Warehouse optimized for insightful analytics. The project employs Kimball Methodology, combining the power of Snowflake for data warehousing with DBT for seamless data transformation, and PowerBI for intuitive reporting.

Project Overview
The goal of this project was to create a dimensional model to enable sophisticated Business Intelligence (BI) processes. Utilizing Azure Storage for data extraction, we employed DBT Cloud for performing low-latency transformations. The culmination of this work is a series of modular DBT models, executed within Snowflake, and reported on with PowerBI.

Business Processes
We targeted three key business questions:

Revenue Analysis: Analyzing total revenue and identifying key contributing factors such as customer demographics and peak sales periods.
Sentiment Analysis: Understanding the influence of regions on track sentiment within genres, along with tracking genre popularity.
Storage Analysis: Investigating the impact of track size and length on earnings and artist distribution.
Challenges
The project's main challenges included:

Establishing a connection between DBT and Snowflake.
Mastering PowerBI for KPI implementation and chart creation.
Ensuring data quality in the presence of numerous null values within the dimensions.
Outcomes and Learnings
The project was not only a practical application of data warehousing concepts but also a deep dive into ELT processes. We established Snowflake as our Data Warehouse with DBT for transformation and PowerBI for reporting, demonstrating an efficient approach to BI that yielded actionable insights across our key business questions.

Technologies
Data Warehousing: Snowflake
ETL/ELT Processes: Azure Storage, DBT
Reporting and Visualization: PowerBI

Power bi dashboard:- https://app.powerbi.com/groups/me/reports/756f89c9-acdb-41d6-8ab6-cb8aeb0e0c27/ReportSection?experience=power-bi
