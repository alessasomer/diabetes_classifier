# Classifier for Diabetes Patient Utilizing Glucose Data

This project explores the development of a machine learning model to classify individuals as diabetic or non-diabetic using data from the National Health and Nutrition Examination Survey (NHANES). The project emphasizes the importance of correctly prescribing diabetes treatment drugs and aims to support medical professionals in assessing the legitimacy of prescriptions.

## Project Overview

- **Objective**: To develop a random forest that accurately classifies individuals as diabetic or non-diabetic using various health indicators.
- **Data Source**: NHANES 2017-2018 dataset.
- **Tech Stack**: R, Python, Scikit-learn, Pandas, Matplotlib, Seaborn

## Methodology

1. **Data Preprocessing**:
   - Data preprocessing was performed using R, including data cleaning, feature selection, and normalization. The dataset included age, blood glucose levels, dietary intake, and more.
   - The final dataset consisted of 2163 observations with 11 features.

2. **Models**:
   - **Logistic Regression**: Served as the baseline model, providing an accuracy of 67%. The model used a logistic loss function with an L2 penalty to avoid overfitting.
   - **Random Forest Classifier**: Selected as the final model due to its superior performance. It utilized ensemble learning to mitigate overfitting and improve accuracy.

## Read the full paper here: 
(https://drive.google.com/file/d/105S7rX-caUsqjegx0CjOXlA8QkWsKpxP/view)
