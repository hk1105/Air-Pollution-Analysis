# Air Pollution Analysis

This repository provides a comprehensive analysis of global air pollution using **R**. It explores various aspects of air pollution data, such as handling missing values, data visualization, and correlation analysis. The dataset used in this project is publicly available on **Kaggle** and must be downloaded manually due to copyright restrictions.

---

## 🔍 Features of the Analysis

### 📥 **Data Loading and Preprocessing:**
- Loads the dataset from a local file (manual download required).
- Handles missing values by:
  - Filling **numeric** columns with their mean.
  - Filling **non-numeric** columns with their mode.

### 📊 **Data Exploration:**
- Displays the structure of the dataset.
- Separates **numeric** and **non-numeric** columns for targeted analysis.

### 📈 **Visualization:**
- **Histograms** and **density plots** to visualize the Air Quality Index (AQI) distribution.
- **Scatter plot** to explore the relationship between AQI and CO AQI values.

### 🔗 **Correlation Analysis:**
- Calculates the **correlation matrix** for numeric columns.
- Visualizes the correlation matrix using a **correlation plot**.

---

## 📌 Prerequisites

Ensure that **R** is installed on your system. The following R packages are required:

- `tidyverse`
- `ggplot2`
- `readr`
- `corrplot`

You can install these packages using the following command in R:

```R
install.packages(c("tidyverse", "ggplot2", "readr", "corrplot"))
```

## 📂 Dataset
The dataset is available on Kaggle: Global Air Pollution Dataset.

## 📥 How to Download:
Manually download the dataset from Kaggle.

Save the dataset as global_air_pollution_dataset.csv in the same directory as the R script.

## 📝 Results
- Missing values in the dataset are handled effectively.

- AQI distribution is visualized using histograms and density plots.

- The relationship between AQI and CO AQI values is illustrated with scatter plots.

- A detailed correlation matrix highlights the relationships between numeric variables.

## ⚙️ How to Use
Download the dataset from Kaggle: Global Air Pollution Dataset.

Save the dataset as global_air_pollution_dataset.csv in the same directory as the R script.

## Clone the repository:
```
git clone https://github.com/hk1105/Air-Pollution-Analysis-name.git
```
Open the R script in RStudio.

Run the script to reproduce the analysis.

_Enjoy exploring global air pollution trends with this analysis!_
