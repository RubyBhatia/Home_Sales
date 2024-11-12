HOME SALE- CHALLENGE-22 

With the use of SparkSQL to determine key metrics about home sales data in this project. There is also use of Spark to create temporary 
table as well as verify that the table has been uncached. 

Methodology: 

1. Import the essential PySpark SQL functions and load the home_sales_revised.CSV dataset into a Spark DataFrame.
2. Then, create a temporary table named home_sales for analysis.

Analysis: 

1. Evaluate the average price of four-bedroom house sold each year (rounding to two decimal places).
2. Calculate the average price of homes built in each year that have three bedrooms and three bathrooms (rounding to two decimal places). 
3. Identify the average price of homes with three bedrooms, three bathrooms, two floors and at least 2,000 square ft built for each year (rounding to two decimal places).
4. Examine the average price of homes based on their "view" rating, where the average price is $350,000 or higher.
5. Analysed the query's runtime and round the result to two decimal places. 

Summary: 
 Cach the home_sales temporary table and verify its cached status. Use the cached data to rerun the query for the average 
 home price per "view" rating (Where the price is $350,000 or more) and compare its runtime to the uncached version. 
 Partition the formatted parquet home sales data by date_built, create a temporary table from it, and rerun the same query, 
 again comparing runtimes. Finally, uncache the home_sales table and confirm it has been successfully uncached. 

Reference: 

1. BCS(Xpert Learning ASSISTANCE) and classroom activities materials, 
2. Classmates and peer assistance,
3. AI tools like Gemini and ChatGpt


