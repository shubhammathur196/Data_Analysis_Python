# Repository Name
This repository contains two Python projects, Python Diwali Sales Analysis and Student Performance Analysis. Both projects aim to provide insights into different data sets using Python.

## Python Diwali Sales Analysis
Python Diwali Sales Analysis is a project that analyzes Diwali sales data to gain insights into customer behavior, popular products, and top-performing states. The project utilizes several libraries such as numpy, seaborn, matplotlib, and pandas.

### Data Loading and Cleaning
The first step is to load the dataset into a pandas dataframe and clean the data. The dataset used in this project is "Diwali Sales Data.csv". The following steps were taken to clean the data:

Drop unnecessary columns ("Status", "unnamed1")
Drop rows with null values
Change the data type of the "Amount" column from object to integer
### Exploratory Data Analysis
The project explores the data and provides insights into customer behavior and popular products.

Gender: There are more female buyers with a larger purchasing power compared to men. The most popular product categories among females are Food, Clothing, and Electronics.
Age: Customers between the ages of 26 and 35 are the largest group of buyers. The most popular product categories among this age group are Food, Clothing, and Electronics.
Top States: The top states in terms of the number of orders are Uttar Pradesh, Maharashtra, and Karnataka. The top states in terms of sales are Uttar Pradesh, Maharashtra, and Karnataka.
Marital Status: Married customers tend to spend more than unmarried customers. Women who are married and between the ages of 26 and 35 tend to purchase more items than other groups.
Occupation: Customers in the IT, Healthcare, and Aviation industries tend to spend more than customers in other industries.
Product Category: The most popular product categories are Food, Clothing, and Electronics. The top-selling products are in the Food, Clothing, and Electronics categories.
### Conclusion
The project concludes that women who are between the ages of 26 and 35, are married, and work in the IT, Healthcare, and Aviation industries in the states of Uttar Pradesh, Maharashtra, and Karnataka, are inclined to purchase items from the Food, Clothing, and Electronics categories.

## Student Performance Analysis
Student Performance Analysis is a project that analyzes the performance of students based on their scores in various subjects. The data is obtained from a CSV file named 'Student.csv'. The project uses various libraries such as Pandas, Seaborn, and Numpy to perform data cleaning, relationship analysis, and data visualization.

### Data Cleaning
The initial step was to clean the data. The project checked for null values and filled them with the mean of the column. Also, it dropped some columns that were not required for the analysis.

### Relationship Analysis
After cleaning the data, the project analyzed the relationship between various features such as math score, reading score, gender, and lunch. Seaborn was used to plot a heat map, a pair plot, and scatter plots to visualize the relationships between the features. The project also generated a histogram and a box plot to visualize the distribution of scores.

Overall, both projects provide a detailed analysis of data sets using Python, providing insights and helping identify the factors affecting the respective areas.
