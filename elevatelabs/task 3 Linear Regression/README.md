# Task 3: Linear Regression – AI & ML Internship

This repository contains my solution for Task 3 of the AI & ML Internship program. The task involved building and evaluating a Linear Regression model using a housing price dataset.

## Objective

To implement and understand linear regression by:
- Preprocessing data
- Training a regression model
- Evaluating model accuracy
- Interpreting feature coefficients

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

- Housing Price Prediction Dataset from Kaggle  
  Link: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction  
- File: `Housing.csv`

## Steps Performed

### 1. Data Preprocessing
- Loaded data using pandas
- Converted `yes/no` values to `1/0`
- Applied one-hot encoding to the `furnishingstatus` column

### 2. Data Splitting
- Split data into training and testing sets using `train_test_split`

### 3. Model Training
- Trained a linear regression model using `LinearRegression()` from scikit-learn

### 4. Evaluation
- Evaluated the model using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 5. Visualization
- Plotted predicted vs actual prices using scatter plots
- Visualized model performance using a regression plot (area vs price)

### 6. Coefficient Interpretation
- Interpreted model coefficients to understand the effect of each feature on predicted price

## Output Files

- `t3_linear_regression.ipynb` – Colab notebook containing all code
- `Housing.csv` – Dataset used
- `README.md` – This documentation file

## Author

shrey sakhiya  
AI & ML Internship Participant

## Submission

All files have been uploaded to this repository and submitted through the internship submission form.
