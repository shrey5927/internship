# Task 6: Multiclass Classification – AI & ML Internship

This repository contains the solution for Task 6 of the AI & ML Internship. The task focuses on performing multiclass classification using Decision Tree and Random Forest models on the Iris dataset.

## Objective

- Train and evaluate Decision Tree and Random Forest models
- Handle multiclass target (Iris-setosa, Iris-versicolor, Iris-virginica)
- Visualize decision tree structure
- Interpret feature importance
- Validate models using cross-validation

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

- Iris Dataset (`Iris.csv`)  
  Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

## Steps Performed

### 1. Data Loading & Cleaning
- Loaded dataset and removed the `Id` column
- Encoded `Species` labels as numeric values

### 2. Model Training
- Trained a Decision Tree Classifier
- Trained a Random Forest Classifier
- Evaluated both models using accuracy, confusion matrix, and classification report

### 3. Visualization
- Visualized the decision tree
- Plotted feature importance from Random Forest

### 4. Cross-Validation
- Performed 5-fold cross-validation on both models
- Compared average accuracy

## Output Files

- `task_6_iris_classification.ipynb` – Colab notebook
- `Iris.csv` – Dataset
- `README.md` – This documentation file

## Author

shrey sakhiya  
AI & ML Internship Participant

## Submission

All required files and code have been uploaded to this repository and submitted through the internship portal.
