# Student Performance Analysis & Prediction

## Overview

A Python-based data analysis and machine learning project analyzing student performance and examining relationships between study hours, previous scores, sleep hours, practice papers, and overall performance.

## Dataset

The dataset contains 10,000 student records with the following variables:
* Hours Studied
* Previous Scores
* Extracurricular Activities
* Sleep Hours
* Sample Question Papers Practiced
* Performance Index

After removing 127 duplicate records, 9,873 records remained.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* IPyWidgets
  
## Analysis

The project includes:
* Data cleaning
* Descriptive statistical analysis
* Exploratory data analysis
* Data visualization
* Pearson correlation
* Covariance analysis

## Machine Learning

A multiple linear regression model was developed to predict Performance Index using:
* Hours Studied
* Previous Scores
* Sleep Hours
* Sample Question Papers Practiced

### Model Performance
* **R²:** 0.988
* **MAE:** 1.68
* **RMSE:** 2.11

## Interactive Prediction
An IPyWidgets interface allows users to enter student information and generate a predicted Performance Index.
