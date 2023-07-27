# home-sales-big-data-challenge
Homework 22 for the big data challenge module of Datavis bootcamp

# Home_Sales

## Project Description
In this project, SparkSQL was employed to determine key metrics about home sales data. The utilization of SparkSQL involved various operations such as creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying that the table has been uncached.

## Data
Visit [Home Sales Dataset](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv) to see dataset used in this project. 

## Analysis
**Query 1:** Average price for a four-bedroom house sold for each year

  <img width="147" alt="image" src="https://github.com/priyajainnyc/home-sales-big-data-challenge/assets/124069684/aaec30fa-0d4c-475b-a7ce-61741aaf1fa4">

**Query 2:** Average price of a home for each year it was built that has three bedrooms and three bathrooms 
 
  <img width="155" alt="image" src="https://github.com/priyajainnyc/home-sales-big-data-challenge/assets/124069684/37d22975-b6e5-409a-a2db-4a9725912a4f">

**Query 3:** Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet

  <img width="155" alt="image" src="https://github.com/yeyanwang/Home_Sales/assets/120543690/d1aafe21-d5b5-43b7-b2e2-66af0c84b73c">

**Query 4:** View rating for homes costing more than or equal to $350,000 group by view
 
  <img width="175" alt="image" src="https://github.com/yeyanwang/Home_Sales/assets/120543690/8064515d-6c0c-4ae2-bbf1-6a6ef6169884">

**Compare Run Times on Query 4**
1. Uncache Runtime: 1.3247380256652832 seconds
2. Cached Runtime: 0.5603408813476562 seconds
3. Runtime with the parquet DataFrame: 0.9041104316711426 seconds
