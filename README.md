# Power BI Sales Analytics Dashboard

## Project Overview
This project demonstrates an end-to-end sales analytics workflow using Microsoft Power BI. It explores synthetic sales data to analyze sales performance, customer behavior, product performance, and regional trends.

The project was developed as a Data Analyst portfolio project to practice data cleaning, data modeling, DAX, and interactive reporting.

> **Disclaimer:** This project uses synthetic practice data. It is not based on real EY data, client information, or confidential business records.

## Tools & Technologies
- Microsoft Power BI Desktop
- Power Query
- DAX
- Excel
- GitHub

## Dataset
The dataset contains simulated sales transactions and related customer and product information.

Tables used:
- **Sales:** Transaction details, dates, quantities, sales amounts, and order status
- **Customers:** Customer information and region
- **Products:** Product details and categories

## Data Cleaning & Transformation
Performed using Power Query:
- Corrected date data types
- Handled missing values
- Standardized payment mode values
- Trimmed and cleaned text
- Checked duplicates
- Investigated unusual quantity values

## Data Modeling
Created relationships between:
- Sales and Customers
- Sales and Products
- Sales and DateTable

The model follows a star-schema-style structure with Sales as the fact table and Customers, Products, and DateTable as dimensions.

## Key DAX Measures
- Total Sales
- Total Quantity
- Total Orders
- Average Order Value
- Returned Orders
- Return Rate
- Sales YTD
- Sales Previous Year
- Sales YoY Growth %
- Sales All Regions

## Dashboard Features
- KPI cards
- Sales by product category
- Sales trend over time
- Region slicer
- Order status slicer
- Date slicer
- Year-to-date analysis
- Year-over-year growth analysis

## Key Learning Outcomes
- Data cleaning using Power Query
- Data modeling and relationships
- DAX measures and filter context
- Time intelligence calculations
- Interactive dashboard design
- Row-Level Security concepts

## Project Structure
```text
PowerBI-Sales-Analytics/
├── PowerBI/
│   └── Sales_Analytics_Dashboard.pbix
├── Dataset/
│   └── Practice_Sales_Dataset.xlsx
├── Screenshots/
│   └── Dashboard.png
└── Documentation/
    ├── Data_Cleaning.md
    └── DAX_Measures.md
```

## Future Improvements
- Add more business KPIs
- Improve dashboard design
- Practice dynamic Row-Level Security
- Add SQL-based analysis
- Explore advanced time-intelligence measures

## Author
Data Science Student | Aspiring Data Analyst
