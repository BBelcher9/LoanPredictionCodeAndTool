# LoanPredictionCodeAndTool

## Description

This repository contains the code for a loan prediction machine learning model and an interactive prediction tool. The machine learning model, implemented in the notebook `HomeLoanPredictionML_RF.ipynb`, is built using Python and Jupyter Notebook. The project leverages the "Home Loan Predictions" dataset, uploaded by GOVARDHAN C on Kaggle.com, specifically utilizing the `loan_sanction_train.csv` file for training purposes.

The machine learning model is trained on this dataset and the resulting model is saved as a `.joblib` file. This saved model is then imported into the prediction tool, implemented in the notebook `HomeLoanPredictorTool_RF.ipynb`. This tool provides an interactive application that allows users to predict loan status based on input information.

## Dataset

### Name
[Home Loan Predictions](https://www.kaggle.com/datasets/gavincanacam/home-loan-predictions)

### Description
The Home Loan Predictions dataset contains data on various examples of home loan status with determining factors. It includes fields such as applicant income, loan amount, credit history, and more, providing comprehensive coverage of home loans and their approval status.

### Instructions
To use the dataset with this project, follow these steps:

1. Download the dataset from [Home Loan Predictions](https://www.kaggle.com/datasets/gavincanacam/home-loan-predictions).
2. Unzip the downloaded file to extract `loan_sanction_train.csv`.
3. Move the `loan_sanction_train.csv` file to the root directory of this project.