# Data Cleaning using Pandas

## Overview

This Python script utilizes the Pandas library to perform data cleaning on a given dataset. The dataset, stored in a CSV file named "Data-cleaning-for-beginners-using-pandas.csv," is loaded into a Pandas DataFrame for analysis and cleaning.

## Libraries Used

- Pandas
- NumPy
- Seaborn

## Data Exploration

The script begins by loading the dataset and examining its information, columns, and data types. It identifies missing values and provides a summary of the 'age' column using descriptive statistics and a box plot.

### Handling Outliers in 'Age' Column

Outliers in the 'age' column are addressed by calculating the Interquartile Range (IQR) and adjusting values beyond a specified threshold.

## Handling Missing Values

### Imputing Missing Values in 'Age' Column

Missing values in the 'age' column are imputed by replacing them with the mean age of the dataset, rounded to one decimal place.

### Imputing Missing Values in 'Rating' Column

Negative values in the 'rating' column are replaced with NaN, and missing values are imputed with the mean rating of the dataset.

### Imputing Missing Values in 'Established' Column

Negative values in the 'established' column are replaced with NaN, and missing values are imputed with the median established year of the dataset, rounded to one decimal place.

## Data Transformation

### Cleaning 'Salary' Column

The 'salary' column is cleaned by removing the dollar sign ($) and converting the values to numerical format.

### Column Name Standardization

Column names are converted to lowercase and spaces are replaced with underscores for consistency.

### Handling 'Easy Apply' Column

The 'easy_apply' column is converted to boolean values, replacing '-1' with False and any other values with True.

## Output

The cleaned DataFrame is printed to the console at various stages of the script for inspection.

---

Feel free to customize the readme file based on the specifics of your project and the level of detail you want to include.# Prepinsta-week-3-project-1
