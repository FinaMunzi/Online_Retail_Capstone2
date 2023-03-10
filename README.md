# Capstone 2 Data Analysis in POSGRESSQL
--------------------------------------------------------------------------
### An analysis on Online Retail E-Commerce
--------------------------------------------------------------------------

[![Screenshot-2023-03-10-at-4-43-50-PM.png](https://i.postimg.cc/gkHrhNCq/Screenshot-2023-03-10-at-4-43-50-PM.png)](https://postimg.cc/0br8Rd2b)

----------------------------------------------------------------------------------------
[Link to dataset](https://www.kaggle.com/code/kmartin1/onlineretaildata-notebook/notebook)

An analysis of Online Retail E-Commerce on the performance and customer behavioural based on country using POSGRESSQL.
The interactive dashboard shows the highest transacted country and the least transacted country.
1.	Pie chart shows the number of orders received from each country with filter.
2.	Column chart shows the timeline of the sales transactions quarterly based on annual data collected from Q4 2010 to Q4 2011.
3.	The world map highlighted the most number of customer with darker blue shade to least number of customer withh lighter blue shade.
4.	The line chart point out the performance of the transactions based on products. The exponential line indicates that the company was able to achieve profitable returns overall. 

POSGRESSQL Analysis
---------------------------------------------------------------------------------

Most profitable product
[![Most-Profitable-product.png](https://i.postimg.cc/CxF1Fk6P/Most-Profitable-product.png)](https://postimg.cc/crbZhgWw)

Quarterly sales progress
[![Monthly-performance.png](https://i.postimg.cc/QNbw271x/Monthly-performance.png)](https://postimg.cc/Sjng8Jgw)

Number of customers by Country
[![customer-by-country.png](https://i.postimg.cc/YqFg46Rt/customer-by-country.png)](https://postimg.cc/rK8z3t7H)

ERD and SCHEMA Table Diagram
--------------------------------------------------------------------------------------

Schema Table Diagram
[![Schema-table.png](https://i.postimg.cc/7YYYCcz3/Schema-table.png)](https://postimg.cc/0rFqFVcj)

ERD
[![ERD.png](https://i.postimg.cc/5tcVmkXk/ERD.png)](https://postimg.cc/fVvpzCjx)

## I've learned that :
__________________________________________________________________________

•	SQL is a powerful tool which allows us to work with bigger data as compared to excel.

•	The queries can be coded as per what we want to find and POSGRESSQL can point out the issues on the individual line.

•	When writing the coding, one must mindful with what is written as it is involving big data and it will be challenging to rectify the data if the issue is on bigger digit number.

•	The main part of the coding is the first line when executing to read or create the data.

•	The data shows that highest number of customers are from United Kingdome given with 3950.

•	The analysis provides overall picture of the e-commerce performance of the company and areas to improve. 

## Changes made from original data.
----------------------------------------------------------------------------

•	Data cleaning – edited date in excel to ISO 8601. Created table for customer, and unknown transaction in POSGRESSQL using conditions.
  Altered column from TEXT dataset type to DATE, TIME, MONEY dataset type.
  
  [![sample-of-alter-table.png](https://i.postimg.cc/FH8q4dmf/sample-of-alter-table.png)](https://postimg.cc/Js3K3hsm)

•	Run queries for various analysis to understand the data and derived with the above results.

•	Download the data in CSV format for Dashboard creation.

•	Created pivotable, charts, and added slicer.

•	Created interactive dashboard.

## Reflections
----------------------------------------------------------------------------
The analysis of online retail market have given me the opportunity to understand the consumer and production market in e-Commerce.
With a click away, it shows how powerful the technology have emerge especially in e-commerce where it allows the customers to 
purchase the product with the comfort of their customer. The data allows the e-commerce companies to focus on the area of improvement and area of interest with highest transaction.

The interactive dashboard allows me to compare the data, filter the data and focus on specific interest when need to. 
When we have big data file, POSGRESSQL does a magic by running the queries at ease

----------------------------------------------------------------------------
[Contact me via LinkedIn](https://www.linkedin.com/in/shafinabegum)








