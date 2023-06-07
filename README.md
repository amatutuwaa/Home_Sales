# Home Sales
Home Sales Data Analysis with SparkSQL

Welcome to my Home Sales Data Analysis repository! In this project, I utilize the power of SparkSQL to derive key metrics from home sales data. Through Spark, I create temporary views, partition the data, cache and uncache temporary tables, and verify table caching status.


##Project Overview

In this project, I work with a dataset of home sales data and leverage SparkSQL to answer important questions about the data. The tasks include creating temporary views, performing calculations on the data, and comparing query runtimes. Here is an overview of the tasks involved:

 1. Rename the notebook file from Home_Sales_starter_code.ipynb to Home_Sales.ipynb.
 2. Import the necessary PySpark SQL functions for the analysis.
 3. Read the home_sales_revised.csv data into a Spark DataFrame.
 4. Create a temporary table named "home_sales" to work with the data.
 5. Use SparkSQL to answer the following questions:
 6. Determine the average price for a four-bedroom house sold each year, rounding the answer to two decimal places.
 7. Calculate the average price of homes for each year they were built, considering only those with three bedrooms and three bathrooms.      
 8. Find the average price of homes for each year that have three bedrooms, three bathrooms, two floors, and a minimum area of 2,000 square feet. 
 9. Determine the "view" rating for homes that cost $350,000 or more. Measure the runtime of this query, rounding the answer to two decimal places.
 10. Cache the "home_sales" temporary table and verify its caching status.
 11. Execute the query from step 5 using the cached data, and measure its runtime. Compare the runtime with the uncached execution.
 12. Partition the home sales data by the "date_built" field and store it in the Parquet format.
 13. Create a temporary table for the Parquet data.
 14. Run the query from step 5 on the Parquet temporary table and measure its runtime. Compare the runtime with the uncached execution
 15. Uncache the "home_sales" temporary table and verify its uncached status using PySpark.
 
 
 ##Repository Contents
 1. Home_Sales.ipynb: The Jupyter Notebook that contains the code for the Home Sales Data Analysis using SparkSQL.
 
