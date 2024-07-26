# Multiple Linear Regression Analysis

This repository contains a Jupyter notebook that demonstrates a multiple linear regression analysis using Python. The dataset used for this analysis consists of startup data to predict profit based on various independent variables.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)


## Introduction

This project aims to predict the profit of startups based on their spending on R&D, Administration, and Marketing using multiple linear regression. The analysis is performed in a Jupyter notebook, leveraging libraries such as Pandas, NumPy, and Matplotlib.

## Dataset

The dataset used in this analysis is `50_Startups.csv`, which contains the following columns:
- `R&D Spend`: The amount spent on research and development.
- `Administration`: The amount spent on administration.
- `Marketing Spend`: The amount spent on marketing.
- `State`: The state in which the startup operates.
- `Profit`: The profit of the startup.

## Features
- `Importing the dataset`: Load the dataset using Pandas.
- `Exploring the data`: Display the first few rows of the dataset to understand its structure.
- `Encoding categorical data`: Encode the state column using one-hot encoding.
- `Splitting the data`: Split the dataset into training and testing sets.
- `Training the model`: Use the training set to fit a multiple linear regression model.
- `Predicting and visualizing`: Make predictions on the test set and evaluate the model.
