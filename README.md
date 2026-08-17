# dataset_summery_repor
This repository contains a Google Colab notebook that generates a comprehensive dataset summary report for the Student_Dataset.csv file using Python and the Pandas library.
Analysis Steps Included
The notebook performs the following data exploration steps:

Dataset Loading: Loads the Student_Dataset.csv into a Pandas DataFrame.
Initial Inspection: Displays the first few rows, last few rows, and random samples of the dataset to get a preliminary view.
Shape and Information: Checks the number of rows and columns, lists column names, and provides detailed information including non-null counts and data types using df.info().
Data Types Overview: Presents a summary of data types for all columns.
Descriptive Statistics: Generates descriptive statistics for numerical columns, showing count, mean, standard deviation, min/max values, and quartiles using df.describe().
Basic Observations: Summarizes key findings such as the total number of rows and columns, available features, data types, and identifies columns with missing values.
Dataset
The Student_Dataset.csv contains simulated student information, including student IDs, names, ages, courses, marks, attendance percentages, and city of residence.
