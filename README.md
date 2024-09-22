# Amazon E-Commerce Sales Analysis

## Overview

This project analyzes a comprehensive dataset of Amazon e-commerce sales in India, consisting of over **110,000 orders**. The objective is to identify key factors influencing sales performance and consumer behavior through data analysis and statistical evaluation.

## Dataset

The dataset includes the following attributes:
- **Order Status**
- **Order ID**
- **Amount Paid**
- **B2B/B2C Type**
- **Order Date**
- **Seller (Amazon or Other)**

The data was pre-processed by removing canceled orders and encoding categorical variables to facilitate correlation analysis. The dataset can be accessed [here](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data).

## Key Findings

- **Seasonal Trends**: Revenue in **June** was significantly higher than in **April**, indicating a peak during the summer months.
- **B2C vs. B2B**: B2C sales revenue was significantly greater than B2B, despite B2B having a higher average order amount.
- **Correlation Analysis**: The most correlated factors to revenue were identified as the **month** and **B2B/B2C classification**.

## Methodology

1. **Data Cleaning**: Canceled orders were removed to ensure accurate revenue analysis.
2. **Statistical Analysis**: T-tests were conducted to assess differences in revenue between groups.
3. **Visualization**: Data was visualized using Matplotlib to compare total sales, average revenue, and total revenue for B2B and B2C segments.

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook
