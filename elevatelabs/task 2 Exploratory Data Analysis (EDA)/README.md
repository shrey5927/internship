# Task 2: Exploratory Data Analysis (EDA) – AI & ML Internship

This repository contains my submission for Task 2 of the AI & ML Internship program. The goal of this task was to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand its structure, identify patterns, and extract insights through visualizations and statistics.

## Objective

To explore the Titanic dataset using descriptive statistics and visualizations to identify trends, correlations, and data distributions that can help in building machine learning models.

## Tools Used

- Google Colab (Python environment)
- Python
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib

## Dataset Used

- Titanic Dataset from Kaggle  
  Link: https://www.kaggle.com/datasets/yasserh/titanic-dataset  
- File used: `train.csv`

## Steps Performed

### 1. Data Loading and Exploration
- Loaded the dataset using pandas
- Viewed basic information like shape, data types, and null values
- Used `describe()` and `median()`, `mode()` to understand data distribution

### 2. Visualizations
- **Histograms** to understand distribution of numeric features (`Age`, `Fare`, etc.)
- **Boxplots** to identify outliers in `Age` and `Fare`
- **Countplots** to examine distribution of categorical values like `Pclass` and `Sex`

### 3. Feature Relationships
- Generated a **correlation heatmap** to examine relationships between numerical features
- Used **pairplot** to visualize how features interact with each other and the target (`Survived`)

### 4. Key Observations
- Females had a much higher survival rate than males
- Passengers in 1st class had better survival chances and paid higher fares
- Age was approximately normally distributed with some outliers
- `Fare` had strong outliers and was correlated with both `Pclass` and `Survived`
- Weak correlation between family features (`SibSp`, `Parch`) and survival

## Output Files

- `titanic_eda_ready.csv` – Optional cleaned dataset after analysis
- `eda_titanic.ipynb` – Google Colab notebook with code and charts
- `boxplot_age.png`, `heatmap.png`, etc. – Optional saved visualizations

## Author

shrey sakhiya  
AI & ML Internship Participant

## Submission

All code, visualizations, and this README are included in the repository for submission.
