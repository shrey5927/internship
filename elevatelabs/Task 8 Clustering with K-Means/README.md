# Task 8: Customer Segmentation with K-Means Clustering – AI & ML Internship

This repository contains my solution for Task 8 of the AI & ML Internship. The task involves applying K-Means clustering to segment customers based on their annual income and spending score.

## Objective

- Perform customer segmentation using K-Means clustering
- Find the optimal number of clusters using the Elbow Method
- Visualize clusters and cluster centroids
- Evaluate clustering performance using Silhouette Score

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

- Customer Segmentation Dataset  
  File: `Mall_Customers.csv`  
  Source: [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## Steps Performed

### 1. Data Loading & Cleaning
- Loaded the dataset and checked for missing values
- Selected `Annual Income (k$)` and `Spending Score (1-100)` for clustering
- Scaled features for better K-Means performance

### 2. Finding Optimal K
- Used the Elbow Method to determine the optimal number of clusters

### 3. Model Training
- Applied K-Means clustering with K=5
- Assigned cluster labels to customers

### 4. Visualization
- Plotted customer segments and cluster centroids

### 5. Evaluation
- Calculated Silhouette Score to assess clustering quality

## Output Files

- `task_8_kmeans_clustering.ipynb` – Colab notebook
- `Mall_Customers.csv` – Dataset used
- `README.md` – This documentation file

## Author

shrey sakhiya
AI & ML Internship Participant

## Submission

All files and code have been uploaded to this repository for internship submission.
