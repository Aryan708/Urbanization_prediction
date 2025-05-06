# Urbanization Prediction Using Machine Learning

This project predicts the urbanization status of Indian states using machine learning techniques on socio-economic and land use data. The workflow includes data preprocessing, feature engineering, model training, and evaluation.

## Dataset

- **Source:** [Mendeley Data - Urbanization in India](https://data.mendeley.com/datasets/586r25nts5/1)
- **Description:** State-wise land use and socio-economic indicators such as road density, electricity consumption, tele-density, GDP, investment ratios, and more.

## Project Workflow

1. **Data Loading**
    - Loaded the dataset using pandas from an Excel file.
2. **Data Cleaning & Preprocessing**
    - Handled missing values and filled categorical columns (`CATEGORY OF STATE`) based on state.
    - Converted categorical variables to numerical format using one-hot encoding.
3. **Feature Engineering**
    - Selected relevant features: road density, electricity consumption, tele-density, GDP, investment ratios, etc.
    - Created a binary target variable (`urbanized`) based on urban population percentage.
4. **Train-Test Split**
    - Split the data into training and testing sets (80/20 split).
5. **Model Training**
    - Trained a Random Forest Classifier to predict urbanization status.
6. **Model Evaluation**
    - Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix.
    - Achieved **97.8% accuracy** on the test set.

## Example Code Snippet

