
# Breast Cancer Classification using SVM

## Project Overview

This project demonstrates Breast Cancer Classification using Machine Learning and Support Vector Machine (SVM).

The dataset is loaded using the `load_breast_cancer()` dataset provided by Scikit-learn.

## Dataset

The Breast Cancer Wisconsin Diagnostic dataset contains features computed from digitized images of breast mass.

The target contains two classes:

- Malignant
- Benign

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Support Vector Machine (SVM)
- StandardScaler

## Machine Learning Workflow

1. Load the dataset
2. Explore the dataset
3. Split data into training and testing sets
4. Standardize features using StandardScaler
5. Train SVM classifier
6. Make predictions
7. Evaluate the model
8. Analyze the confusion matrix and classification report

## Model

Support Vector Machine (SVM)

```python
SVC(kernel="linear")
