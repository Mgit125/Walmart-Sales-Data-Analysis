# Walmart-Sales-Data-Analysis

![logo](https://raw.githubusercontent.com/Mgit125/Walmart-Sales-Data-Analysis/refs/heads/main/walmart%20sales.avif)

## About the Project

This project explores Walmart sales data to uncover insights into top-performing branches, product trends, and customer behavior. The analysis aims to provide actionable strategies for branch performance improvement and enhanced customer targeting.
##Purpose of the Project
The main objective is to analyze Walmart's sales data to identify various factors influencing branch performance and suggest actionable strategies for improvement.

## Dataset Overview

Source: Kaggle Walmart Sales Forecasting competition

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

## Insights and Findings from Walmart Sales Data Analysis

#### City and Branch Distribution

The dataset covers three cities: Naypyitaw, Yangon, and Mandalay, with branches located in each city.

#### Sales Performance by Time of Day

Afternoon sales dominate across all branches, making it the most profitable time of the day.

Customers also preferred Afternoon for providing service ratings, contributing to over 50% of total ratings.

#### Day-wise and Week-wise Analysis

Monday has the highest average customer rating overall (7.15).

By branch:

Branch A: Best ratings on Friday.

Branch B: Best ratings on Monday.

Branch C: Best ratings on Friday.

#### Top Product Lines

Food and Beverages is the most sold product line, generating the highest revenue of $53,471.28 and contributing the most VAT at $2,673.56.

Fashion Accessories is most popular among females, while Health and Beauty appeals most to male customers.

#### Payment Method Preferences

The E-wallet is the most preferred payment method among customers.

#### Customer Demographics and Preferences

Female customers contribute the highest sales revenue.

Members generate more revenue than normal customers, paying higher VAT as well.

#### Monthly Trends

January shows the highest Cost of Goods Sold (COGS) at $110,754.16.

Revenue trends suggest seasonal patterns that businesses can leverage.

#### Branch Performance

Branch A outperforms others in terms of quantity sold, exceeding the average products sold by branches.

Gender distribution analysis shows slight variations in transaction counts per branch.

#### Ratings and Feedback

Feedback is predominantly given in the Afternoon, indicating a favorable time for customer interactions.

#### Customer Ratings by Product Line

Average ratings reveal that Fashion Accessories received the highest customer satisfaction.

#### Revenue Contribution by City

Naypyitaw generates the highest revenue at 105,303.53, also contributing the most in VAT (34.24%).

#### Performance Classification

A detailed classification of product lines indicates "Good" or "Bad" performance based on average sales, enabling focused strategies for improvement.

## Conclusion

The analysis highlights the importance of understanding customer preferences, branch-specific trends, and product line performance. Afternoon hours, food and beverage products, female customers, and e-wallet payments drive significant revenue. Seasonal sales and ratings also indicate potential opportunities to align business strategies.

### Suggestions for Business Improvements

#### Focus Marketing Efforts During Peak Hours

Leverage the Afternoon period for promotions and customer engagement activities to capitalize on peak sales and feedback hours.

#### Promote High-Performing Product Lines

Increase inventory and advertising for Food and Beverages and Fashion Accessories, which are top-performing categories.

#### Expand E-Wallet Payment Options

Promote and expand partnerships with popular e-wallet providers to attract more customers and streamline transactions.

#### Incentivize Membership Enrollment

Develop loyalty programs to encourage more customers to become members, as they contribute significantly to revenue.

#### Optimize Branch-Specific Strategies

Tailor strategies for each branch based on its unique strengths (e.g., higher customer satisfaction days and top-selling products).

#### Monitor Seasonal Sales Trends

Prepare for seasonal demand spikes, particularly in January, by adjusting inventory and staffing levels accordingly.

#### Enhance Customer Experience

Invest in training staff to provide exceptional service on high-feedback days and times, such as Friday afternoons.

#### Improve Underperforming Product Lines

Investigate customer preferences and address issues in product lines with lower sales to improve their performance.


This actionable roadmap empowers Walmart to optimize revenue, enhance customer satisfaction, and strengthen operational efficiency.

