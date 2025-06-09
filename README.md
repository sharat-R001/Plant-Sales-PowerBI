# Plant Sales Performance Report - Power BI Dashboard

## Project Overview

This repository contains a Power BI project focused on analyzing and visualizing plant sales performance. The report transforms raw Excel data into actionable insights using Power Query and DAX, presenting interactive visuals such as treemaps, waterfall charts, combo charts, and scatter plots with zoom capabilities.

The dashboard includes dynamic titles and conditional formatting to improve user experience, enabling detailed sales trend analysis and regional performance tracking.

## Dataset Description

The dataset consists of sales transactions and account details, with the following columns:

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| `Product_id`        | Unique identifier for each product            |
| `Sales_USD`         | Total sales amount in USD                      |
| `quantity`          | Number of units sold                           |
| `Price_USD`         | Price per unit in USD                          |
| `COGS_USD`          | Cost of Goods Sold in USD                      |
| `Date_Time`         | Transaction date and time                      |
| `Account_id`        | Unique identifier for the account              |
| `country_code`      | Country code of the account                    |
| `Account`           | Account name                                   |
| `Master_id`         | Master account identifier                      |
| `latitude2`         | Latitude coordinate of account location       |
| `longitude`         | Longitude coordinate of account location      |
| `country2`          | Country name                                   |
| `Postal_code`       | Postal/ZIP code                                |
| `street_name`       | Street name of account location                |
| `Street_number`     | Street number of account location              |
| `Product_Family`    | Product family classification                   |
| `Product_Family_Id` | Unique identifier for product family           |
| `Product_Group`     | Product group classification                    |
| `Product_Group_id`  | Unique identifier for product group             |
| `Product_Name`      | Name of the product                             |
| `Product_Name_id`   | Unique identifier for product name              |
| `Product_Size`      | Size or packaging information of the product   |
| `Product_Type`      | Type or category of the product                 |

## Features

- Data cleaning and transformation with Power Query.
- Use of virtual tables and advanced DAX measures for accurate analytics.
- Interactive visuals: treemaps, waterfall charts, combo charts, scatter plots with zoom slider.
- Dynamic report titles, axis titles, and conditional formatting.
- Drill-down and slicer functionalities for in-depth data exploration.
- Final report optimized for performance and usability.


