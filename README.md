# Retail Sales Analysis 2019

## Overview

This project analyzes 2019 retail sales data to identify patterns in sales performance across time and geographic markets. Twelve monthly sales datasets were combined, cleaned, and analyzed using Python.

The analysis focuses on two business questions:

1. Which month generated the highest sales revenue?
2. Which city generated the highest sales revenue?

## Key Findings

- **December** generated the highest monthly sales revenue at approximately **$4.61 million**.
- **San Francisco** generated the highest sales revenue among the cities analyzed at approximately **$8.25 million**.

## Analysis Process

- Combined 12 monthly CSV files into a single dataset.
- Inspected and cleaned missing and duplicate records.
- Converted quantity and price fields to numeric values.
- Created month and city features from transaction data.
- Calculated sales revenue using quantity ordered and unit price.
- Aggregated revenue by month and city.
- Visualized sales performance using bar charts.

## Tools & Technologies

- **Python**
- **pandas**
- **Matplotlib**
- **Jupyter Notebook**

## Repository Structure

```text
Retail-Sales-Analysis-for-the-year-of-2019/
│
├── README.md
│
├── data/
│   ├── README.md
│   ├── Sales_January_2019.csv
│   ├── Sales_February_2019.csv
│   ├── Sales_March_2019.csv
│   ├── Sales_April_2019.csv
│   ├── Sales_May_2019.csv
│   ├── Sales_June_2019.csv
│   ├── Sales_July_2019.csv
│   ├── Sales_August_2019.csv
│   ├── Sales_September_2019.csv
│   ├── Sales_October_2019.csv
│   ├── Sales_November_2019.csv
│   └── Sales_December_2019.csv
│
└── notebooks/
    ├── README.md
    └── retail_sales_analysis.ipynb
```

## Dataset

The analysis uses 12 monthly retail sales files covering transactions from January through December 2019. The combined raw dataset contains approximately **186,850 records** and includes order ID, product, quantity ordered, price, order date, and purchase address. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

## Results

## Dataset

The analysis uses 12 monthly retail sales files covering transactions from January through December 2019. The combined raw dataset contains approximately **186,850 records** and includes order ID, product, quantity ordered, price, order date, and purchase address.

## Results

The analysis identified **December as the strongest month for sales**, generating approximately **$4.61 million in revenue**.

At the geographic level, **San Francisco generated the highest sales revenue**, at approximately **$8.25 million**.
