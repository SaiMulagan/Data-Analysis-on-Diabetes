# Data Analysis on Diabetes
Author: Sai Mulagan
Date: 2023-12-11
Output: PDF Document

## Project Overview
This project aims to analyze data related to diabetes to uncover insights into factors influencing diabetes management. Utilizing a dataset with variables such as stable glucose levels, HDL cholesterol, and glycosylated hemoglobin, the goal is to identify key factors associated with the target variable glyhb_star, representing diabetes control, and to develop a predictive model.

## Data Description
The dataset includes quantitative variables like cholesterol levels, glucose levels, and blood pressure, and qualitative variables such as location, gender, and body frame size.

## Analysis Summary
Data Exploration and Splitting: The analysis begins with identifying quantitative and qualitative variables, followed by generating histograms and pie charts for visual representation.

Model Building: Several models are constructed to predict glyhb_star. Techniques used include linear regression, Box-Cox transformation, and regression subset selection.

Model Evaluation: Models are assessed using metrics like Mean Squared Error (MSE), PRESS statistic, and model comparison with adjusted R-squared, AIC, and BIC.

Final Model Selection: After comparing different models, the most appropriate model is selected based on its performance on training and test data.

## Repository Contents
README.md: Project description and summary.
diabetes_analysis.Rmd: R Markdown file with the complete analysis.
diabetes_data.txt: Dataset used in the analysis.
diabetes_analysis.pdf: PDF output of the analysis.

## Dependencies
R and RStudio
Packages: ggplot2, GGally, dplyr, magrittr, glmnet
