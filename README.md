# Walmart-Sales-Analysis
Overview

This project analyzes Walmart sales data using SQL to perform data cleaning, transformation, and insights extraction. The dataset includes information on sales transactions, customer details, product lines, revenue, and ratings.

Database Schema

**Database:** salesDataWalmart

**Table:** sales

  invoice_id: Unique transaction ID (Primary Key)

  branch: Store branch identifier

  city: Store location

  customer_type: Type of customer (e.g., Member, Normal)

  gender: Customer gender

  product_line: Category of the product sold

  unit_price: Price per unit of product

  quantity: Number of units sold

  VAT: Tax applied to the sale

  total: Total amount paid after tax

  date: Date of transaction

  time: Time of transaction

  payment_method: Payment type (Cash, Credit, etc.)

  cogs: Cost of Goods Sold

  gross_margin_pct: Gross margin percentage

  gross_income: Profit made per transaction

  rating: Customer rating

  time_of_day: (Derived column) Morning, Afternoon, Evening

  day_name: (Derived column) Day of the week

  month_name: (Derived column) Month of the year

**Data Cleaning & Transformation**

  **Added columns:** time_of_day, day_name, month_name for better time-based analysis.

  **Updated Columns:** time_of_day, day_name, and month_name using SQL transformations.

**Key Queries & Insights**

**General Analysis**

  Unique cities in the dataset

  Mapping of branches to cities

**Product Analysis**

  Number of unique product lines
  
  Best-selling product lines
  
  Revenue per product line
  
  Largest revenue-generating product line
  
  Product line VAT comparison
  
  Product performance classification ("Good" or "Bad")

**Customer Analysis**

  Unique customer types and payment methods
  
  Most common customer type
  
  Customer type contributing the highest revenue
  
  Gender distribution of customers
  
  Gender sales per branch
  
  Customer ratings by time of day and day of the week

**Sales Analysis**

  Total revenue by month
  
  Best-performing month in terms of revenue and cost of goods sold (COGS)
  
  Branch-wise and city-wise revenue comparison
  
  Customer type contribution to revenue
  
  Tax/VAT percentage by city
  
  Most profitable customer type in terms of VAT contribution

**How to Use**

  Setup Database: Create a MySQL database named salesDataWalmart and execute the provided SQL scripts.
  
  Load Data: Ensure that the sales data is properly imported into the sales table.
  
  Run Queries: Execute the provided queries to gain insights.

**Requirements**

  MySQL database
  
  SQL Editor (e.g., MySQL Workbench, DBeaver, or any SQL-supported tool)

**Contributions**

  Contributions are welcome! Feel free to submit issues or pull requests.

**License**

  This project is open-source and available under the MIT License.
