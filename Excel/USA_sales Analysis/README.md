# Data Analysis of USA_Sales using Excel

## Problem Statement
Find out change in sales from 2014 to 2017.
Top 5 Customers who purchase product on large scale.
Which category product has highest sales.

## Data Cleaning and Preparation:
- Step:1 Insert Table to the Dataset. Rename table.
- Step:2 Change the datatype of some column from general to number format. Decrease Decimal of some columns.
- Step:3 Sort Data yearwise.
- Step:4 Insert year column, extract values from order date column using year function. Change the datatype from general to number.
- Step:5 Insert month column, extract values from order date column using month function. Change the datatype from general to number.
- Step:6 Check and remove duplicates.
- Step:7 Check blank Values. In the home tab ribbon their is option called find and select using this check blank values. In the table their is no any blank value.

## Insert Pivot Tables:
1) Sales By Category:
To create clustered chart of sales by category first create pivot table. Select sub-category as rows and sum of sales as values.
Sort data from largest to smallest. Copy the data using = function to create clustered chart.

2) Profit Gained Over time:
To create line chart of sales by category first create pivot table. Select year as rows and profit as values. Add category as a column. Copy the data using = function to create clustered chart. This chart shows change in profit over time.

3) Monthly Sales:
To create 2d area chart of monthly sales first create pivot table. Select year as rows and sum of sales as values. Add year as slicer. Copy the data using = function to create clustered chart. This chart shows montly sales.

4) Top 5 Customers making profit:
To create pie chart of top 5 customers first create pivot table. Select customer name as rows and profit as values. Filter profit column largest to smallest. This chart shows only top 5 customers. 

5) Sales By State:
To create line chart of sales by state first create pivot table. Select state as rows and sum of sales as values.

6) Customer Count:
To create bar chart of customer count first create table. Remove duplicates to get only unique customer names. Then create pivot table. Select year as rows and customer count as values.

## Dashboard:
Step:1) Remove Gridlines and headings.
Step:2) Add rounded corner shape to add heading to the dashboard.Add dashboard name.
Step:3) Cut and paste year slicer on dashboard which prepared previously. 
Step:4) Add category slicer.
Step:5) Add rounded corner shapes to the dashboard, so the visualization can fit into it.
Step:6) Fit the visualizations into the shapes.
Step:7) Give Colour effect to the dashboard.

## Analysis:
1) The Phone sub category has highest sales with number of 330007.
2) For furniture category decrease and increase in profit pattern seen from year 2014 to 2017. Whereas for Office supplies and technology category steadily increase pattern.
3) Tamara Chand, Raymond Buch, Sanjit Chand, Hunter Lopez and adrian Barton are the top 5 customers who contributing in the profit to the company.
4) In year November 2015 the highest sale seen of all time.
5) 2017 has highest customer count of all time with number of 693 unique customers.
6) State California and New York has higbest sales.
