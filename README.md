# Parikshit-s-toolkit-
# Statistical Analysis Toolkit – User Guide

## Overview

The Statistical Analysis Toolkit is a web-based application designed to perform statistical analysis, data visualization, probability distribution analysis, hypothesis testing, and report generation directly in a web browser.

The system supports CSV and Excel datasets and provides an interactive environment for students, researchers, and data analysts.

---

# 1. Getting Started

## Launching the Application

1. Download the project files.
2. Open `index.html` in a modern web browser.
3. The application will load automatically.
4. Navigate using the top menu bar.

Supported browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

---

# 2. Upload Dataset

## Purpose

Import datasets for analysis.

## Supported Formats

* CSV (.csv)
* Excel (.xlsx)
* Excel (.xls)

## Steps

1. Click **Upload Dataset**.
2. Drag and drop a file or browse manually.
3. Wait for the dataset to load.
4. Review:

* Number of rows
* Number of columns
* Missing values
* Dataset preview

---

# 3. Data Cleaning

## Purpose

Prepare datasets before analysis.

### Available Functions

### Remove Duplicate Rows

Removes identical observations.

### Handle Missing Values

Options:

* Mean Imputation
* Median Imputation
* Mode Imputation
* Fill with Zero
* Remove Rows

### Data Transformation

Options:

* Standardization (Z-Score)
* Min-Max Normalization
* Log Transformation
* Square Root Transformation
* Label Encoding

---

# 4. Outlier Detection

## Purpose

Identify abnormal observations.

### Methods Available

### Z-Score Method

Detects observations with:

|Z| > 3

### IQR Method

Uses:

Q1 − 1.5(IQR)

Q3 + 1.5(IQR)

### Outputs

* Number of outliers
* Box Plot
* Histogram

---

# 5. Descriptive Statistics

## Purpose

Summarize dataset characteristics.

### Calculated Statistics

* Mean
* Median
* Mode
* Minimum
* Maximum
* Range
* Variance
* Standard Deviation
* Skewness
* Kurtosis

### Visualizations

* Histogram
* Box Plot

---

# 6. Data Visualization

## Univariate Analysis

Visualize one variable using:

* Histogram
* Density Plot
* Box Plot
* Violin Plot

## Bivariate Analysis

Compare two variables using:

* Scatter Plot
* Line Chart
* Bar Chart

## Multivariate Analysis

Generate:

* Correlation Heatmap
* Pair Plot

---

# 7. Probability Distributions

The toolkit includes interactive demonstrations of:

## Bernoulli Distribution

Single trial success/failure model.

## Binomial Distribution

Fixed number of independent Bernoulli trials.

## Poisson Distribution

Models event counts.

## Normal Distribution

Continuous bell-shaped distribution.

## Uniform Distribution

Equal probability across an interval.

## Exponential Distribution

Models waiting times between events.

### Outputs

* PMF
* PDF
* CDF
* Mean
* Variance
* Standard Deviation

---

# 8. Normal Distribution Learning Center

## Features

### Interactive Bell Curve

Adjust:

* Mean (μ)
* Standard Deviation (σ)

### Empirical Rule

Visual explanation of:

* 68%
* 95%
* 99.7%

coverage intervals.

---

# 9. Central Limit Theorem Simulator

## Purpose

Demonstrates the Central Limit Theorem.

### User Controls

* Sample Size (n)
* Number of Samples
* Population Distribution

### Outputs

* Population Distribution
* Sampling Distribution
* Standard Error

---

# 10. Z-Score Calculator

## Formula

Z = (X − μ) / σ

### Outputs

* Z Score
* Percentile
* Cumulative Probability

---

# 11. Normality Testing

## Purpose

Determine whether data follows a normal distribution.

### Tests Included

* Shapiro-Wilk Test
* Kolmogorov-Smirnov Test
* Anderson-Darling Test

### Visualizations

* Q-Q Plot
* Histogram with Normal Curve

### Decision Rule

If p-value > 0.05

Data is considered approximately normal.

If p-value < 0.05

Data is considered non-normal.

---

# 12. Hypothesis Testing

## Purpose

Evaluate statistical claims using sample data.

### Concepts

#### Null Hypothesis (H₀)

No significant effect exists.

#### Alternative Hypothesis (H₁)

A significant effect exists.

### Outputs

* Test Statistic
* p-value
* Decision

---

# 13. Non-Parametric Testing

Used when data does not satisfy normality assumptions.

### Tests

* Mann-Whitney U Test
* Wilcoxon Signed-Rank Test
* Kruskal-Wallis Test

---

# 14. Automatic Test Recommendation Engine

## Purpose

Automatically recommends the most suitable statistical test.

### Example Recommendations

| Dataset Type              | Recommended Test                         |
| ------------------------- | ---------------------------------------- |
| Single Numeric Variable   | One Sample T-Test                        |
| Two Numeric Variables     | Paired T-Test                            |
| Numeric + Group Variable  | ANOVA                                    |
| Two Categorical Variables | Chi-Square                               |
| Non-Normal Data           | Mann-Whitney / Wilcoxon / Kruskal-Wallis |

The recommendation is based on:

* Data Type
* Number of Variables
* Number of Groups
* Normality Test Results

---

# 15. Report Generation

## Purpose

Export analysis results.

### Export Formats

* PDF Report

### Included Information

* Dataset Summary
* Statistical Results
* Visualizations
* Conclusions

---

# Troubleshooting

## Dataset Not Loading

Verify:

* File format is CSV or XLSX.
* Dataset is not corrupted.

## Charts Not Appearing

Refresh the browser and reload the dataset.

## Statistical Test Disabled

Ensure:

* A dataset has been uploaded.
* Appropriate columns are selected.

---

# Best Practice Workflow

1. Upload Dataset
2. Clean Data
3. Detect Outliers
4. Generate Descriptive Statistics
5. Visualize Data
6. Check Normality
7. Run Hypothesis Tests
8. Use Test Recommendation Engine
9. Export Final Report

---

# Author

Parikshit Akula

Statistical Analysis Toolkit
