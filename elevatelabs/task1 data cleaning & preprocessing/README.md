# 🚀 Task 1: Data Cleaning & Preprocessing (AI & ML Internship)

This repository contains my completed solution for **Task 1** of the AI & ML Internship program. The objective was to learn how to clean and prepare raw data for machine learning using the Titanic dataset.

---

## 🎯 Task Objective

The main goal of this task was to:
- Understand a real-world dataset
- Clean missing values
- Convert categorical data into numerical format
- Scale numerical features
- Detect and remove outliers
- Prepare a dataset that’s ready for machine learning

---

## 🧰 Tools Used

- Google Colab (Python environment)
- Python Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📊 Dataset Used

- Titanic dataset from Kaggle  
  🔗 [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.csv`

---

## 🧪 Step-by-Step Process

### 1. **Loading the Dataset**
- Used `pandas` to read `Titanic-Dataset.csv` in Google Colab

### 2. **Exploring the Data**
- Checked shape, column names, data types, and missing values using `.info()` and `.isnull().sum()`

### 3. **Handling Missing Values**
- Filled missing `Age` with **median**
- Filled missing `Embarked` with **mode**
- Dropped the `Cabin` column (too many missing values)

### 4. **Encoding Categorical Variables**
- Converted `Sex` to numerical using **Label Encoding**
- Converted `Embarked` to dummy variables using **One-Hot Encoding**

### 5. **Feature Scaling**
- Scaled `Age` and `Fare` using `StandardScaler` from `scikit-learn`

### 6. **Outlier Detection & Removal**
- Used **boxplot** to visualize outliers in the `Fare` column
- Removed extreme outliers using the **IQR method**

---

## 💾 Output Files

- ✅ `cleaned_titanic.csv`: Final cleaned dataset (saved using `to_csv`)
- 📊 `fare_boxplot.png` (optional): Boxplot used to detect outliers

---

## 🙋‍♂️ Author

shrey sakhiya  
Beginner in Python & Machine Learning  
AI & ML Internship Trainee

---

## 📤 Submission

Uploaded code and files to GitHub and submitted the repo link as required.
