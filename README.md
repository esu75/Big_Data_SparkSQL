# Big_Data_SparkSQL

In this project, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views,
partition the data, cache and uncache a temporary table, and verify that the table has been uncached

### Instructions
1.	Import the necessary PySpark SQL functions.
2.	Read the home_sales_revised.csv data 
3.	Create a temporary table called home_sales.
4.	Answer the following questions using SparkSQL:

   	i. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
      
      ii. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal 	     places.
      
      iii. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal
       	   to 2,000 square feet? Round off your answer to two decimal places.
      
      iv. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to 	    two decimal places.
      
5.	Cache your temporary table home_sales.

7.	Check if your temporary table is cached..	
9.	Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the 	 runtime and compare it to uncached runtime.
	
11.	Partition by the "date_built" field on the formatted parquet home sales data.
12.	Create a temporary table for the parquet data.
	
14.	Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it 	 to uncached runtime.
	
16.	Uncache the home_sales temporary table.
	
18.	Verify that the home_sales temporary table is uncached using PySpark.
