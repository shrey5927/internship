# Task 7: Breast Cancer Classification with Support Vector Machines (SVM)

This repository contains my solution for Task 7 of the AI & ML Internship. The task focuses on using Support Vector Machines (SVM) for classifying breast cancer cases as benign or malignant.

## Objective

- Train and evaluate an SVM classifier on a breast cancer dataset
- Visualize performance using confusion matrix and ROC-AUC curve
- Tune SVM hyperparameters for optimal performance

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

- Breast Cancer Dataset (`breast-cancer.csv`)

## Steps Performed

### 1. Data Loading & Cleaning
- Loaded the dataset and removed unnecessary columns
- Encoded target labels: `M → 1 (Malignant)`, `B → 0 (Benign)`
- Checked for missing values

### 2. Preprocessing
- Scaled features using `StandardScaler` (important for SVM models)

### 3. Model Training
- Trained an SVM classifier using a linear kernel

### 4. Evaluation
- Evaluated the model using:
  - Accuracy
  - Confusion matrix
  - Precision, Recall, F1-score
  - ROC-AUC Curve

### 5. Visualization
- Plotted confusion matrix
- Plotted ROC curve to visualize classifier performance

## Output Files

- `task_7_svm_breast_cancer.ipynb` – Colab notebook with code
- `breast-cancer.csv` – Dataset used
- `README.md` – This documentation file

## Author

shrey sakhiya
AI & ML Internship Participant

## Submission

All required files and code have been uploaded to this repository for internship submission.
