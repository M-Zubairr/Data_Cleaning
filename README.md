<h1>Data Cleaning and Exploratory Data Analysis on python</h1>

 
**Earing on the "house price prediction" data set. 
Liaries used; numpy, pandas, missingno & matplotlib**
  
 <h2>Step 1: Initial steps</h2>

-Deleted unncessary columns
-Made a user defined function "info" to get get number of nulls and unique values in a column instantly
-Made a user defined function "ranges" to get minimum, maximum, mean, median and mode in a coloumn instantly
-Made a column to uniquely identify every row (this is used later)

<h2>Step 2 : Removed data entry errors</h2>

-Replaced blank spaces and other data entry errors with null values

<h2>Step 3 : Identified the case of MNAR (Missing Not at Random)</h2>

-Used manobar library to visualize the trend of missing values /n
-Deleted those specific rows as it was less than 5% of the original data

<h2>Step 4 : Replaced null values with appropriate values</h2>

-Used the documentation given with the csv file to understand the relationship between columns
-Used EDA to detect outliers
-Replaced null values with appropriate values
