# Pizza-Shop-Sales-Data-Analysis-With-Dashboard-Using-SQL-And-MS-Excel

Project Overview:
This project focuses on analyzing the sales performance of a pizza shop using a combination of SQL for data querying and Microsoft Excel for data visualization. The goal is to derive meaningful business insights from raw sales data, such as revenue trends, customer behavior, and product performance. This end-to-end project transforms a simple dataset into an insightful interactive dashboard using industry-standard tools and techniques.

Dataset Description:
The dataset used for this project, named pizza_sales_data.csv, contains a total of 48,620 rows and 12 columns. Each row in the dataset represents a single order record and includes critical details such as order ID, date and time of the order, pizza name, pizza category (like Classic or Veggie), pizza size (Small, Medium, Large), the quantity of pizzas sold, and the total price of that order. These columns form the foundation for the analysis, allowing us to study customer trends and product performance in detail.

Database and Table Setup:
The first step in this project was setting up a relational database using Microsoft SQL Server. A new database was created, and the pizza sales data was imported into a structured table. This enabled efficient querying and analysis using SQL. By organizing the raw data into a formal SQL table, the project laid the groundwork for generating reliable and scalable insights.

Key Performance Indicators (KPIs):
A major focus of the project was on computing essential Key Performance Indicators (KPIs) using SQL queries. These metrics help understand how the business is performing overall. The KPIs calculated included:

Total Revenue: The total income from all pizza orders.

Average Order Value: The average amount spent per customer order.

Total Pizzas Sold: The total number of pizza units sold.

Total Orders: The count of unique orders placed.

Average Pizzas per Order: A measure of how many pizzas, on average, were ordered per transaction.

These KPIs were derived by executing SQL aggregation queries directly on the database and provided a solid summary of business health.

Trend Analysis with SQL:
Beyond KPIs, SQL queries were also used to identify trends and patterns in sales activity:

Daily Order Trend: By grouping order data by weekday, we identified which days of the week received the most orders, helping to plan resources and promotions accordingly.

Hourly Order Trend: Using the order time data, we charted peak ordering hours throughout the day — a critical insight for managing kitchen operations and staff.

Sales by Pizza Category and Size: Revenue was broken down by pizza category and pizza size, and their percentage contributions to total sales were calculated to understand customer preferences.

Top and Bottom Sellers: The top 5 and bottom 5 pizza types were identified based on the total quantity sold, guiding product-level decisions like promotions or discontinuations.

Excel Integration and Dashboard Creation:
After deriving insights through SQL, the next phase involved creating an interactive Excel dashboard. The Excel file was connected directly to the SQL Server database using the “Get Data from SQL Server” feature. This allowed real-time data updates in Excel whenever the database was refreshed.

Within Excel, Pivot Tables were used to structure the queried data, and Pivot Charts were created to visualize it. Slicers and timeline filters were also added to make the dashboard dynamic and user-friendly, enabling users to filter data by category, size, or time period.

Features of the Dashboard:
The resulting Excel dashboard includes:

A KPI panel with metrics like total revenue, total orders, and average pizzas per order.

Line and bar charts visualizing daily and hourly order patterns.

Pie charts and column charts displaying sales distribution by category and size.

Leaderboards for best-selling and least-selling pizzas.

These features make the dashboard a one-stop tool for business decision-makers to understand what's working and what needs attention.

Skills & Learning Outcomes:
This project introduces several valuable concepts and skills:

Creating a SQL database and importing data.

Writing advanced SQL queries to generate KPIs and analytical summaries.

Connecting SQL Server to Excel for live data refresh.

Using Pivot Tables, Charts, and Slicers to build professional dashboards.

Performing trend analysis and building data-driven business strategies.

Anyone working on or reviewing this project will come away with a comprehensive understanding of how to transform raw business data into actionable insights.

Real-World Application:
The project mirrors a real-world use case where a restaurant or retail chain can use its order data to make smarter decisions. It provides insight into customer preferences, high-performing products, and optimal operating hours. This can lead to improved marketing, better inventory planning, and enhanced customer satisfaction.

