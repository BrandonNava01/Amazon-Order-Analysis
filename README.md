# Amazon Order Analysis

## Overview
This project involves analyzing Amazon order data using various machine learning models. The models used include Linear Regression, Gradient Boosting Machine (GBM), Random Forest, Decision Tree, and K-Nearest Neighbors (KNN). 
The goal is to predict `log_total`, the log-transformed total order amount.

## Project Structure
- `train.csv`: The training dataset.
- `test.csv`: The test dataset.
- `scripts/`: Directory containing R scripts for data preprocessing, model training, and prediction.
- `results/`: Directory containing output files such as predictions and evaluation metrics.
- `README.md`: Project documentation.

## Installation
To run the project, you need to have R and the following packages installed:
- `tidyverse`
- `tidymodels`
- `xgboost`
- `rpart`
- `kknn`
- `readr`

You can install the packages using the following commands:
```r
install.packages("tidyverse")
install.packages("tidymodels")
install.packages("xgboost")
install.packages("rpart")
install.packages("kknn")
install.packages("readr")
