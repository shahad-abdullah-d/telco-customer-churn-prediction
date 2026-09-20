# Telco Customer Churn Prediction

A machine learning project focused on predicting customer churn in a telecommunications company using classification models and customer segmentation techniques.

## Project Overview

Customer churn occurs when a customer stops using a company's services. This project uses customer data to predict whether a customer will leave the company (`Churn = Yes`) or continue using its services (`Churn = No`).

The project covers exploratory data analysis, data preprocessing, classification model training and evaluation, and customer segmentation.

## Dataset

The project uses the **Telco Customer Churn** dataset, containing 7,043 customer records.

The dataset includes customer demographics, subscribed services, contract information, tenure, monthly charges, total charges, and churn status.

The target variable is `Churn`.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Explored customer characteristics, service subscriptions, and churn distribution to understand the dataset and identify patterns associated with customer churn.

### 2. Data Cleaning and Preprocessing

- Checked missing values, duplicates, and data types.
- Addressed missing values in `TotalCharges`.
- Prepared numerical and categorical features for machine learning.
- Considered class imbalance during model evaluation.

### 3. Churn Prediction

Trained and compared multiple classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting

### 4. Model Evaluation

Evaluated the models using accuracy, precision, recall, F1-score, and ROC-AUC.

**Random Forest was selected as the final model**, with particular attention to recall for customers who churn.

The notebook also explores hyperparameter tuning and model overfitting.

### Final Model Results

The selected Random Forest model achieved the following results on the **test set**:

| Metric | Score |
|---|---:|
| Accuracy | 76.4% |
| Recall (Churn) | 74.1% |
| Precision (Churn) | 54.0% |
| F1-score (Churn) | 62.5% |
| ROC-AUC | 82.9% |

The model correctly identified approximately **74% of customers who actually churned**.

Recall was prioritized because identifying customers who may leave was an important objective of this project.

### 5. Customer Segmentation

Applied **K-Means** and **Hierarchical Clustering** to explore customer groups based on tenure, monthly charges, and total charges.

## Project Files

- `Telco_Customer_Churn_Prediction.ipynb` — Notebook containing data analysis, preprocessing, machine learning models, evaluation, and clustering.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Dataset used in the project.

## How to Run

1. Download the notebook and dataset from this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Update the dataset file path in the notebook if needed.
4. Run the cells in order to reproduce the analysis and results.

## Author

Shahad Abdullah

Artificial Intelligence Bootcamp Project
