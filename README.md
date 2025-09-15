📊 Data Analysis Assignment
Overview

This project demonstrates basic data analysis and visualization skills using Python, Pandas, Matplotlib, and Seaborn.
The Iris dataset was chosen, saved to CSV, and reloaded with Pandas for analysis.

The workflow includes:

Loading and exploring the dataset

Cleaning and analyzing the data

Creating visualizations to uncover insights

Tasks Completed
✅ Task 1: Load and Explore Dataset

Loaded the Iris dataset from sklearn.datasets

Saved it as iris.csv and reloaded it using Pandas

Displayed the first 5 rows using .head()

Checked data types and missing values with .info() and .isnull().sum()

Cleaned the dataset (no missing values found)

✅ Task 2: Basic Data Analysis

Computed descriptive statistics with .describe()

Grouped the data by species (target) and calculated the mean petal length

Insights:

Setosa → smallest average petal length

Virginica → largest average petal length

Versicolor → lies in between

✅ Task 3: Data Visualization

Created four types of plots with Matplotlib and Seaborn:

Line Chart → Petal length trend across samples

Bar Chart → Average petal length per species

Histogram → Distribution of sepal length

Scatter Plot → Relationship between sepal length and petal length (with species distinction)

Each plot is customized with titles, axis labels, and legends.

Technologies Used

Python 3

Pandas → data loading, cleaning, and analysis

Matplotlib & Seaborn → data visualization

Scikit-learn → for accessing the Iris dataset

How to Run the Project

Clone or download the repository.

Install required libraries (if not already installed):

pip install pandas matplotlib seaborn scikit-learn


Open the Jupyter Notebook and run all cells:

jupyter notebook assignment.ipynb


Author

Stacy Gathoni
