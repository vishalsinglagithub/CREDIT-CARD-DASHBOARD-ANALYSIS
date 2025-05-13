# CREDIT-CARD-DASHBOARD-ANALYSIS

Overview
This project presents a comprehensive Power BI dashboard built using two datasets related to credit card customers. The goal is to analyze customer demographics, credit behavior, spending patterns, and repayment trends to generate actionable insights for business decision-making in the banking and finance domain.

By integrating and visualizing the data, this dashboard enables deeper understanding of customer behavior, credit limit utilization, and risk indicators.

📂 Dataset Description
The project uses two CSV files:

credit_card.csv

Contains customer profile data.

Key columns:

CustomerID

Gender

Age

Income

Education

Marital_Status

Credit_Limit

credit_card (1).csv

Contains transaction and account activity data.

Key columns:

CustomerID

Avg_Open_To_Buy

Total_Trans_Amt

Total_Trans_Ct

Avg_Utilization_Ratio

Total_Revolving_Bal

Payment_Ratio

Both files are linked using the CustomerID key in Power BI to form a single data model.

🎯 Objectives
Understand customer demographics and credit card usage behavior.

Identify customer segments based on spending and repayment patterns.

Highlight key financial metrics like:

Credit Limit Distribution

Transaction Trends

Utilization Ratios

Payment Behaviors

Build a clean, interactive dashboard for easy exploration of insights.

📊 Dashboard Features
The Power BI dashboard includes the following components:

1. Customer Demographics Overview
Gender & Age distribution

Education level and marital status analysis

Income range categorization

2. Credit Utilization Analysis
Average credit limit by customer segments

Credit usage vs. available credit (Utilization Ratio)

Revolving balance vs. open-to-buy analysis

3. Transaction Summary
Total transaction amount and count by customer

High vs. low spenders visualization

Monthly spending patterns (if applicable)

4. Repayment & Risk Insights
Payment to balance ratios

Late payment trends

Identification of potentially risky customers with high utilization and low repayment

5. Interactive Filters & Slicers
Filter by age group, education, gender, or income

Drill down by individual customers or groups
Key Insights from the Dashboard
Customer Segmentation Based on Spending

High-income customers generally have higher transaction volumes.

A small percentage of customers account for a large portion of the total transaction amount, indicating the presence of high-value users.

Credit Limit vs. Utilization

Most customers utilize less than 50% of their available credit limit.

A few customers show a high utilization ratio (>80%), which could be potential credit risk indicators.

Revolving Balance Trends

Customers with high revolving balances tend to have lower payment ratios.

There is a clear segment of customers who carry forward significant balances month-to-month, indicating possible financial stress.

Payment Behavior Patterns

Customers with consistent high payments maintain low revolving balances and utilization ratios.

Customers with lower payment ratios tend to also have lower total transaction counts, possibly indicating reduced card activity.

Demographic Spending Patterns

Middle-aged customers (35–50 years) tend to have the highest average transaction amounts.

Married customers and those with higher education levels show more stable and predictable credit behavior.

Total Transactions and Activity

There is a positive correlation between Total_Trans_Ct and Total_Trans_Amt, showing that frequent users are also high spenders.

Some customers with high Credit_Limit are underutilizing their credit cards, which could be an opportunity for upselling or cross-selling.

Open to Buy Analysis

Many customers have a high Avg_Open_To_Buy value, suggesting they are financially conservative or cautious credit users.

This could also mean the bank is overestimating limits for some customers, which may need reevaluation.

 Tools & Technologies Used
Power BI – for data modeling and interactive dashboards

Power Query – for data cleaning and transformation

DAX – for calculated columns and measures

CSV Files – as data sources
