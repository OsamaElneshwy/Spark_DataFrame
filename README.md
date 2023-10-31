# PySpark DataFrame hands on experience

## In this hands on
- I used walmart_stock.csv dataset

![Screenshot from 2023-10-31 19-02-19](https://github.com/OsamaElneshwy/Spark_DataFrame/assets/36084719/93dae8c1-5054-4f99-be04-bf8b5ab079f8)

- I used test1.csv dataset

![Screenshot from 2023-10-31 19-20-33](https://github.com/OsamaElneshwy/Spark_DataFrame/assets/36084719/360c8075-22f0-459e-a8c1-145d00203fda)

- I used test3.csv dataset

![Screenshot from 2023-10-31 19-26-56](https://github.com/OsamaElneshwy/Spark_DataFrame/assets/36084719/97b2a38d-97d1-41b7-8602-552fa3f463e3)

## To answer some questions:
### Task1
- Load the Walmart Stock CSV File, have Spark infer the data types.
- What are the column names?
- What does the Schema look like?
- Print out the first 5 salary.
- Use describe() to learn about the DataFrame.
- Create a new dataframe with a column called HV Ratio that is the ratio of the High Price versus volume of stock traded for a day.
- What day had the Peak High in Price?
- What is the mean of the Close column?
- What is the max and min of the Volume column?
- How many days was the Close lower than 60 dollars?
- What percentage of the time was the High greater than 80 dollars?
- What is the Pearson correlation between High and Volume?
- What is the max High per year?
- What is the average Close for each Calendar Month?

### Task2
- Read "test1" dataset
- Display Salary of the people less than or equal to 20000
- Display Salary of the people less than or equal to 20000 and greater than or equal 15000

### Task 3
- Read "test3" dataset
- Display dataset
- Display schema
- Group by "Name" column and using sum function on "salary" column
- Group by "Name" column and using avg function on "salary" column
- Group by "Departments" column and using sum function on "salary" column
- Group by "Departments" column and using mean function on "salary" column
- Group by "Departments" column and using count function on "Departments" column
- Apply agg to using sum function get the total of salaries

