# Pandas-Data-Science-Tasks

This repository contains a set of real-world data science tasks completed using the Python Pandas library.

## Setup

### Installing Jupyter Notebook

Follow the instructions [here](https://jupyter.readthedocs.io/en/latest/install.html) to install Jupyter Notebook.

### Installing Pandas library

Refer to the official Pandas documentation [here](https://pandas.pydata.org/pandas-docs/stable/install.html) for instructions on installing the Pandas library.

## Background Information

In this project, we leverage Python Pandas and Matplotlib to analyze and answer business questions about 12 months' worth of sales data. The dataset includes hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

### Data Cleaning

Tasks during this section include:

- Drop NaN values from DataFrame
- Remove rows based on a condition
- Change the type of columns (`to_numeric`, `to_datetime`, `astype`)

### Data Exploration

Once we have cleaned up our data, we move to the data exploration section. In this section, we explore 5 high-level business questions related to our data:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisements to maximize the likelihood of customers buying a product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

To answer these questions, we use various Pandas and Matplotlib methods, including:

- Concatenating multiple CSVs together to create a new DataFrame (`pd.concat`)
- Adding columns
- Parsing cells as strings to make new columns (`.str`)
- Using the `apply()` method
- Using `groupby` to perform aggregate analysis
- Plotting bar charts and line graphs to visualize our results
- Labeling our graphs

Feel free to explore the Jupyter Notebook files in this repository for detailed code implementations and visualizations.
