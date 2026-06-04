# 📊 Task 1: Exploring and Visualizing the Iris Dataset
📌 Internship

DevelopersHub Corporation
Data Science & Analytics Internship

# 🎯 Objective

The objective of this task is to understand the structure of a dataset and perform Exploratory Data Analysis (EDA) using Python. The focus is on data loading, inspection, and visualization to extract meaningful insights from the Iris dataset.

# 📂 Dataset

The Iris dataset contains measurements of iris flowers and includes the following features:

Sepal Length
Sepal Width
Petal Length
Petal Width
Species (Target Variable)

The dataset is loaded using Seaborn’s built-in function:

sns.load_dataset("iris")
🛠️ Tools & Libraries Used
Python
Pandas
Matplotlib
Seaborn
 Google Colab
# 📊 Project Workflow
1. Data Loading
The dataset was imported using Seaborn.
The first few rows were displayed using .head().
2. Data Understanding
Dataset shape was checked using .shape.
Column names were explored using .columns.
Data types and non-null values were inspected using .info().
Statistical summary was generated using .describe().
3. Data Cleaning
Missing values were checked using .isnull().sum().
Duplicate records were identified using .duplicated().sum().
Duplicate values were removed to ensure data consistency.
4. Exploratory Data Analysis (EDA)
# 📌 Scatter Plot

Used to analyze relationships between features such as sepal length and petal length.

# 📌 Histogram

Used to understand the distribution of sepal length.

# 📌 Box Plot

Used to detect data spread and identify potential outliers across different species.

# 📈 Key Insights
The dataset contains 150 samples and 5 columns.
No missing values were found in the dataset.
Duplicate values were identified and removed.
Petal length and petal width show a strong correlation.
Different species exhibit clear separation in feature distributions.
# 📌 Results

The visualization analysis provided insights into:

Distribution of features
Relationships between variables
Class-wise separation of iris species

These insights help in understanding the dataset structure and its suitability for machine learning tasks.

# 🚀 End of Task

This task demonstrates basic data exploration and visualization techniques using Python libraries.
