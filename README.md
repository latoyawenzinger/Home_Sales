# Home_Sales

## Purpose

The goal of this assignment was to successfully use SparkSQL to discover insights in the home sales data. Spark was also used to:
- create temporary views
- partition the data on 'date_built' field
- cache and uncache the temporary table

## Questions answered using SparkSQL:
- What is the average price for a four-bedroom house sold for each year? 
- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 
- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query (both answered using original and partitioned data).
- Each runtime was compared between uncached, cached, and cached/partioned data. 

## Summary

![image](https://github.com/latoyawenzinger/Home_Sales/assets/115582691/03585893-5c52-4940-9198-f87a20674c64)
![image](https://github.com/latoyawenzinger/Home_Sales/assets/115582691/bae92fdf-b5a9-40b3-bbdd-bc6ff41940ed)
![image](https://github.com/latoyawenzinger/Home_Sales/assets/115582691/ef41299d-6078-48c8-b5b9-e02fb544a753)



