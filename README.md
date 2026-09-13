E-Commerce Sales & Customer Analytics
An end-to-end Data Analytics project completed with my friend Saranesh Pandiyan SPM, focused on analyzing an E-Commerce Sales & Customer Analytics use case.

The project follows a complete analytics workflow:

Excel → SQL → Data Cleaning → Data Analysis → Power BI → Business Insights

We developed a 2-page interactive Power BI dashboard to analyze sales, customers, products, orders, payments, returns, discounts, and other business metrics.

📌 Project Overview
The objective of this project was to transform raw e-commerce data into structured and meaningful information that can be used to understand business performance and support data-driven decisions.

The project includes:

Customer analysis
Order analysis
Product analysis
Sales analysis
Payment analysis
Return analysis
Category and sub-category analysis
City-wise sales analysis
Sales trend analysis
Discount analysis
🛠️ Tools & Technologies
Tool	Purpose
Excel	Data collection and initial data structuring
MySQL / SQL	Data cleaning, validation, transformation and analysis
Power BI	Data visualization and dashboard development
🔄 Project Workflow
1. Data Collection & Structuring – Excel
The raw e-commerce dataset was collected and organized using Excel.

The dataset contains information related to:

Customers
Orders
Products
Payments
Categories
Cities
Shipping
Returns
2. Data Cleaning & Preparation – SQL
SQL was used extensively to clean, validate, and prepare the data.

The following data quality checks were performed:

Identified duplicate records
Checked NULL and blank values
Validated Customer IDs
Validated Order IDs
Validated Product IDs
Checked invalid ages
Checked invalid sales values
Validated discounts
Checked invalid dates
Standardized date formats
Validated payment modes
Checked order statuses
Checked return statuses
Validated product prices
Checked category and sub-category values
Removed data inconsistencies
SQL techniques used
SELECT
WHERE
GROUP BY
HAVING
COUNT
SUM
DISTINCT
JOIN
LEFT JOIN
RIGHT JOIN
ORDER BY
ALTER TABLE
UPDATE
Date functions
Aggregate functions
Primary Keys
Foreign Keys
🗄️ Data Model
The project contains four main tables:

Customers
Contains customer-related information such as:

Customer ID
Customer Name
Age
City
State
Gender
Registration Date
Orders
Contains transaction-related information such as:

Order ID
Order Date
Customer ID
Product ID
Quantity
Sales
Discount
Payment Mode
Shipping City
Shipping State
Order Status
Products
Contains product information such as:

Product ID
Product Name
Category
Sub-Category
Cost Price
Selling Price
Returns
Contains return-related information such as:

Return ID
Order ID
Return Date
Return Reason
Return Status
Primary and foreign key relationships were created to maintain data integrity between related tables.

📊 Power BI Dashboard
A 2-page interactive Power BI dashboard was developed to present the analysis in a business-friendly format.

Dashboard Page 1 – E-Commerce Overview
The first dashboard focuses on overall sales and order performance.

Key elements include:

Total Sales
Total Orders
Order Status
Product Sales
Monthly Order Status
Sales Amount
Sales by Category
Sales by Category and Sub-Category
Cost Price Analysis
Overall Data Table
Dashboard Page 2 – Sales & Customer Analytics
The second dashboard provides detailed sales and customer analysis.

KPIs
Total Sales
Total Orders
Total Customers
Total Quantity
Average Order Value (AOV)
Visualizations
Sales Trend Over Time
Sales by Category
Sales vs Discount
Sales by Sub-Category
Return Status
Sales by Payment Mode
Sales by City
Product-Level Analysis
Interactive Filters
The dashboard includes filters/slicers for:

Category
Order Date
Payment Mode
Sub-Category
City
Start Date
End Date
📈 Key Business Areas Analyzed
Sales Performance
Analyzed sales performance across:

Categories
Sub-categories
Cities
Products
Time periods
Customer Analysis
Analyzed customer-related information and customer distribution using demographic and geographic attributes.

Order Analysis
Analyzed:

Order volume
Order status
Monthly order performance
Delivered orders
Shipped orders
Processing orders
Cancelled orders
Payment Analysis
Compared sales generated through different payment methods such as:

Card
Cash
UPI
Net Banking
Product Analysis
Analyzed product sales and product-level performance using category, sub-category, cost price, and selling price.

Return Analysis
Analyzed return status and return-related information to understand product return patterns.

