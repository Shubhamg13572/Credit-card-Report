# Credit-card-Report
Credit Card Financial Dashboard: SQL data cleaning and Power BI visualization with DAX analysis for detailed financial insights.

This repository contains a comprehensive credit card financial dashboard project developed to provide detailed insights into financial performance. The project involves the following components:

Data Preparation:
SQL Data Cleaning: SQL scripts are used to clean and organize data from two primary tables: cc_detail (credit card transactions) and cust_detail (customer information).
Data Integration: Added a 53rd week of data into the SQL database after completing initial dashboard development. The dashboard was dynamically updated in Power BI upon refreshing the data source.

Dashboard Visualization:
Power BI Reports: Interactive dashboards showcasing key metrics, including total revenue, transaction amounts, interest earned, and transaction counts.
Detailed Metrics: Visualizations include card category-wise revenue, revenue by chip use, education, customer job, and more. Slicers for filtering data by weeks, quarters, card categories, gender, and income groups are included.

Advanced Analysis:
DAX Calculations: Implemented DAX measures for dynamic calculations, including:
AgeGroup: Categorizes customers into age brackets.
IncomeGroup: Segments income into Low, Med, and High.
Current_week_Reveneue & Previous_week_Reveneue: Tracks weekly revenue changes.

Project Insights:

Week 53 (December 31, 2023):
Revenue Increase: Revenue grew by 28.8% compared to the previous week.
Transaction Metrics: Total transaction amount and count also saw significant increases.
Customer Growth: There was an increase in the number of customers.

Year-to-Date (YTD) Overview:
Total Revenue: $57 million for the year.
Interest Earned: $8 million.
Total Transaction Amount: $46 million.
Customer Breakdown: Male customers contributed $31 million in revenue, while female customers contributed $26 million.
Card Type Contributions: Blue and Silver credit cards accounted for 93% of overall transactions.
Geographic Distribution: Texas (TX), New York (NY), and California (CA) together contributed 68% of the total revenue.
Activation Rate: Overall activation rate was 57.5%.
Delinquent Rate: Overall delinquency rate was 6.06%.
