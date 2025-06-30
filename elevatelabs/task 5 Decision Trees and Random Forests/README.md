# Task 5: Decision Trees & Random Forest – AI & ML Internship

This repository contains my solution for Task 5 of the AI & ML Internship. The objective was to implement tree-based classification models, understand overfitting, compare decision trees with random forests, and interpret results using visualizations and cross-validation.

## Objective

- Train and evaluate a Decision Tree Classifier
- Visualize tree structure
- Control tree depth to prevent overfitting
- Train a Random Forest Classifier
- Compare performance of models
- Use cross-validation for evaluation
- Interpret feature importance

## Tools Used

- Google Colab
- Python
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Dataset Used

- Heart Disease Dataset  
  Source: [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
  File: `heart.csv`

## Steps Performed

### 1. Data Exploration
- Loaded and inspected the dataset
- Checked for missing values and class distribution

### 2. Model Building
- Built and evaluated a basic Decision Tree
- Visualized the full tree
- Trained a shallow tree (max_depth = 3) to reduce overfitting
- Trained and evaluated a Random Forest model

### 3. Evaluation
- Compared accuracy of all models
- Performed 5-fold cross-validation
- Visualized feature importance from the Random Forest

## Output Files

- `task_5_decision_tree_random_forest.ipynb` – Colab notebook with code
- `heart.csv` – Dataset used
- `README.md` – This file

## Author

shrey sakhiya  
AI & ML Internship Participant

## Submission

All files have been uploaded to this GitHub repository as part of the official internship submission.
