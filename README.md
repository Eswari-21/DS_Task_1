# Descriptive Statistics & Correlation Heatmap for Iris Dataset

## Overview
This Python script performs exploratory data analysis (EDA) on the Iris dataset by calculating key descriptive statistics and visualizing the relationships between numerical features through a correlation heatmap.

## Requirements
Ensure you have the following Python libraries installed:
pip install pandas seaborn matplotlib

## Dataset
The script expects a CSV file named iris_sample.csv with the following columns:

sepal_length: Sepal length in cm

sepal_width: Sepal width in cm

petal_length: Petal length in cm

petal_width: Petal width in cm

species: Iris flower species (e.g., Setosa, Versicolor, Virginica)


## Descriptive Statistics
The script computes and displays the following statistics for each numerical feature:

Summary Statistics: Count, mean, standard deviation, min, 25th percentile, median (50th percentile), 75th percentile, max

Mean: Average value

Median: Middle value when data is sorted

Mode: Most frequent value

Variance: Measure of data spread

Standard Deviation: Measure of data dispersion

Skewness: Measure of data asymmetry

Kurtosis: Measure of data peakness

## Correlation Heatmap
The script calculates the pairwise correlation coefficients between numerical features and visualizes them using a heatmap:

Positive Correlation: Values close to +1 (e.g., petal_length and petal_width)

Negative Correlation: Values close to -1 (e.g., sepal_width and petal_length)

No Correlation: Values close to 0

The heatmap is generated using Seaborn's heatmap() function with the 'coolwarm' colormap and annotations for clarity.
