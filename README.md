# Telco Customer Churn Prediction

A machine learning project focused on predicting customer churn in a telecommunications company using customer data, classification models, and clustering techniques.

## Project Overview

The project aims to predict whether a customer will leave a telecommunications company (`Churn = Yes`) or continue using its services (`Churn = No`).

The notebook covers exploratory data analysis, data preprocessing, machine learning model training and evaluation, and customer segmentation.

## Dataset

The project uses the **Telco Customer Churn** dataset, containing 7,043 customer records.

The dataset includes customer demographics, subscribed services, contract information, tenure, monthly charges, total charges, and churn status.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Explored customer characteristics, service subscriptions, and churn distribution to understand the dataset.

### 2. Data Cleaning and Preprocessing

- Checked missing values, duplicates, and data types.
- Addressed missing values in `TotalCharges`.
- Prepared numerical and categorical features for machine learning.
- Considered class imbalance during model evaluation.

### 3. Churn Prediction

Trained and compared several classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting

### 4. Model Evaluation

Evaluated model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

**Random Forest was selected as the final model**, with particular attention to recall for customers who churn.

The notebook also explores hyperparameter tuning and model overfitting.

### 5. Customer Segmentation

Applied K-Means and Hierarchical Clustering to explore customer groups based on tenure, monthly charges, and total charges.

## Project Files

- `Telco_Customer_Churn_Prediction.ipynb` — Analysis and machine learning notebook.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Dataset used in the project.

## How to Run

1. Download the notebook and dataset from this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Update the dataset file path in the notebook if needed.
4. Run the cells in order to reproduce the analysis and results.

## Author

Shahad Abdullah

Artificial Intelligence Bootcamp Project
