
# Data Preprocessing Tools

This repository contains a Jupyter Notebook that demonstrates essential data preprocessing techniques using Python. The notebook covers importing libraries, loading datasets, handling missing data, encoding categorical data, splitting datasets into training and test sets, and feature scaling.

## Contents

- **Importing Libraries**: Demonstrates how to import essential libraries like NumPy, Matplotlib, and Pandas.
- **Importing the Dataset**: Instructions for loading a dataset from a CSV file and separating features and the target variable.
- **Handling Missing Data**: Techniques for dealing with missing values in the dataset.
- **Encoding Categorical Data**: Methods to convert categorical data into numerical format.
- **Splitting the Dataset**: How to split the dataset into training and test sets.
- **Feature Scaling**: Normalizing features to improve the performance of machine learning algorithms.

## How to Use

1. Clone this repository to your local machine.
   ```sh
   git clone https://github.com/jaythecool/DataPreprocessingTools.git
2. Navigate to the project directory.
   ```sh
   cd DataPreprocessingTools
3. Install the necessary libraries.
   ```sh
   pip install numpy matplotlib pandas scikit-learn
4. Open the Jupyter Notebook.
   ```sh
   jupyter notebook DataPreprocessingTools.ipynb

## Dataset
The notebook uses a sample dataset Data.csv, which should be placed in the same directory as the notebook. The dataset contains the following columns:

- **Country**
- **Age**
- **Salary**
- **Purchased**

## Features
- **Handling Missing Data** : Replacing missing values with the mean of the column.
- **Encoding Categorical Data** : Using label encoding and one-hot encoding to convert categorical features.
- **Splitting the Dataset** : Using train_test_split from scikit-learn to divide the data.
- **Feature Scaling** : Applying standardization to normalize the feature values.

## Author
Jayesh Vengurlekar
