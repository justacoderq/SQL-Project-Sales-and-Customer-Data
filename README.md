# Sales and Customer Data Analysis

## Overview
This project involves analyzing sales and customer data using SQL. The data includes information on customers' age, gender, product type, payment methods, and shopping mall locations. The analysis aims to answer business-related questions such as total revenue generation, popular products, and customer purchasing behavior.

## Dataset
The dataset contains two tables:
1. **Customer Data** - Includes customer demographics like age, gender, and payment method.
2. **Sales Data** - Contains information on product categories, quantities sold, prices, and sales locations.

## Project Structure
- **Data Exploration**: Initial exploration of sales and customer tables to assess the data structure and content.
- **Data Cleaning**: Join the customer and sales data into a consolidated table for further analysis.
- **Data Analysis**: SQL queries to extract insights related to sales, revenue, and customer behavior.

## Tools Used
- **SQL**: Queries to perform data analysis.
- **Kaggle**: Dataset sourced from Kaggle.
- **Google BigQuery**: Used for running SQL queries and managing data.

## Analysis Steps

### 1. Data Exploration
Initial exploration of the customer and sales data to understand the fields and check for any data quality issues such as duplicates or missing values.

### 2. Data Cleaning
Joining the sales and customer data into a combined table named `sales_customer_data`. This included:
- Adding a computed `total_price` column (price * quantity).
- Verifying there were no duplicate rows in the sales data.
- Checking for null values in the newly created columns.

### 3. Data Analysis
Key questions answered include:

- **Total Revenue Generated**: Calculating the total sales revenue for the year 2022.
- **Most Popular Product Category**: Determining which product categories sold the most units.
- **Top Shopping Malls by Revenue**: Identifying the top three malls with the highest sales revenue.
- **Gender Distribution in Purchases**: Analyzing how gender influences purchasing patterns across different product categories.
- **Age Distribution and Payment Preferences**: Analyzing how different age groups prefer different payment methods.

## Key Findings

- **Total Revenue in 2022**: $115,436,814.08.
- **Most Popular Product Category**: 'Clothing' with 103,558 units sold.
- **Top Three Shopping Malls by Revenue**:
  1. Mall of Istanbul: $50,872,481.68
  2. Kanyon: $50,554,231.10
  3. Metrocity: $37,302,787.33
- **Gender Distribution**: Females purchased more than males in all product categories, particularly in 'Clothing' and 'Cosmetics'.
- **Age and Payment Methods**:
  - Age group 26-50 prefers using Cash, followed by Credit Cards.
  - Age group 51-75 shows a similar trend, with Cash as the dominant payment method.
  - Age group 0-25 also leans towards Cash, followed by Credit Cards.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sales-customer-data-analysis.git
