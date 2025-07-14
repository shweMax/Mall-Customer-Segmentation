# Mall Customer Segmentation using K-Means Clustering

This project focuses on segmenting mall customers into distinct groups based on their purchasing behavior and demographics such as age, annual income, and spending score. The goal is to help businesses better understand customer profiles and target their marketing strategies effectively.

---

## 📊 Overview

Businesses often have a large and diverse customer base. Grouping similar customers into segments helps companies:
- Personalize marketing campaigns
- Recommend better products
- Improve customer retention
- Optimize pricing strategies

In this project, we apply **K-Means Clustering**, a popular unsupervised machine learning technique, to group mall customers into segments. The dataset is visualized **before and after clustering**, and we use **PCA (Principal Component Analysis)** to project high-dimensional data into 2D space for better visualization of the clusters.

---

## 📁 Dataset

- **Name:** Mall Customer Segmentation Data
- **Source:** [Kaggle (VJ Choudhary)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Attributes:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Techniques Used

- **Standardization** of features using `StandardScaler`
- **K-Means Clustering** for unsupervised segmentation
- **Hyperparameter Tuning** using Silhouette Score to find optimal number of clusters
- **Dimensionality Reduction** using PCA
- **Data Visualization**:
  - Scatter plots before and after clustering
  - PCA 2D projection of clustered data

---

## 📌 Key Features

- Automatically selects the best number of clusters using silhouette score.
- Visualizes how the clustering improves understanding of customer behavior.
- Saves the segmented data as a CSV for further use.
- Easy to run on Google Colab or Jupyter Notebook.

---

## 🖼️ Sample Visualizations

- Age vs Spending Score before and after clustering
- Income vs Spending Score before and after clustering
- PCA projection showing final cluster separation

---

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation
2. Make sure you have the required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
3. Place `Mall_Customers.csv` in the root directory.
4. Run the notebook:

In **Jupyter Notebook** or **Google Colab**, open and run the file:  
`Customer-Segmentation.ipynb`

  

