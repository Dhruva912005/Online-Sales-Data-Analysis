# 📊 Online Sales Data Analysis

## Overview

This project performs Exploratory Data Analysis (EDA) on an online sales dataset containing 240 transactions across multiple product categories, regions, and payment methods. The objective is to uncover business insights related to sales performance, customer purchasing behavior, revenue trends, and regional market distribution.

The analysis was conducted using Python, Pandas, NumPy, Matplotlib, and Seaborn. The project not only analyzes sales performance but also provides business and marketing recommendations based on data-driven insights.

## Dataset Information

* Total Records: 240
* Total Columns: 9
* Missing Values: None
* Unique Transactions: 240
* Unique Product Categories: 6
* Unique Products: 232
* Regions: 3 (Asia, Europe, North America)
* Payment Methods: 3 (Credit Card, PayPal, Debit Card)

### Features

* Transaction ID
* Date
* Product Category
* Product Name
* Units Sold
* Unit Price
* Total Revenue
* Region
* Payment Method

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analysis Performed

### Data Quality Assessment

* Checked data types
* Verified missing values
* Duplicate value analysis
* Unique value analysis

### Statistical Analysis

* Mean, Median, Minimum, Maximum
* Standard Deviation
* Revenue Distribution
* Units Sold Analysis

### Business Analysis

* Product Category Analysis
* Monthly Revenue Trends
* Regional Revenue Analysis
* Payment Method Distribution
* Product Performance Analysis
* Correlation Analysis

## Key Insights

### Sales Performance

* Average units sold per transaction: 2.16
* Average unit price: 236.40
* Average revenue per transaction: 335.70
* Maximum revenue recorded: 3899.99

### Monthly Revenue Trends

* January generated the highest revenue (14,548.32).
* July recorded the lowest revenue (6,797.08).
* Sales were strongest during the first four months of the year.

### Product Category Analysis

* Electronics was the highest revenue-generating category.
* Home Appliances peaked in March.
* Books generated the lowest revenue overall.
* Different categories exhibited different seasonal demand patterns.

### Regional Analysis

* North America: 36,844.34
* Asia: 22,455.45
* Europe: 21,268.06

North America emerged as the strongest-performing region, contributing nearly 46% of total revenue.

### Payment Method Analysis

* Credit Card: 50.0%
* PayPal: 33.3%
* Debit Card: 16.7%

Credit Card was the most preferred payment method among customers.

### Product Performance

* Garmin Forerunner 945 generated the highest revenue among the most frequently purchased products.
* Most products appeared only once in the dataset, indicating a highly diverse product portfolio.

### Correlation Analysis

* Unit Price and Total Revenue showed a strong positive correlation (r = 0.93).
* Units Sold had a relatively weak impact on overall revenue compared to pricing strategy.

## Marketing Strategy Recommendations

The insights derived from this analysis can be used to support business and marketing decisions:

* Focus marketing efforts on Electronics, as it is the highest revenue-generating product category.
* Increase promotional activities in North America, the most profitable region contributing nearly 46% of total revenue.
* Plan seasonal campaigns during January and March, which recorded strong sales performance.
* Develop region-specific marketing strategies based on product category distribution.
* Encourage Credit Card payments through discounts, cashback offers, and loyalty programs, as it is the most preferred payment method.
* Promote high-performing products and identify opportunities to increase repeat purchases.
* Optimize pricing strategies, as Unit Price has a strong positive correlation with Total Revenue.
* Explore growth opportunities in lower-performing regions and product categories to improve overall business performance.

## Project Structure

├── Online Sales Data.csv
├── Online Sales Data Analysis.ipynb
├── Online Sales Data Report.pdf
├── README.md

## Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can transform raw sales data into meaningful business insights. By analyzing revenue trends, customer preferences, product performance, and regional sales patterns, organizations can make informed decisions regarding marketing strategies, pricing policies, inventory management, and business expansion. The findings highlight the importance of data-driven decision-making in improving sales performance and maximizing revenue.

## Author

**Dhruva Jain**
B.Tech Mathematics & Computing
Aspiring Data Analyst | Exploring Data, Markets & Business
