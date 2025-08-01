# Breast Cancer Diagnosis Prediction

This project uses machine learning to predict whether a breast tumor is malignant or benign based on real valued features extracted from cell nuclei in digitized medical images. Several classification models were evaluated to determine the best-performing approach.

## Features

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) and feature correlation  
- Multiple classifiers: Logistic Regression, SVM, KNN, Random Forest, Gradient Boosting  
- Model evaluation with accuracy, precision, recall, F1 score, and **ROC AUC** (due to class imbalance)  
- Clear visualization and model comparison  

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) Data Set**, available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) or on [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

## How to Run

1. Clone this repository.  
2. Place `data.csv` (Breast Cancer Wisconsin Diagnostic dataset) in the project root folder.  
3. Open and run the Jupyter Notebook (`breast_cancer_classification.ipynb`).

## Libraries

- Python 3.x  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn  
