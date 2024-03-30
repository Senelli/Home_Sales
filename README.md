# Home_Sales
- The file Home_Sales_starter_code.ipynb was renamed to Home_Sales.ipynb.
- The necessary PySpark SQL functions were imported for this assignment.
- The data from the file home_sales_revised.csv provided in the starter code was read into a Spark DataFrame.
- A temporary table named home_sales was created to hold the data.
- The following questions were answered using SparkSQL:
    - The average price for a four-bedroom house sold for each year was calculated and rounded to two decimal places.
    - The average price of a home for each year it was built, given that it has three bedrooms and three bathrooms, was calculated and rounded to two decimal places.
    - The average price of a home for each year it was built, considering it has three bedrooms, three bathrooms, two floors, and is at least 2,000 square feet in size, was calculated and rounded to two decimal places.
    - The average price of a home per "view" rating for homes with an average price greater than or equal to $350,000 was determined. The runtime for this query was also calculated and rounded to two decimal places.
- The temporary table home_sales was cached to optimize subsequent queries.
- It was verified whether the temporary table home_sales was cached.
- The cached data was utilized to run the last query mentioned in step 5d, calculating the average price of a home per "view" rating for homes with an average price greater than or equal to $350,000. The runtime was determined and compared with the uncached runtime.
- The formatted parquet home sales data was partitioned by the "date_built" field.
- A temporary table was created for the parquet data.
- The last query mentioned in step 5d was run, calculating the average price of a home per "view" rating for homes with an average price greater than or equal to $350,000. The runtime was determined and compared with the uncached runtime.
- The home_sales temporary table was uncached.
- It was verified that the home_sales temporary table was successfully uncached using PySpark.