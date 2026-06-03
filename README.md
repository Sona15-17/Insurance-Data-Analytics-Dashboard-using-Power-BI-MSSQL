# Insurance-Data-Analytics-Dashboard-using-Power-BI-MSSQL


## Problem Statement

Insurance companies manage large volumes of policy, customer, and claim data. Analyzing this information manually can be difficult and time-consuming. There is a need for an interactive reporting solution that can provide insights into policy performance, claim activity, customer demographics, and customer feedback.

This project uses Microsoft SQL Server (MSSQL) and Power BI to transform raw insurance data into an interactive dashboard. The dashboard enables users to monitor key insurance metrics, analyze claim status, evaluate policy information, and understand customer feedback through sentiment analysis.


## Project Overview

This project focuses on analyzing insurance data using Microsoft SQL Server (MSSQL) and Power BI. The insurance dataset was imported into MSSQL Server and then connected to Power BI for data analysis and visualization.

The dashboard provides a comprehensive view of insurance policies, premium amounts, coverage amounts, claim amounts, policy status, customer demographics, and customer feedback. Various Power BI visualizations such as cards, slicers, ribbon charts, donut charts, matrix visuals, and drill-through filters were used to create an interactive reporting experience.

Additionally, sentiment analysis was performed on customer feedback using Power Query to gain insights into customer opinions and service satisfaction.


## Project Objective

The objective of this project is to analyze insurance data and develop an interactive dashboard that provides meaningful insights into policy information, claim activity, customer demographics, and customer feedback.

The project aims to:

* Import and manage insurance data using Microsoft SQL Server (MSSQL).
* Connect and transform data in Power BI.
* Monitor key insurance metrics such as Premium Amount, Coverage Amount, and Claim Amount.
* Analyze policy and claim status through interactive visualizations.
* Enable data exploration using slicers and drill-through functionality.
* Perform sentiment analysis on customer feedback using Power Query.
* Present business information in a clear and interactive dashboard for better analysis and decision-making.


## Tools & Technologies Used

| Tool / Technology            | Purpose                                    |
| ---------------------------- | ------------------------------------------ |
| Microsoft SQL Server (MSSQL) | Data storage and data management           |
| Power BI Desktop             | Data visualization and dashboard creation  |
| Power Query                  | Data transformation and sentiment analysis |
| Data Profiling               | Data quality and structure analysis        |
| SQL                          | Data retrieval and verification


## Dataset Information

The project uses an insurance dataset containing information related to insurance policies, customers, and claims.

The dataset includes details such as:

* Policy Information
* Customer Information
* Premium Amount
* Coverage Amount
* Claim Information
* Claim Status
* Customer Demographics
* Age Group Details
* Customer Feedback

The dataset was imported into Microsoft SQL Server (MSSQL) and then connected to Power BI Desktop for analysis and visualization.


## Project Workflow

The following steps were performed during the development of this project:

* Downloaded and installed Microsoft SQL Server (MSSQL).
* Imported the insurance dataset into MSSQL Server.
* Loaded the data into Power BI Desktop.
* Performed table view analysis and data profiling.
* Added slicers and text elements to improve dashboard interactivity.
* Created card visuals to display key metrics.
* Added a Multi Row Card and Ribbon Chart.
* Created a Donut Chart and Matrix Visual.
* Implemented Drill Through functionality for detailed analysis.
* Performed sentiment analysis using Power Query.
* Added sentiment analysis visuals to the report.


## SQL Implementation

Microsoft SQL Server (MSSQL) was used to create the database and store the insurance dataset before connecting it to Power BI Desktop.

### Database Creation

```sql
CREATE DATABASE Insurancedb;
```

### Data Verification

```sql
SELECT *
FROM [dbo].[InsuranceData];
```

The dataset was successfully imported into MSSQL Server and verified before being loaded into Power BI for further analysis and visualization.



## Dashboard Features

The Power BI dashboard includes the following features:

* Interactive slicers for filtering and exploring insurance data.
* Card visuals to display important insurance metrics.
* Multi Row Card for summarizing multiple data points.
* Ribbon Chart for comparative analysis.
* Donut Chart for visual representation of categorical data.
* Matrix Visual for detailed data summarization.
* Drill Through functionality for deeper data exploration.
* Sentiment Analysis visuals to analyze customer feedback.
* Interactive dashboard design for easy navigation and reporting.



## Key Performance Indicators (KPIs)

The dashboard tracks the following key performance indicators:

* Premium Amount
* Coverage Amount
* Claim Amount

These metrics provide a quick overview of insurance-related performance and claim information.



## Dashboard Screenshots

### Page 1 – Insurance Overview Dashboard

This page provides an overview of insurance data, including Premium Amount, Coverage Amount, Claim Amount, policy status, claim status, and age group analysis.

<img width="1612" height="754" alt="Image" src="https://github.com/user-attachments/assets/f494e6b6-56fb-4de4-bae9-a6afa0e257bb" />

### Page 2 – Insurance Data View

This page presents detailed insurance records, allowing users to explore policy, customer, and claim-related information.

<img width="1613" height="753" alt="Image" src="https://github.com/user-attachments/assets/3aba2978-04d1-4666-a719-ef3803063ec2" />

### Page 3 – Customer Feedback & Sentiment Analysis

This page focuses on customer feedback analysis and sentiment evaluation using Power Query, helping users understand customer opinions and areas for improvement.

<img width="1613" height="744" alt="Image" src="https://github.com/user-attachments/assets/61a69232-f393-484c-a692-a2fa72712cb4" />


## Conclusion

This project demonstrates the integration of Microsoft SQL Server (MSSQL) and Power BI for insurance data analysis and visualization. The insurance dataset was imported into MSSQL Server, connected to Power BI, and transformed into an interactive dashboard using various visualizations and filtering techniques.

The dashboard enables users to explore insurance-related information, including premium amount, coverage amount, claim amount, policy status, claim status, customer demographics, and customer feedback. In addition, sentiment analysis was performed using Power Query to analyze customer feedback and enhance reporting capabilities.

Overall, this project highlights the use of data analytics and visualization techniques to present insurance data in an interactive and meaningful manner.


## Files Included

This repository contains the following files:

* Insurance Dashboard.pbix
* SQL Script.sql
* Dashboard Screenshots
* README.md

