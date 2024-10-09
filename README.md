# LITA-Class-Documentation
This is where I document my first project while learning Data Analysis  With The Incubator Hub

### Project Title: Sales Analysis 

### Project Overview
The Data Analysis Project Aims To Generate Insight into the sales performance of the  company Project over the past year. 
By analysing the various parameters in the data received, I seek to gather enough insight to make reasonable descisions 
which then enable me to tell compelling stories around the data from the insight gotten and to know the best  performance from the data.

### Data Source
The primary source of data used here is “international breweries .csv” with  1048 rows from the year 2017 to 2019 which was provided by our Trainer “Mr Femi” .

### Tools Used
  - Microsoft Excel for Data Cleaning.
  - Structered Query Language (SQL) for Querying the Data

### Data Cleaning and Preparation
In the initial phase of the data cleaning and preparations, I perform the following action Using Excel;
  -	Data Loading and inspection.
  -	Data Cleaning and Formatting 

### Exploratory Data Analysis
EDA Involved the exploring of the data to answer some questions about the data such as;
-	What is the total profit
-	What is the total profit for each country
-	Which year had the highest profit.
-	What is the total profit for the country Nigeria in the last 3 year  (2017, 2018,2019).
-	What is the total profit for each brand in nigeria in year ‘2017’
-	What is the total profit for each brand in Nigeria in the last 3 years ( 2017, 2018 and 2019)
-	What is the total profit for ‘Hero Brand’ in Nigeria in year 2017
-	Categorize Countries into their language  such as Nigeria and Ghana would be ‘Anglophone’ & Benin, Togo and Senegal would be ‘Francophone’. Also Calculate Their Profit.  
-	What is the total quantity sold 
-	What is the total quantity sold per brand
-	What is the overall sales trend
-	What is the total sales per country
-	What is the total profit by sales rep
-	What brand had the highest sales in year ‘2019’


  #### Using SQL To Answer The Questions Above
  1)  What is the total profit
    
```SQL
SELECT SUM(profit) As Total_Profit
FROM international_breweries
```

```SQL
SELECT * FROM TABLE1
WHERE CONDITION = TRUE
```
https://github.com/Homololamie/LITA-Class-Documentation/blob/main/PIE%20CHART.PNG
