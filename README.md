# Super Store Performance Analysis
![](SuperStore.png)

## Introduction
This is a project on Super Store sales data from 2014 to 2018. This goal of this analysis is to gain insight into the company sales within the given time to help the company make profit-driven decisions.
The aim of this project is to come up with important business questions and provide valuable answers to help the company make data driven decisions.
## BUSINESS QUESTIONS
1.	What product category generated the most and least sales 
2.	Percentage of profit each region contributed to the total profit 
3.	Does region and product category affect  the time of delivery of items            
4.	What is the average profit per product category 
5.	What consumer segment had the highest profit/sale
6.	Number of profit or loss per product category, segment, and region
## THE DATASET
This data set contained 9945 rows of information with 21 columns. The data set included different categories of information. 
- ORDER INFORMATION: This includes order id, order date, ship date and ship mode.
- CUSTOMER INFORMATION: This includes customer id, customer name and segment.
- LOCATION INFORMATION: This includes country, city, state, postal code, and region.
- PRODUCT INFORMATION: This includes product id, category, subcategory, and product name.
- SALES INFORMATION: Sales price, quantity sold, discount and profit. 
## SKILLS DEMONSTRATED
- Data cleaning/Management
- Pivot tables
- Pivot charts
- Data visualization 
## DATA CLEANING
This data came with no duplicates or blanks so it was a bit easy to work with. To make ted at easir to look at, I hadto remove some colums. I removed the row id colum as it did not serve any purpose to the data and the transaction already had a unique identifier which is the order id.
I created a new column and called it “days to ship” and filled the column with values gotten from subtracting the order date from the ship date. This is done to know how long each purchase took to ship.
I also removed customer name as each customer already had a unique identifier which is the customer id.
I also removed the country column as all transactions were made in the same country.
I also created an extra column and called it profit or loss and used the if function on the profit column to locate losses and profit.

## KPI of the business
1.	Total revenue : the total revenue is the first most important KPI as it gives insight to how much the company generated during the given time.
This was gotten by using the sum function on the sales column
The toal revenue given was ----
2.	Total Profit: the total profit tells us how much the profit the company made and this is gotten by using the sum function on the profit colum . the profit the company made during the given time is –
3.	Profit Margin: this is the percentage the company generates as profit from the total revenue. This is gotten by dividing the total revenue by the total profit. The profit margin is 12%. This means that company made just 12% from its total revenue


