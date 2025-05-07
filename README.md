# Pulsar Candidate Prediction Analysis

This R script (`pulsarPrediction.R`) performs exploratory data analysis on a pulsar candidate dataset. 
It includes visualizations and statistical summaries to help understand the underlying patterns in the features.

## 📁 Files

- `pulsarPrediction.R`: The main analysis script.
- `pulsar_data.csv`: The dataset used (assumed to be in the same directory as the script).

## 📊 This Script Covers

- Viewing the structure and first few rows of the dataset
- Calculating descriptive statistics (mean, SD, min, max) for each feature
- Drawing histograms for all columns
- Drawing boxplots for all columns
- Calculating and visualizing correlation matrix (heatmap)
- Checking and displaying class imbalance in the target variable
- Generating class-wise summary statistics for features
- Displaying outlier summary statistics for each column
- Showing dimensions and column names of the dataset

## 📦 Requirements

Make sure you have the following R packages installed:

```r
install.packages("ggplot2")
install.packages("corrplot")
```

## ▶️ How to Run

1. Open R or RStudio.
2. Make sure `pulsarPrediction.R` and `pulsar_data.csv` are in the same folder.
3. Run the script:

```r
source("pulsarPrediction.R")
```

Alternatively, modify the script to select the dataset manually:

```r
df <- read.csv(file.choose())
```

## 📌 Notes

- The dataset must be in CSV format and match the structure expected by the script.
- Output includes various plots and printed statistics in the console.


