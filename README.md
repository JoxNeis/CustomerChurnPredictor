# Customer Churn Classifier

## Overview

Customer churn occurs when customers stop doing business with a company. This project focuses on building a machine learning model to predict which customers are likely to churn based on their demographic information, account details, and activity patterns. By identifying at-risk customers, businesses can implement retention strategies to improve loyalty and reduce revenue loss.

## Features

  - **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
  - **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations, and key drivers of churn.
  - **Model Training:** Implementation of classification algorithms such as Logistic Regression, Random Forest, or Gradient Boosting.
  - **Evaluation:** Assessment of model performance using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

## Project Structure

```text
├── Churn_Modelling.csv               # Dataset files
├── CustomerChurnModel.ipynb          # Jupyter notebooks for EDA and modeling
└── README.md                         # Project documentation
```


## Pipelines

1.  **Prepare the Data:** Put the dataset into a directory.
2.  **Dimensionality Reduction:** Reduce data dimension by using PCA
3.  **Feature Selection:** Using K-Folds Cross Validation
4.  **Train Model:** Using TensorFlow Keras API for Deep Learning Model
5.  **Evaluate:** Evaluate performance metrics

## Dataset

The model features such as:
  - **Demographics:** Age, gender, geography.
  - **Account Info:** Tenure, balance, number of products, credit score.
  - **Activity:** Activity status, estimated salary, and whether they have a credit card.

## Results

A summary of the model's performance on the test set:
  - **Accuracy:** 0.80
  - **F1-Score:** 0.60
  - **Key Insight:** 

## Acknowledgments

  - Inspired by industry standard churn datasets.
  - Built using libraries like TensorFlow, Scikit-Learn, Pandas, and Matplotlib.
