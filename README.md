# Home_Sales

---

## Summary

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

---

## Criteria

- [x] A Spark DataFrame is created from the dataset. (5 points)
- [x] A temporary table of the original DataFrame is created. (10 points)
- [x] A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. (5 points)
- [x] A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. (5 points)
- [x] A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. (5 points)
- [x] A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) (10 points)
- [x] A cache of the temporary "home_sales" table is created and validated. (10 points)
- [x] The query from step 6 is run on the cached temporary table, and the run time is computed. (10 points)
- [x] A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. (10 points)
- [x] A temporary table of the parquet data is created. (10 points)
- [x] The query from step 6 is run on the parquet temporary table, and the run time is computed. (10 points)
- [x] The "home_sales" temporary table is uncached and verified. (10 points)

---

## Working Notes

This challenge was actually something I felt incredibly comfortable with as i'm comfortable with using SQL. It made using SparkSQL incredibly simple. I think the main exercise here was to demonstarate the different load times using different methods when using big data. 

This makes my last weekly challenge for this Bootcamp! WOO!

---
