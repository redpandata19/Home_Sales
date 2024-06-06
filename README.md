# Home_Sales

Jupyter notebook: https://github.com/redpandata19/Home_Sales/blob/main/Home_Sales.ipynb

Background (UNC Bootcamp): In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.


Questions to answer: 
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Dependencies: 
import findspark
findspark.init()
from pyspark.sql import SparkSession
import time
import os
from pyspark import SparkFiles
