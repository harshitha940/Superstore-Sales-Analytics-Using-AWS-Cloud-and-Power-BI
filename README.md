# Superstore-Sales-Analytics-Using-AWS-Cloud-and-Power-BI
Superstore Sales Analytics is a cloud-based data analytics project designed to analyze sales, profit, customers, products, and regional performance using AWS Cloud and Power BI. The project demonstrates an end-to-end data analytics workflow, from data storage and ETL processing to SQL analysis and interactive dashboard creation.
# Superstore Sales Analytics Using AWS Cloud and Power BI

## 📌 Project Overview

Superstore Sales Analytics is an end-to-end cloud-based data analytics project developed to analyze sales, profit, customers, products, categories, and regional performance.

The project uses AWS Cloud services for data storage, data cataloging, and SQL analysis, followed by Power BI for data transformation, DAX calculations, visualization, and dashboard development.

## 🎯 Project Objective

The main objective of this project is to build a complete data analytics pipeline that transforms raw Superstore sales data into meaningful business insights using AWS Cloud and Power BI.

## 🛠️ Tools & Technologies

- Amazon S3
- AWS IAM
- AWS Glue
- AWS Glue Crawler
- AWS Glue Data Catalog
- Amazon Athena
- SQL
- Simba Amazon Athena ODBC
- Power BI
- Power Query
- DAX

## 🔄 Project Workflow

Superstore CSV  
↓  
Amazon S3  
↓  
AWS IAM  
↓  
AWS Glue Database  
↓  
AWS Glue Crawler  
↓  
AWS Glue Data Catalog  
↓  
Amazon Athena  
↓  
SQL Analysis  
↓  
Simba Amazon Athena ODBC  
↓  
Power BI  
↓  
Power Query & DAX  
↓  
Interactive Dashboard

## ☁️ AWS Cloud Process

### 1. Amazon S3
The Superstore CSV dataset is uploaded and stored in an Amazon S3 bucket.

### 2. AWS IAM
IAM is used to manage AWS users, roles, and permissions required for accessing AWS services.

### 3. AWS Glue Database
A Glue database is created to organize and manage the metadata of the Superstore dataset.

### 4. AWS Glue Crawler
The Glue Crawler scans the dataset stored in S3 and automatically identifies the schema, columns, and data types.

### 5. AWS Glue Data Catalog
The crawler stores the discovered metadata in the AWS Glue Data Catalog.

### 6. Amazon Athena
Athena is used to query and analyze the Superstore data directly from Amazon S3 using SQL.

## 📊 Power BI Process

The data from Amazon Athena is connected to Power BI using the Simba Amazon Athena ODBC driver.

Power Query is used for data cleaning and transformation, while DAX is used to create calculated measures and KPIs.

## 📈 Dashboard Analysis

The Power BI dashboard analyzes:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Sales by Category
- Sales by Sub-Category
- Sales by Region
- Sales by State
- Monthly Sales Trends
- Profit Analysis
- Top Products
- Customer Segment Performance
- Discount Analysis
- Shipping Analysis

## 💡 Key KPIs

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Average Sales
- Average Discount
- Profit Margin

## 🧮 DAX

DAX measures are created in Power BI to calculate business KPIs and support interactive dashboard analysis.

Example:

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Quantity = SUM(Superstore[Quantity])

Average Discount = AVERAGE(Superstore[Discount])
