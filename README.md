# Air-Pollution-Analysis
This repository contains a comprehensive analysis of global air pollution using R. The analysis explores various aspects of air pollution data, including missing value handling, data visualization, and correlation analysis. The dataset used in this project is publicly available on Kaggle and must be downloaded manually due to copyright restrictions.

Features of the Analysis

Data Loading and Preprocessing:

Reads the dataset from a local file after manual download.

Handles missing values by filling numeric columns with their mean and non-numeric columns with their mode.

Data Exploration:

Displays the structure of the dataset.

Separates numeric and non-numeric columns for targeted analysis.

Visualization:

Histogram and density plots of Air Quality Index (AQI) values.

Scatter plot to explore the relationship between AQI and CO AQI values.

Correlation Analysis:

Calculates the correlation matrix for numeric columns.

Visualizes the correlation matrix using a correlation plot.

Prerequisites

Ensure that R is installed on your system. The following R packages are required:

tidyverse

ggplot2

readr

corrplot

You can install these packages using the following command in R:

install.packages(c("tidyverse", "ggplot2", "readr", "corrplot"))

Dataset

The dataset is available on Kaggle:Global Air Pollution Dataset.

You must manually download the dataset and place it in the same directory as the R script. Save it as global_air_pollution_dataset.csv

Results

Missing values in the dataset are effectively handled.

The AQI distribution is visualized using histograms and density plots.

The relationship between AQI and CO AQI values is illustrated using scatter plots.

A detailed correlation matrix is provided for numeric columns, highlighting relationships between variables.

How to Use

Download the dataset from Kaggle: Global Air Pollution Dataset.

Save the dataset as global_air_pollution_dataset.csv in the same directory as the R script.

Clone the repository:

git clone https://github.com/hk1105/https://github.com/hk1105/Air-Pollution-Analysis-name.git

Open the R script in RStudio.

Run the script to reproduce the analysis.
