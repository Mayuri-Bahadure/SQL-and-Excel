# Data Analysis of Pizza Sales using SQL and PowerBi

### Dashboard link: https://drive.google.com/file/d/1BehSbs7CcQautRxqNwwMa3sHJSqcpCOG/view?usp=drivesdk

## Problem Statement:
The business owner want insights about Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, Average Pizzas Per Order. Which pizza category generate more profit and which is less sold pizzas.

## Data Analysis using SQL:
### KPI’s REQUIREMENT
To analyse key indicators for sales data to gain insights into business performance. Specifically calculate following metrics:
1. Total Revenue: The sum of the total price of all pizza orders.
2. Average Order Value: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.         
3. Total Pizzas Sold :  The sum of the  quantities of all pizzas sold.
4. Total Orders: The total number of orders placed.
5. Average Pizzas Per Order : The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.

### CHART REQUIRMENT
To visualize various aspects of sales data to gain insights and understand key trends.identified the following requirements for  creating charts:
1. Daily Trend for Total Orders: Create  a bar chart that that displays the daily trend for total orders over a specific time period. This chart will help to identify any pattern or fluctuations in order volumes on a daily basis.

2. Monthly Trend for Total Orders: Create a line chart that illustates the monthly trend of total orders throughout the year. This chart allow  to identify peak hours or periods of high order activity.

3. Percentage of Sales by Pizza Category: Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.

4. Percentage of Sales by Pizza Size: Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.

5. Total Pizzas Sold by Pizza Category: Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.

6. Top 5 Best Sellers by Revenue, Total Quantity and Total Orders:
Create a bar chart highlighting the top 5 best-selling pizzas based on the Revenue, Total Quantity, Total Orders. This chart will help us identify the most popular pizza options.

7. Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders:
Create a bar chart showcasing the bottom 5 worst-selling pizzas based on the Revenue, Total Quantity. Total Orders. This chart will enable us to identify underperforming or less popular pizza options.

## Data Visualization using Power Bi:
- Step:1: Import data from SQL data server to power Bi.
- Step:2: Data Cleaning: In pizza size column some abbreavations are found. Use power query and replace the abbreavations with word.
- Step:3: Create new measures according KPI's.
- Step:4: Build new card visual for KPI's.
- Step:5: Add a column to the table with the help of power query. extract day from date column. This column will help to build daily trend visualization. Add clause to get series from sunday to saturday as 1 to 7.
- Step:6: Build a bar visual of daily trend. Change the colours of visualization.
- Step:7: Create new column for month number with help of power query. Extract data from date column. This columnn help to build monthly trend visualization.
- Step:8: Build Area chart visualization for monthly trend. Change the colours of visualization.
- Step:9: Build donut chart visualization for % of sales by category. Change the colour scheme of visualization.
- Step:10: Build donut chart visualization for % of sales by pizza size. Change the colour scheme of visualization.
- Step:11: Create funnel chart for total pizzas sold by pizza category.
- Step:12: Add insights to visualization.
- Step:13: Add Slicer of pizza category. For interactive visualization.
- Step:14: Add Order date slicer to visualization.
- Step:15: Create Another dashboard to visualization 
- Step:16: Create bar chart for top 5 pizzas by revenue, add the pizza name with respect to total revenue. Apply filter to get top 5 pizzas.
- Step:18: Create bar chart for bottom 5 pizzas by revenue, add the pizza name with respect to total revenue. Apply filter to get bottom 5 pizzas.
- Step:19: Create bar chart for top 5 pizzas by quantity, add the pizza name with respect to total pizza sold. Apply filter to get top 5 pizzas. Change colour scheme of visualization.
- Step:20: Create bar chart for bottom 5 pizzas by quantity, add the pizza name with respect to total pizza sold. Apply filter to get bottom 5 pizzas. Change colour scheme of visualization.
- Step:21: Create bar chart for top 5 pizzas by total orders, add the pizza name with respect to total orders. Apply filter to get top 5 pizzas. Change colour scheme of visualization. Format the visualization.
- Step:22: Create bar chart for bottom 5 pizzas by total orders, add the pizza name with respect to total orders. Apply filter to get bottom 5 pizzas. Change colour scheme of visualization. Format the visualization.
- Step:23: Add insights to the best/worst seller dashboard.
- Step:24: Add button to nevigate between home page and best/worst seller page.

## Conclusions:
#### 1) Busiest days and months:
- 1)DAYS: Orders are highest on weekends, Friday, Saturday evenings.
- 2) MONTHLY: There are maximum orders from month of July and January.

#### 2) Sales Performance:
- 1)CATEGORY: Classic category contribute to maximum sales and maximum total orders.
- 2)SIZE: Large size pizza contribute to more maximum sales.

#### 3) Best Sellers:
- 1) REVENUE: The thai chicken pizza contribute to maximum revenue.
- 2) QUANTITY: The classic deluxe pizzas contribute to maximum total quantities.
- 3) TOTAL ORDERS: The classic deluxe pizzas contribute to maximum total orders.

#### 4) Worst Sellers:
- 1) REVENUE: The brie Carrie pizza contribute to minimum revenue.
- 2) QUANTITY: The brie carrie pizza contribute to minimum total quantity.
- 3) TOTAL ORDERS: The brie carrie pizza contribute to minimum total orders.
