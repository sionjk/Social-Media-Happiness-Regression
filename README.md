# Social Media and Happiness Regression Analysis

## Overview

This project analyzes the relationship between social media habits, health factors, demographics, and happiness using statistical modeling in R.

The dataset contains **500 participants and 13 predictor variables**. The goal of the analysis was to identify which factors were most useful for explaining and predicting happiness.

## Project Objectives

* Clean and prepare the dataset for analysis
* Explore relationships between variables using data visualization and correlation analysis
* Develop multiple linear regression models
* Check regression assumptions and multicollinearity
* Evaluate model performance using cross-validation
* Apply a transformation to improve model fit
* Interpret regression coefficients and statistical significance
* Generate confidence and prediction intervals

## Key Findings

The analysis found that **sleep quality and stress level** were important predictors of happiness in the final transformed model. Age also showed a statistically significant relationship with happiness.

The square transformation of the happiness variable improved the model's fit, increasing the R² from approximately **0.643 to 0.665**.

The transformed model was also evaluated using prediction error measures, including RMSE and MAE.

## Statistical Methods

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Visualization
* Correlation Analysis
* Multiple Linear Regression
* Variable Selection
* Multicollinearity Testing
* Variance Inflation Factor (VIF)
* Regression Diagnostics
* Cross-Validation
* Variable Transformation
* Confidence Intervals
* Prediction Intervals
* RMSE and MAE

## Tools & Technologies

* **R**
* **R Markdown**
* **RStudio**
* **ggplot2**
* **dplyr**
* **caret**
* **car**
* **GGally**
* **corrplot**
* **e1071**
* **lmtest**

## Files

* `README.md` — Project overview and results
* `Social-Media-Happiness-Regression-Report.docx` — Full project report
* `Social-Media-Happiness-Regression.Rmd` — R Markdown source code
* `data/` — Project dataset
* `figures/` — Generated visualizations

## Data Source

The dataset was obtained from **Kaggle** and contains survey information from participants between ages 16 and 49.

## Authors

**Sion King**

**Aditya Muddapu**

**Ricardo Gonzalo**

University of Central Florida — Statistics
