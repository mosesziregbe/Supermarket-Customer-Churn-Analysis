 Supermarket Customer Churn Analysis

## Introduction

This project analyzes customer data from a supermarket chain to understand factors influencing customer churn. By examining customer demographics, purchase behavior, and loyalty indicators across different branches and product categories, we aim to provide insights that can help improve customer retention strategies.

Churn refers to the rate at which customers stop doing business with a company over a given period. In this supermarket analysis, churn is identified when a customer ceases to make purchases. Understanding churn is crucial as it directly impacts revenue and growth. By analyzing factors contributing to churn, such as demographics, purchasing behavior, and customer satisfaction, the supermarket can develop targeted strategies to improve retention and reduce customer attrition.

## Data Description

The dataset contains 10,000 rows of raw customer data showing detailed information on customer transactions and characteristics, including:

- Customer demographics (age, gender, credit score)
- Membership status and activity
- Transaction details (products purchased, amounts, ratings)
- Branch information
- Churn status

Key fields include:

- `id`: Unique identifier for each transaction
- `branch`: Location of the supermarket (Houston, Dallas, San Antonio)
- `customer_type`: Type of customer (Normal/Member)
- `product_category`: Category of products purchased
- `total_amount`: Total amount of the transaction including tax
- `customer_churn`: Whether the customer has churned (1) or not (0)

## Tools Used

- Power BI: For data visualization and dashboard creation
- DAX (Data Analysis Expressions): For creating calculated measures and columns

## Visualization

The project includes a comprehensive Power BI dashboard with two main pages:

1. Overview Page: Provides a high-level summary of key metrics and trends.
2. Customer Churn Analysis Page: Offers detailed insights into churn factors and customer segments.

The dashboard is interactive, allowing users to filter data by various dimensions such as branch, product category, and customer type.

[Link to Power BI Dashboard]

## Key Findings

### Overview Page

### Churn Rate and Customer Retention
- **Overall Churn Rate**: 20.37%, with 2,037 customers churned out of a total of 10,000.
- **Member Retention**: 79.3% of members are retained (3,964 members), while 20.7% have churned (1,046 members).
- **Regular Customers (Non-Members)**: 80.1% retention rate, with 3,999 retained and 991 churned.

### Financial Performance
- **Total Revenue**: $3.2 million across all branches.
- **Total Transactions**: 10,000 transactions recorded.
- **Total Quantity Sold**: 55,100 units sold.
- **Average Customer Rating**: 7.0 out of 10, indicating moderate customer satisfaction.

### Revenue Breakdown by Branch
- **Dallas**: Highest revenue at $1.11 million.
- **Houston and San Antonio**: Both branches generated $1.06 million in revenue.

### Revenue Breakdown by Product Category
- **Top Category**: Food and beverages generate the most revenue at $0.56 million.
- **Second Category**: Sports and travel closely follows with $0.55 million.
- **Other Categories**: Revenue from electronic accessories, fashion accessories, home and lifestyle, and health and beauty categories is relatively evenly distributed.

### Churn Analysis by Credit Score
- **Churn by Credit Score**: Customers with poor credit scores exhibit the highest churn rates, while those with excellent credit scores show the lowest churn rates.

### Branch Performance Insights
- A performance table details total revenue, average transaction value, average rating, and churn rate for each branch and product category.
- Notably, while Dallas has the highest total revenue, it also experiences a higher churn rate in certain categories.


