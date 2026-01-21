# Bike Sales Data Analysis – Exploratory Data Analysis (EDA) with Pandas
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yusufKh7-ctrl/Bike-Sales/blob/main/Bike_sales.ipynb)
A comprehensive **Exploratory Data Analysis (EDA)** project on bike sales data (113,036 records) using Python and Pandas. The dataset contains detailed sales transactions including customer demographics, product information, order quantities, costs, profits, and revenue across multiple years and countries.

## Project Overview

This project demonstrates practical data cleaning, transformation, aggregation, visualization, and business insights extraction using:

- Pandas for data manipulation
- Matplotlib & Seaborn for visualization
- Basic statistical analysis and correlation

Main questions answered in this analysis:

- What is the total revenue, profit, and cost?
- How do sales trends look over the years (2011–2016)?
- Which countries generate the most revenue?
- Which age groups and genders contribute most to sales?
- What are the seasonal patterns (sales by month)?
- Is there a relationship between order quantity and profit/revenue?

## Dataset

- **Source**: Adapted from FreeCodeCamp Pandas Real-Life Example dataset  
  Raw CSV: https://raw.githubusercontent.com/ine-rmotr-curriculum/FreeCodeCamp-Pandas-Real-Life-Example/master/data/sales_data.csv
- **Rows**: 113,036
- **Columns**: 18
- **Time period**: 2011–2016
- **Key fields**: Date, Customer_Age, Age_Group, Customer_Gender, Country, Product_Category, Order_Quantity, Unit_Cost, Unit_Price, Profit, Revenue

## Key Findings (Highlights)

- **Total Revenue**: $85,271,008  
- **Total Profit**: $32,221,100  
- **Top Revenue Year**: 2015 (~$20M)
- **Top Revenue Country**: United States (~$28M) → followed by Australia
- **Top Age Group**: Adults (35–64) → ~50% of revenue
- **Gender Split**: Males slightly higher revenue than females
- **Strongest correlation**: Profit & Revenue (r = 0.957)
- **Peak sales months**: December, June, May
- **Weak negative correlation**: Order Quantity ↔ Profit / Revenue (bulk orders don't always mean higher margin)

## Technologies & Libraries

- Python 3.8+
- pandas
- matplotlib
- seaborn
- jupyter / Google Colab (recommended)

## Project Structure

```text
bike-sales-eda/
├── bike_sales_analysis.ipynb     ← Main Jupyter Notebook with full analysis
├── README.md                     ← This file
├── requirements.txt              ← (optional) list of dependencies
└── images/                       ← (optional) exported charts
    ├── revenue_by_year.png
    ├── revenue_by_country.png
    └── age_distribution.png
