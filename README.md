# ECOMMERCE_SALES_ANALYSIS
E-commerce Sales Analysis
Project Overview
This project analyzes e-commerce sales data to understand overall sales
performance, product and category performance, customer locations,
payment methods, and monthly sales trends.
The project follows a simple data analytics workflow:
Data → Cleaning → Analysis → Insights → Recommendations
Business Problem
The objective is to understand:
- Overall sales performance
- Best-performing categories and products
- Strong customer locations
- Preferred payment methods
- Monthly sales trends
- Order status issues that may affect business performance
Dataset
- Records: 100
- Columns: 21
- Period: January to April 2024
- Dataset: ecommerce_sales_data_cleaned.csv
Main fields include Date, Order ID, Customer ID, Product Category,
Product Name, Quantity Sold, Unit Price, Discount, Payment Method,
Customer Location, Order Status, Shipping Cost, Profit Margin, Customer
Age, Customer Gender, Customer Segment, Review Rating, Total Sales and
Month.
Data Cleaning
The dataset was checked and prepared before analysis.
The following checks were performed:
- Dataset structure and column names
- Data types
- Missing values
- Duplicate records
- Numeric fields such as quantity, price, discount, shipping cost,
  profit margin and sales
- Date and month fields for time-based analysis
The cleaned dataset was then used for the analysis.
Analysis
The analysis was performed using Python/Pandas.
Key analysis areas:
- Total sales and quantity sold
- Sales by product category
- Sales by product
- Sales by customer location
- Sales by payment method
- Monthly sales trend
- Order status distribution
Key Business Insights
1. Sports was the highest-revenue category, generating
   approximately $19,059 in sales.
2. Smartphones were the strongest individual product, generating
   approximately $17,520 in sales.
3. New York was the leading customer location, generating
   approximately $18,271 in sales.
4. Debit Card was the leading payment method by sales, contributing
   approximately $23,813.
5. March recorded the highest monthly sales, while April showed a
   noticeable decline.
6. Cancelled and returned orders were significant, so order-status
   performance requires attention.
Recommendations
1. Focus on high-performing products and categories
Maintain stock availability and targeted promotions for strong
performers such as Sports products and Smartphones.
2. Strengthen regional marketing
Use targeted campaigns in strong markets such as New York and Los
Angeles while identifying opportunities in weaker locations.
3. Investigate cancellations and returns
Review the reasons behind cancelled and returned orders and identify
products or locations with unusually high issues.
4. Support sales during weaker months
Use targeted offers and category-specific promotions during slower
periods such as April.
Project Files
- ecommerce_sales_data_cleaned.csv --- cleaned dataset
- Python analysis file --- EDA and business analysis
- Business report --- summary of findings and recommendations
- Power BI dashboard --- visual summary of business performance
Dashboard
The dashboard is designed as a simple management view with:
- Total Sales KPI
- Total Quantity KPI
- Average Sales per Order KPI
- Monthly Sales Trend
- Sales by Category
- Top Products
- Sales by Customer Location
- Order Status
- Simple filters for Category, Month and Order Status
Conclusion
The analysis provides a clear view of e-commerce sales performance and
highlights the products, categories, locations and periods contributing
most to revenue. It also identifies cancellations, returns and weaker
months as areas that management can investigate further.
