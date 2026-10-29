# E-Commerce Sales Dashboard - Power BI

An interactive sales analysis dashboard built in Power BI Desktop to analyze e-commerce performance across regions, product categories, and customer segments.

## Dashboard Preview

![E-Commerce Sales Dashboard](screenshots/dashboard_preview.jpg)

## About the Project

This project explores sales performance, profitability, and customer trends using the popular Superstore Sales dataset from Kaggle. The analysis includes regional breakdown, monthly sales trends, and category performance to help identify high-margin products and growth opportunities.

## Data Source

Dataset: [Superstore Sales Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The `data/sales_data.csv` file contains the complete Superstore dataset (9,994 records across 4 years of retail transactions).

## Tools Used

- Power BI Desktop (Dashboard design & interactive visuals)
- Power Query (Data cleaning, formatting, and date transformations)
- DAX (Calculated measures: Total Sales, Total Profit, Profit Margin %, Order Count)
- Microsoft Excel (Data validation and summary analysis - `Superstore_Analysis.xlsx`)

## Key Insights Covered

- Total sales, total profit, and overall profit margin
- Month-over-month sales trends and seasonality patterns
- Category & Sub-Category profitability (Technology, Furniture, Office Supplies)
- Regional performance breakdown (Central, East, South, West)
- Customer segment distribution (Consumer, Corporate, Home Office)

## Project Structure

```
ECommerce-Sales-Dashboard-PowerBI/
|-- data/
|   |-- sales_data.csv
|-- screenshots/
|   |-- dashboard_preview.jpg
|-- Superstore_Analysis.xlsx
|-- README.md
```

## Note

The dashboard screenshot above shows the final visual output designed in Power BI. You can also review `Superstore_Analysis.xlsx` in this repo for the summary tables, KPI calculations, and chart representations.
