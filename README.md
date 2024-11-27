# Boston Housing Price Prediction

This project aims to predict the median value of owner-occupied homes in Boston using various machine learning models. The dataset used for this project is the **Boston Housing Dataset**. The goal is to compare different regression models (Linear Regression, Random Forest, and Support Vector Regressor) and evaluate their performance based on Mean Squared Error (MSE) and R² scores.

## Project Overview

The project involves the following key steps:
1. **Loading and Exploring the Dataset**:
    - Load the dataset from a CSV file.
    - Perform initial data exploration (checking for missing values, basic statistics).
    
2. **Data Preprocessing**:
    - Normalize and standardize the features.
    - Visualize the distribution of the data before and after preprocessing.

3. **Modeling**:
    - Train three regression models:
      - **Linear Regression**
      - **Random Forest Regressor**
      - **Support Vector Regressor (SVR)**

4. **Model Evaluation**:
    - Evaluate the models using MSE (Mean Squared Error) and R² score.
    - Compare the performance of the models.

## Requirements

To run this project, you will need the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
