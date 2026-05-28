# Sales Data Cleaning 2019-2020

## Project Overview
This project involves cleaning a Sales Export dataset from 2019-2020 
using Python and Pandas.

## Dataset
- **Source:** Sales Export CSV
- **Rows:** 1,000
- **Columns:** country, order_value_eur, cost, date, category, 
customer_name, sales_manager, sales_rep, device_type, order_id

## What I Did
1. Stripped spaces and lowercased all column headers
2. Removed commas from order_value_eur and converted to float
3. Converted date column from string to datetime format
4. Standardized text values in country, category and device_type columns
5. Fixed incorrect casing for UK and PC values
6. Checked and removed duplicate rows

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Files
- `Sales-Export_2019-2020.csv` — original raw dataset
- `Sales_Cleaned.csv` — cleaned dataset
- `sales_cleaning.ipynb` — Jupyter notebook with full code
