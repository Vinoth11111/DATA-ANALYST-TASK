# DATA-ANALYST-TASK
Data Analyst internship project at ELEVATE LAB focused on data collection, cleaning, EDA, and visualization using Python, Pandas, NumPy, Matplotlib, Seaborn, and SQL. Aimed at uncovering insights, identifying trends, and supporting data-driven decisions through analysis and reporting

TASK - 1

Description:
This task is part of my ongoing Data Analyst internship. The goal was to clean and prepare raw data for analysis.

Tasks Done:
Handled missing values using .isnull() in Python and filters in Excel
Removed duplicate rows using .drop_duplicates() and Excel’s "Remove Duplicates"
Standardized text values (e.g., gender, country names)
Converted dates to dd-mm-yyyy format
Renamed columns (lowercase, no spaces)
Fixed data types (e.g., age as int, date as datetime)


Tools Used:
Python (Pandas)
Microsoft Excel

TASK-2
Key Insights

Sales by Region/State: Identifies top-performing and underperforming markets to guide strategic focus.
Sales Trend Over Time: Tracks monthly and yearly sales to detect seasonality and growth patterns.
Product Performance: Analyzes sales across product categories and sub-categories, aiding inventory and marketing decisions.
Customer Segments: Evaluates the contribution of different customer segments (Consumer, Corporate, Home Office) to overall revenue, helping target the right audience.
Shipping Mode Impact: Examines how shipping modes affect delivery time and customer purchasing behavior, revealing areas for logistics optimization.

TASK-3
Key SQL Tasks Performed

Data Selection & Filtering:
Used SELECT, WHERE, ORDER BY, and GROUP BY to filter, sort, and group data for better analysis.
Joins:
Applied INNER JOIN to combine data from multiple tables for deeper insights.
Subqueries:
Used nested queries to perform complex filtering and calculations.
Aggregate Functions:
Implemented functions like SUM and AVG to calculate total sales, average order value, and other key metrics.
Views Creation:
Created reusable VIEWS for simplified and efficient data access.
Query Optimization:
Used INDEXES to speed up data retrieval and enhance performance.

TASK-4
Description

This task focuses on creating interactive dashboards to explore sales and profit data visually. Using tools like Power BI / Tableau (specify which), the dashboard helps stakeholders quickly understand key business metrics and trends.

Key Features

📊 KPI Analysis
Total Sales Revenue for the selected period
Total Profit earned across all regions
Average Profit Margin across all transactions
Summary Cards displaying:
Total Sales
Total Profit
Total Orders


🎛️ Slicers & Filters for Interactivity
View sales and profit by region, country, and product category
Filter by sales channels, country, or region to identify top-performing areas


📈 Time-Series Analysis
Monthly trends of sales and profit over the past year
Seasonal patterns identified in sales performance
Tools Used

Power BI / Tableau (choose one)
Excel / CSV data source

Tools Used
SQL (PostgreSQL)

TASK-5
Exploratory Data Analysis (EDA)

Description

This task involves performing exploratory data analysis to understand the structure, distribution, and relationships within the dataset. Various statistical methods and visualizations are used to uncover insights and patterns.

Key Steps

📋 Data Overview
Used .describe(), .info(), and .value_counts() to understand data types, missing values, and distribution of categorical variables.
📊 Data Visualization
Created visualizations using:
sns.pairplot() to observe pairwise relationships
sns.heatmap() to show correlations between variables
Histograms, boxplots, and scatterplots to analyze distributions and outliers
🔍 Trend & Relationship Analysis
Identified key relationships between variables (e.g., sales vs. profit, discount impact)
Detected patterns, outliers, and correlations
📝 Observations & Summary
Wrote brief insights for each visual
Provided a summary of overall findings to guide further analysis and decision-making
Tools Used

Python (Pandas, Seaborn, Matplotlib)


TASK-6
Time-Based Sales Analysis (SQL)

Description

This task focuses on analyzing sales data over time using SQL queries. The goal is to extract monthly and yearly trends in revenue and order volume to support business planning and forecasting.

Key SQL Operations

Date Extraction:
Used EXTRACT(MONTH FROM order_date) to group data by month.
Grouping:
Grouped sales data by year and month using GROUP BY.
Revenue Calculation:
Used SUM() to calculate total monthly revenue.
Order Volume:
Used COUNT(DISTINCT order_id) to calculate total number of unique orders.
Sorting:
Applied ORDER BY to sort results chronologically.
Time Filtering:
Limited results to specific time periods for focused analysis.
Tools Used

SQL (PostgreSQL)


TASK-7
Description

This task demonstrates how to connect a SQLite database to Python, run SQL queries, and visualize the results using pandas and matplotlib. The goal is to analyze total quantity sold and revenue generated per product.

Key Steps

Connected to sales_data.db using sqlite3
Ran a SQL query to calculate total quantity and revenue per product
Loaded query results into a pandas DataFrame
Displayed results using print()
Plotted a bar chart of product revenue using matplotlib
Tools Used

Python (sqlite3, pandas, matplotlib)
Postgresql Database

TASK-8

Description

This task focuses on building a visual sales dashboard to uncover trends, regional performance, and product category insights. Data was formatted and visualized to support interactive business analysis.

Key Steps

Converted Order Date to Month-Year format for clear time-based visuals
Created 3 key visuals:
Line Chart: Monthly Sales Trend
Bar Chart: Sales by Region
Donut Chart: Sales by Category
Added interactive slicer/filter for Region and Category
Applied color highlights to showcase top-performing areas
Key Insights

West region recorded the highest sales in Q3
Technology category led overall revenue contribution
Sales peaked in November and December, indicating seasonal demand
Tools Used

Power BI / Tableau (specify which one)
Excel / CSV as data source
