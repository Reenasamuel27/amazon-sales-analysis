📊 Amazon Sales Data Analysis | Power BI

Project Overview
This Power BI project analyzes Amazon sales data to understand sales performance, customer engagement through reviews, and time-based trends.
The dashboard focuses on monthly, weekly, and category-level sales analysis, along with top-performing products using YTD metrics.

Tools & Technologies

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX (Time Intelligence Measures)

GitHub (Version Control & Project Hosting)

Data Model & Tables Used

Sales Table
Contains product-level and order-related details:

Product Category

Product Description

Price (Dollar)

Number of Reviews

Shipment

Order Date

Date Table (Created in Power BI)
Custom date table used for time-based analysis:

Date

Month Name

Month Number

Week

Quarter Number

Qtr

Calculated Measures (DAX)
The following measures were created for analysis:

YTD Sales

YTD Reviews

YTD Product Sales

QTD Sales

Dashboard Visuals & Analysis

Sales Trend Analysis

Sales by Month

Sales by Week

Category Analysis

Sales by Product Category

Top Performance Analysis

Top 5 Products by YTD Sales

Top 5 Products by YTD Reviews

Filters Used

Product Category

Quarter (Qtr)

These filters allow dynamic and interactive analysis of sales performance.

Dashboard Preview
Dashboard image is available in this repository as:
dashboard.png

Repository Structure

amazon-sales-analysis
│
├── Amazon Sales Data Analyst.pbix
├── dashboard.png
├── README.md
└── data_description.txt

How to Use This Project

Download the PBIX file

Open it in Power BI Desktop

Refresh data if required

Use slicers to explore insights interactively

Skills Demonstrated

Data modeling and relationships

Time intelligence using DAX (YTD, QTD)

Interactive dashboard development

Business-focused data analysis

GitHub documentation and version control

PowerBi service URL:https://app.powerbi.com/groups/me/reports/633f3ecf-5e3a-492e-9c51-f905464236bc/ad3a00d343a0071e8c99?experience=power-bi

Author

Reena Samuel
GitHub: https://github.com/Reenasamuel27

Email: jenisam98896@gmail.com

Power BI Analyst | Data Analyst

data_description.txt

Amazon Sales Data Analysis – Dataset & Dashboard Description

SALES TABLE

Product Category: Category of the product

Product Description: Product details

Price (Dollar): Product price in USD

Number of Reviews: Customer review count

Shipment: Shipment type or status

Order Date: Date of order placement

DATE TABLE (Created in Power BI)

Date: Calendar date

Month Name: Name of the month

Month Number: Month index (1–12)

Week: Week number

Quarter Number: Quarter index

Qtr: Quarter label (Q1, Q2, Q3, Q4)

CALCULATED MEASURES (DAX)

YTD Sales: Year-to-date sales value

YTD Reviews: Year-to-date total reviews

YTD Product Sales: Product-level YTD sales

QTD Sales: Quarter-to-date sales

DASHBOARD VISUALS

Sales by Month

Sales by Week

Sales by Product Category

Top 5 Products by YTD Sales

Top 5 Products by YTD Reviews

FILTERS / SLICERS

Product Category

Quarter (Qtr)
