# E-Commerce Sales Dashboard - Power BI

An interactive sales dashboard built in Power BI to analyze e-commerce performance across regions, product categories, and time periods.

## Dashboard Preview

![E-Commerce Sales Dashboard](screenshots/dashboard_preview.jpg)

## About the Project

I built this dashboard to practice end-to-end data analysis — from cleaning raw sales data to building visuals that help in decision-making. The dataset is based on the popular Superstore sales dataset available on Kaggle. I used a subset of it and adapted the region/city data for India.

## Data Source

Dataset: [Superstore Sales Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Tools Used

- Power BI Desktop
- Power Query (for data cleaning)
- DAX (for calculated measures)
- Excel / CSV (data source)

## What the Dashboard Shows

- Total sales, profit, and order count
- Month-wise sales trend
- Category and sub-category breakdown
- Region-wise performance (North, South, East, West)
- Customer segment analysis (Consumer, Corporate, Home Office)

## Project Structure

`
ECommerce-Sales-Dashboard-PowerBI/
|-- data/
|   |-- sales_data.csv
|-- screenshots/
|   |-- dashboard_preview.jpg
|-- README.md
`

## How to Use

1. Download or clone this repository
2. Open the .pbix file in Power BI Desktop
3. The data will load automatically from the CSV file
4. Use slicers to filter by region, category, or date