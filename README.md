# ca_scores

## Medium Post

https://medium.com/@preeti.amin/analysis-of-standardized-student-test-scores-using-pre-processing-for-bias-removal-1d210f56c05f

## Introduction

This project explores the California student test scores from grade 3-8 for Math and English Language Arts

## Project Motivation

The goal of the project was to analyze standardized test scores for California and create a model to predict these from school demographic data. The project also explored removing bias in the model by removing features that have inherent bias such as gender, ethnicity, economic status etc.

## Technologies

* Python, Jupiter
* numpy, pandas, matplotlib, seaborn, scipy and sklearn libraries

## Questions answered in the analysis

#### Question 1: Is there a difference between the scores of economically disadvantaged students vs. not economically disadvantaged?
Yes, there is a statistically significant difference between these two groups.

#### Question 2: Is there a difference between English language arts and Math scores for students?
Yes, there is a statistically significant difference between these two groups.

#### Question 3: Can a model be derived to predict school scores without using biased features such as gender, ethnicity?
Yes, a Gradient Boosting Regression model was derived for the data after removing gender, ethnicity, disability and economic status from the features with a R2 score of 0.74.

## Acknowledgements
The data for the analysis was downloaded from https://caaspp-elpac.cde.ca.gov/caaspp/
