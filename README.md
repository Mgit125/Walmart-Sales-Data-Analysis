# Walmart-Sales-Data-Analysis

## About the Project
This project explores Walmart sales data to uncover insights into top-performing branches, product trends, and customer behavior. The analysis aims to provide actionable strategies for branch performance improvement and enhanced customer targeting.
##Purpose of the Project
The main objective is to analyze Walmart's sales data to identify various factors influencing branch performance and suggest actionable strategies for improvement.
## Dataset Overview

Source: Kaggle Walmart Sales Forecasting(https://github.com/Princekrampah/WalmartSalesAnalysis/blob/master/SQL_queries.sql)

Description: Sales transactions from three Walmart branches in Myanmar

Branches: Mandalay, Yangon, Naypyitaw

Size: Columns: 17, Rows: 1,000

## Steps for Analysis

### Step 1: Product Analysis

Goals:

Analyze the performance of different product lines.

Identify:

Top-performing product lines.

Underperforming product lines requiring improvement.

Use bar charts and pie charts for visualization.

### Step 2: Sales Analysis

Goals:

Examine sales trends across product lines.

Analyze monthly and seasonal sales data to measure strategy effectiveness.

Evaluate the impact of sales promotions or events on revenue.

Use time-series charts to illustrate trends and patterns.

### Step 3: Customer Analysis

Goals:

Segment customers based on:

Purchase behavior.

Demographic information.

Identify profitable customer segments and trends in customer purchases.

Analyze gender-wise or customer type-wise profitability.

Visualize findings using clustered bar charts or heatmaps.

## Approach Used

### 1. Data Wrangling

Inspected the dataset for missing or NULL values.

Ensured data integrity by applying the following steps:

Built a database.

Created tables and inserted the data.

Verified columns for NULL values:

All fields were set to NOT NULL during table creation, ensuring data quality.


### 2. Feature Engineering

Generated new columns for deeper insights:

time_of_day: Categorized transactions into Morning, Afternoon, and Evening.

day_name: Extracted the day of the week (e.g., Mon, Tue).

month_name: Extracted the month (e.g., Jan, Feb).

### 3. Exploratory Data Analysis (EDA)

Conducted in-depth analysis to answer the project objectives:

Identified top-performing branches and product lines.

Analyzed customer behavior and purchase trends.

Visualized sales and profit patterns across time periods.




