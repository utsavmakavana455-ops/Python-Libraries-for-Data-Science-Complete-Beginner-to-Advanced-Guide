# Python-Libraries-for-Data-Science-Complete-Beginner-to-Advanced-Guide
A comprehensive guide to the most important Python libraries used in Data Science, Data Analytics, Machine Learning, and AI. This repository includes theory, practical examples, datasets, visualizations, and mini-projects using NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, and other popular libraries.


import pandas as pd

 

data = {

    "Name": ["Ali", "Maria", "John", "Sara", "David", "Emma"],

    "Age": [25, 32, 45, 29, 40, 36],

    "Department": ["HR", "Finance", "IT", "HR", "IT", "Finance"],

    "Salary": [3000, 4000, 5000, 3200, 5500, 4200]

}

 

df = pd.DataFrame(data)

print(df)





Tasks

Basic Exploration

Print the first 3 rows of the DataFrame.

Use .info() and .describe() to learn about the dataset.

New Column

Create a column called AgeGroup:

“Young” if Age < 30

“Mid” if 30–39

“Senior” if 40+

Summaries

Count how many employees are in each AgeGroup.

Find the average salary per department.

Visualizations

Create a bar chart showing the average salary per department.

Create a histogram of employee ages.

Create a line plot showing salaries of employees in order of Age (youngest to oldest).
