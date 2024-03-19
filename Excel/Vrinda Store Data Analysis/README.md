# Data Analysis of Vrinda Store Annual Report 2022 

## Problem Statement
Vrinda store wants to create an annual sales report for 2022. So that, owner can understand their customers and grow more sales in future.

## Data Cleaning and Preparation:
- Step:1 Check Columns for null or duplicate values.
- Step:2 Gender column don't have consistent data somewhere their is M for men and somewhere W for women. Select column and replce M with Men. Repeat same procedure for women too.
- Step:3 Column quantity has some issue with somewhere value is in number format somewhere value is in number format. Change all value in numeric.
- Step:4 Create new column age group on the basis of age column. Three groups are created in this column, Adult, Teenager and Senior.
- Step:5 Create new column for a month extract month from colummn date.

## Data Analysis:
1) Orders vs sales:
To create visualization select sum of amount and count of order id as value. And Month as row. Use secondary axis in visualization because the one value is in million and another one is in thousand. copy it to dashboard.

2) Men Vs Womwn:
To create pie chart visualization of Men vs Women, select sum of amount as value And Gender as row. copy it to dashboard.

3) Order Status:
To create pie chart of order status select status as row and count of order id as value. copy it to dashboard.

4) Sales of top 5 States:
To create the bar chart of states select state as row and sum of amount as value. Apply filter of top 5 to the pivot table. Add visualization of horizontal bar. copy it to dashboard.

5) Age and Gender: 
To create bar chart of age and gender select age group as row and Gender as column. Select order id as value. Convert it into percentage. Copy it to dashboard.

6) Channels:
To create channel pie chart select channel as row and order id as value. Convert it into percentage. Copy it to dashboard.

7) Add month, channel and category slicer to the dashboard. Sync all the visualization with the slicers.

## Insights:
1) The highest sales are in the month of March.
2) Womans contribute more to generate profit as compared to men.
3) Most of the items are delivered.
4) Maharashtra, Karnataka, Utter Pradesh, Telangana and Tamilnadu are top 5 states contributing to generate more profit.
5) Womens age group between 30 to 49 are prime customers.
6) Amazon is major channel for sales.

## Conclusions to improve Vrinda store sales:
Target women customers of age group between 30-49yrs live in Maharashtra, Karnataka and Utter Pradesh by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.

