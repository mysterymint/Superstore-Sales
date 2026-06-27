# Superstore-Sales
Emmanuel Muondo 669926
https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset
51,291 rows and 21 columns.

Business problem being analyzed
As a Business Intelligence Analyst for a global retail company,
I was tasked with analysing sales performance across different
regions, product categories, and customer segments from 2011 to 2014.
The goal was to clean the raw dataset and build a professional
Power BI dashboard to support management decision making.

List of all Power Query transformations performed
Data Cleaning
Renamed unclear columns 
Changed data types 
Removed duplicate records from order_id column
Removed blank rows from the dataset
Trimmed text columns 
Replaced inconsistent values 
Removed unnecessary columns 
Split order_id column by hyphen delimiter into 3 columns
Merged state and country columns into a Location column
Created custom column: Profit Margin % = profit / sales x 100
Created conditional column: Sales Category
Extracted Year, Month, Quarter and Day from order_date column
Filtered rows where sales greater than 0 and discount
  greater than 0
Sorted data by order_date ascending
Added index column starting from 1
Created MinSales parameter to filter sales dynamically
Used Group By to summarise Total Sales, Total Profit
  and Order Count by category
Created Business Tier nested conditional column
  (GOLD, SILVER, BRONZE, Loss)
Used Column Profiling to identify data quality issues
Handled errors in Profit Margin % column by removing errors
3 KPI Cards: Total Sales, Total Profit, Total Orders
Bar Chart: Sales by Region
Column Chart: Sales by Category
Line Chart: Sales Trend Over Time (with drill down)
Donut Chart: Sales by Segment
Table: Order Transaction Details
Matrix: Sales by Category and Segment
Map: Global Sales by Country
Scatter Chart: Sales vs Profit relationship

Slicers Added
Segment slicer (Consumer, Corporate, Home Office)
Region slicer (Africa, APAC, Canada, EU, EMEA, LATAM, US)
Year slicer (2011, 2012, 2013, 2014)

Business Insights
Technology is the best generating revenue
The Technology category consistently generates the highest
sales across all markets particularly in the APAC and US
regions. Management should prioritize stocking and marketing
technology products to maximize revenue growth.

Consumer segment leads but Corporate has higher order value.
The Consumer segment accounts for the majority of orders
but the Corporate segment has a higher average order value
per transaction. The company should invest in targeted B2B
outreach to grow the more profitable Corporate segment.

Q4 seasonal spike requires advance preparation**
Sales data from 2011 to 2014 shows a consistent spike in
Q4 every year driven by holiday season demand. The business
should ensure sufficient inventory and staffing in Q3 to
prepare for and capitalize on the seasonal rush.
