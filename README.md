# Retail Sales Data Analysis

## Overview

This project analyzes retail sales data to uncover patterns in customer demographics, product sales performance, and shopping behavior over time. The goal is to extract actionable insights to help improve business strategies.

## Dataset

The dataset contains transactional retail sales data, including customer age and gender, product categories, quantities sold, prices, and dates of purchase.

## Key Steps

1. Data Cleaning and Preparation  
   - Standardized column names  
   - Converted date fields to Date format  
   - Imputed missing values  
   - Encoded categorical variables for analysis

2. Feature Engineering  
   - Created new variables such as revenue and transaction month/day  
   - Extracted day of the week to analyze temporal trends

3. Exploratory Data Analysis (EDA)  
   - Visualized customer age distribution  
   - Analyzed sales by product category  
   - Examined average spend by gender  
   - Investigated sales patterns across days of the week

## Key Insights

- **Customer Age:** Customers aged **45-55** form the largest group, highlighting a key demographic segment.  
- **Product Performance:**  
  - **Electronics** generate the highest revenue overall.  
  - **Beauty products** sell in greater quantities, indicating popularity but lower price points.  
- **Sales Timing:** There is a noticeable **spike in sales during weekends**, reflecting strong weekend shopping behavior.  
- **Gender Spending:** Male and female customers spend **similarly on average** per transaction, showing comparable purchasing behavior.

## How to Use

Run the R notebook (`.ipynb` or `.Rmd`) step-by-step to replicate the analysis and visualizations. Ensure the following packages are installed: `tidyverse`, `lubridate`, and `ggplot2`.

## Author

Aman Hatmode

---

Feel free to explore, contribute, or open issues for discussion.
