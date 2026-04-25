# Customer Segmentation using K-Means Clustering

## 📌 Overview
This repository contains a Machine Learning project that applies **Unsupervised Learning** to segment a mall's customer base. The goal is to identify target customers to help the marketing team plan effective strategies.

## 📊 Dataset
The dataset includes:
* **Customer ID**
* **Gender & Age**
* **Annual Income (k$)**
* **Spending Score (1-100)**

## 🚀 Methodology
1. **Data Preprocessing:** Handled data loading and checked for null values using `pandas`.
2. **Feature Selection:** Focused on Annual Income and Spending Score for 2D clustering.
3. **Optimizing K:** Used the **Elbow Point Graph** (WCSS) to find that 5 clusters provide the best fit.
4. **Model Training:** Initialized and trained the `KMeans` model.
5. **Visualization:** Created a color-coded scatter plot highlighting the 5 customer segments and their centroids.

## 📈 Results
The model successfully categorized customers into 5 groups:
* **Target:** High Income, High Spending
* **Careful:** High Income, Low Spending
* **Average:** Mid Income, Mid Spending
* **Spendthrift:** Low Income, High Spending
* **Sensible:** Low Income, Low Spending

## 🛠️ Tools
* Language: **Python**
* Libraries: `scikit-learn`, `matplotlib`, `seaborn`, `pandas`, `numpy`
