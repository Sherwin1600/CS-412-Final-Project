# CS-412-Final-Project

We are predicting customer churn within the telecommunications industry
We have two main goals:

- **1. Predict Customer Churn with ML models (logistic regression, SVM, etc) with a high accuracy**
- **2. Understand which specific features/variables do the best job of predicting churn**

## Installing Dependencies

```sh
python3 -m venv venv # Create virtual env
source venv/bin/activate
pip3 install -r requirements.txt
```

## Data Sources

Dataset used: Telcom Customer Churn Dataset

[https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Notebook Breakdown

- `churnExperiment.ipynb`: Contains initial data exploration attempts
- `data_cleaning_preprocessing.ipynb`: Contains all relevant logic to perform data cleaning and pre-processing steps, including null-value removal, one-hot encoding, feature selection and feature engineering using PCA
- The notebooks below contain the training implementations and corresponding visualizations for model training:
  - `knn_classifier.ipynb`: Contains training implementation for kNN classifier
  - `decision_tree_classififer.ipynb`: Contains training implementation for Random Forest classifier
  - `logistc_regression_classifier.ipynb`: Contains training implementation for Logistic Regression
  - `svm_classifer.ipynb`: Contains training implementation for Support Vector Machine (SVM) 
