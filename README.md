# Analytics Engine

This project aims to leverage machine learning algorithms to predict the label of a response variable based on a diverse dataset. Through comprehensive data cleaning, visualization, modeling, and analysis, this work explores the effectiveness of different classifiers and their suitability for handling mixed data types and complexities inherent in the dataset.

## Introduction

The project utilizes a dataset consisting of 1396 observations across 16 columns, featuring a mix of numerical values, categorical data, and text strings. The primary goal is to predict a categorical target variable, posing a classification challenge. The dataset's variety calls for meticulous data cleaning and preprocessing to prepare it for machine learning models.

## Data Cleaning

The data cleaning process included handling missing/empty values, normalizing numeric columns, removing inconsistencies, assigning correct data types, and implementing one-hot encoding for categorical variables. These steps were crucial to ensure the integrity and usability of the dataset for analysis and modeling.

## Data Visualization

Two key visualizations were created to aid in understanding the dataset:
- A pie chart showing the distribution of participants across various sports.
- A scatter plot illustrating the relationship (or lack thereof) between two numerical variables.

These visualizations provide insights into the popularity of different sports and the correlation between numerical features.

## Modeling

Three classifiers were used in this project:
- Logistic Regression
- K-Nearest Neighbor (KNN)
- Decision Tree

No additional parameters were adjusted for these models. The performance of each model was compared using k-fold validation, focusing on accuracy and standard deviation of accuracy as key metrics.

## Analysis

The analysis delves into why certain classifiers performed better than others, the consideration of evaluation metrics beyond accuracy, the continuous need for thorough data cleaning, the statistical significance between classifiers, and the potential for parameter tweaking to enhance model performance.

## Conclusion

The project highlighted the importance of data preprocessing, model selection, and parameter tuning in building robust predictive models. Logistic Regression demonstrated the highest mean accuracy, indicating its strong fit for the dataset used. Areas for further investigation include more advanced ensemble methods and a detailed examination of model performance on separate training and test sets.

## References

This project did not use external references.

## Extra Credit

An additional dataset from Kaggle, comprising the artist, song name, and length of top 100 billboard hip-hop songs, was analyzed. This section follows a similar structure, emphasizing data cleaning, visualization, and modeling but focuses on understanding factors influencing the popularity of music tracks.

## Installation

Instructions on how to set up the project environment, install necessary libraries, and run the code.

## Usage

Examples of how to use the scripts included in this repository to perform data cleaning, visualization, modeling, and analysis.
