# Walmart-Sales-Data-Analysis

![logo](https://raw.githubusercontent.com/Mgit125/Walmart-Sales-Data-Analysis/refs/heads/main/walmart%20sales.avif)

## About the Project

This project explores Walmart sales data to uncover insights into top-performing branches, product trends, and customer behavior. The analysis aims to provide actionable strategies for branch performance improvement and enhanced customer targeting.
##Purpose of the Project
The main objective is to analyze Walmart's sales data to identify various factors influencing branch performance and suggest actionable strategies for improvement.

## Dataset Overview

Source: Kaggle Walmart Sales Forecasting(https://github.com/Princekrampah/WalmartSalesAnalysis/blob/master/SQL_queries.sql)

Description: Sales transactions from three Walmart branches in Myanmar

Branches: Mandalay, Yangon, Naypyitaw

Size: Columns: 17, Rows: 1,000

![logo](https://github.com/Mgit125/Walmart-Sales-Data-Analysis/blob/main/Columns_walmart_data.png)

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

## Business Questions Answered

### General

How many unique cities does the data have?

In which city is each branch?

### Product Analysis

How many unique product lines does the data have?

What is the most common payment method?

Which product line is the best seller?

What is the total revenue by month?

Which month had the largest COGS?

Which product line generated the highest revenue?

Which city had the largest revenue?

Which product line had the largest VAT?

Classify product lines as "Good" or "Bad" based on sales.

Which branch sold more than the average number of products?

What is the most common product line by gender?

What is the average rating of each product line?

### Sales Analysis

Number of sales made during different times of the day on weekdays.

Which customer type generates the most revenue?

Which city has the largest tax percentage (VAT)?

Which customer type pays the most in VAT?

### Customer Analysis

How many unique customer types exist?

How many unique payment methods are used?

What is the most common customer type?

Which customer type buys the most?

What is the gender distribution of customers?

Gender distribution per branch.

Time of the day customers give the most ratings.

Which day of the week has the best average ratings per branch?


### Revenue and Profit Calculations

#### Key Formulas

``` sql

COGS = Unit Price × Quantity
VAT = 5% × COGS
Gross Sales = COGS + VAT
Gross Profit = Gross Sales − COGS
Gross Margin (%) = (Gross Profit ÷ Gross Sales) × 100

Example Calculation

Unit Price: 45.79, Quantity: 7
COGS = 45.79 × 7 = 320.53
VAT = 5% × 320.53 = 16.03
Gross Sales = 320.53 + 16.03 = 336.56
Gross Margin (%) = (16.03 ÷ 336.56) × 100 ≈ 4.76%

```

### Conclusion

Identified top-performing branches and product lines.

Discovered trends in sales, customer behavior, and product performance.

Provided actionable recommendations to optimize sales strategies and enhance branch profitability.


