# Diabetes Prediction System

## Project Overview

This project focuses on predicting the likelihood of diabetes using machine learning techniques and patient health data. A Logistic Regression model was developed to classify individuals as diabetic or non-diabetic based on medical attributes.

## Dataset

This project uses the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements used to predict whether a patient has diabetes.

### Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target Variable

* Outcome (0 = Non-Diabetic, 1 = Diabetic)

## Key Features

* Preprocessed the dataset by handling invalid values and replacing zero values with median values.
* Applied feature scaling using StandardScaler to improve model performance.
* Trained and evaluated a Logistic Regression model using accuracy score, confusion matrix, and classification report.
* Implemented a risk profiling approach to categorize patients into Low, Medium, and High Risk groups based on prediction probabilities.
* Generated predictions for new patient records using the trained model.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Google Colab

## Workflow

1. Data loading and preprocessing.
2. Handling invalid values in the dataset.
3. Train-test split of the dataset.
4. Feature standardization using StandardScaler.
5. Model training using Logistic Regression.
6. Performance evaluation and prediction.
7. Risk level assessment based on predicted probabilities.

## Repository Structure

* `Diabetes Prediction System.ipynb`
* `diabetes.csv`
* `README.md`

## Conclusion

This project demonstrates the application of machine learning techniques in healthcare by predicting diabetes risk and providing interpretable risk categories for patients.
