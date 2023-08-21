
# Walmart Ecommerce Dashboard

This repository contains the code and resources for building an Ecommerce Dashboard for Walmart using Power BI. The purpose of this project is to create an interactive dashboard that provides insights into key performance indicators (KPIs) related to Walmart's ecommerce operations.


https://github.com/kirudang/Ecom_dashboard_Walmart/assets/91911269/3d696c0e-58ef-40ed-a74d-7942ac154365

**Below are the standard steps in a BI Project**:

## Problem Statement

The goal of this project is to analyze and visualize the performance of Walmart's ecommerce business. This involves tracking various KPIs to gain insights into sales, revenue, customer behavior, and more. By creating an informative dashboard, stakeholders can make data-driven decisions to optimize the ecommerce operations.

## Define KPIs

Before proceeding, it's essential to define the KPIs that will be tracked in the dashboard. Some potential KPIs include:

- Common metrics: Sales, Orders, Average Sales per Order, Profit,...
- Time Intelligence metrics: YTD, MTD, YoY,...

## Work with Raw Data and Import Data in SQL Server

You need to import this data into a SQL Server database to facilitate efficient querying and data manipulation.
**Note**: While importing CSV files directly into Power BI is suitable for smaller datasets and quick analyses, using SQL Server as an intermediary step provides more control, efficiency, and scalability for larger and more complex projects. It also aligns with best practices for data management and analysis in enterprise settings.

## SQL Queries for KPIs

Write SQL queries to calculate the KPIs defined earlier from the imported raw data. These queries should extract, transform, and aggregate the data to generate meaningful insights. This step is to validate our results from the dashboard later on as well.

## Connecting Power BI to SQL DB

Power BI will be used to create visualizations and build the dashboard. Connect Power BI to the SQL Server database to directly import the relevant data.

## Data Modelling in Power BI

Design the data model in Power BI to establish relationships between different data tables. This will allow you to create more insightful visualizations by combining data from multiple sources.
It's advised to follow 3NF to optimize data operation. In this project, I used Star Schema to model the data relation.

## Data Cleaning using Power Query

Utilize Power Query within Power BI to clean and transform the data as needed. This step is crucial for ensuring accurate and consistent visualizations.
Power Query also offers the historical steps of data transformation, so that we could trace back as a pipeline for our work and apply the flow when new data is pouring into the server.

## KPIs Building - Measure and Time Intelligence

Create calculated measures within Power BI to compute the KPIs based on the imported data. Additionally, use Time Intelligence functions to analyze trends and patterns over time.

## Building Dashboard

Build the actual dashboard by adding various visualizations, such as charts, graphs, tables, and slicers. Arrange these elements in a user-friendly manner to convey the insights effectively.

## Export to Publish

Once the dashboard is complete, you can export it in various formats, such as PDF or PowerPoint, to share with stakeholders. Alternatively, you can publish the dashboard to the Power BI service for interactive online access.

## Conclusion

This project aims to provide a comprehensive Ecommerce Dashboard for Walmart, enabling stakeholders to monitor and analyze key performance indicators related to the ecommerce operations. Following the outlined steps will lead to the successful creation and deployment of the dashboard.

Feel free to customize the steps and details based on your project's specific requirements.
