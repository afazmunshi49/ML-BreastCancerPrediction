# Breast Cancer Prediction using Logistic Regression

This project is a machine learning model designed to predict breast cancer diagnoses based on a dataset of cell nucleus features. Using logistic regression, the model classifies tumors as malignant or benign with high accuracy.

## Dataset

The dataset used to train and test the model is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data), available on Kaggle. The dataset includes features that describe the characteristics of cell nuclei from breast cancer patients, such as radius, texture, perimeter, area, and smoothness.

## Project Overview

This project follows the steps necessary for data preprocessing, model training, and performance evaluation:

1. **Data Cleaning**  
   - Drop unnecessary columns and handle missing values.

2. **Encoding**  
   - Use `LabelEncoder` to encode the target variable, converting diagnoses into binary labels (0 and 1).

3. **Feature Scaling**  
   - Apply standard scaling to ensure all features are on a similar scale.

4. **Data Splitting**  
   - Split the dataset into training (75%) and testing (25%) sets.

5. **Model Training**  
   - Train a logistic regression classifier on the training dataset.

6. **Model Evaluation**  
   - Evaluate the model’s performance using a confusion matrix and accuracy score.

## Installation and Setup

To reproduce this project, you’ll need to install the required libraries in a Python environment. You can install these packages using:

```bash
pip install pandas seaborn scikit-learn
