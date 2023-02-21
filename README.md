# Machine Learning Capstone Project

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)

## Description

This code performs data analysis and clustering on the "US Arrests" dataset. The dataset contains information about crime rates in different states of the United States, including murder, assault, and rape.

The analysis includes data inspection, exploratory data analysis (EDA), correlation analysis, hierarchical clustering, and K-means clustering.

The code uses various Python libraries, including NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn, and itertools.

The data inspection section loads the data and inspects its shape and null values. EDA includes creating scatterplots, a bar chart to show which states have the highest number of crimes, and a bar chart to show which states have the highest crime rate.

The correlation analysis section creates a heatmap to show the correlation between different variables in the dataset.

The hierarchical clustering section performs hierarchical clustering with different linkage methods and plots the results in dendrograms.

The K-means clustering section performs K-means clustering and visualizes the resulting clusters using scatterplots.

Overall, this code provides a comprehensive analysis of the US Arrests dataset and demonstrates how to perform clustering using Python libraries.

## Installation

First of all, make sure to download UsArrests.csv provided by the Data Science Course.

Then, in order to use this code, first ensure that you have the following libraries installed:
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install them by running the following command in your terminal:
```pip install numpy pandas seaborn matplotlib scikit-learn```


Once you have installed the necessary libraries, you can run the code in your preferred environment, such as Jupyter Notebook.

## Usage

After installing the necessary libraries, you can simply run the provided code to perform hierarchical clustering and K-means clustering on the US crime data. The code loads the data, scales the variables, and performs the clustering analysis. 

The output of the code includes several plots that show the relationships between crime rates and urban population, as well as the resulting clusters from the clustering analysis.

To use the code on your own dataset, simply replace the input data with your own data and adjust the code as needed. You may also want to adjust the clustering parameters to fit your specific data and research question.
