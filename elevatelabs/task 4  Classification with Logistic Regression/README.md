# Task 4: Classification with Logistic Regression – AI & ML Internship

This repository contains the solution for Task 4 of the AI & ML Internship. The task was focused on building a binary classification model using Logistic Regression and evaluating it using proper metrics and visualizations.

## Objective

To implement a binary classifier using Logistic Regression on the Breast Cancer Wisconsin dataset and evaluate it using:
- Confusion Matrix
- Precision and Recall
- ROC-AUC Curve
- Threshold tuning
- Sigmoid function understanding

## Tools Used

- Google Colab
- Python
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn

## Dataset Used

- Breast Cancer Wisconsin (Diagnostic) Dataset  
  Source: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
  File used: `data.csv`

## Steps Performed

### 1. Data Loading and Cleaning
- Dropped unnecessary columns like `id` and `Unnamed: 32`
- Converted `diagnosis` to binary values (`M` = 1, `B` = 0)
- Dropped rows with missing values

### 2. Preprocessing
- Split the data into training and testing sets
- Standardized the features using `StandardScaler`

### 3. Model Training
- Used `LogisticRegression` from `scikit-learn` to fit the model on training data

### 4. Model Evaluation
- Generated confusion matrix
- Calculated precision, recall, F1-score
- Computed ROC-AUC score
- Plotted ROC curve

### 5. Threshold Tuning
- Demonstrated how changing the classification threshold affects performance
- Showed how precision and recall are impacted

### 6. Sigmoid Function
- Explained how logistic regression uses the sigmoid function to produce probabilities between 0 and 1

## Output Files

- `task_4_logistic_regression.ipynb` – Colab notebook
- `data.csv` – Dataset
- `README.md` – This file

## Author

shrey sakhiya  
AI & ML Internship Participant

## Submission

This project was submitted as part of the internship tasks. All required files have been uploaded to this GitHub repository.
