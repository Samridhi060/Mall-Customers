# 🛍️ Mall Customer Segmentation with K-Means

This project performs **unsupervised learning** using **K-Means Clustering** to segment customers based on their demographic and spending data. It uses the popular **Mall Customers dataset** and includes feature preprocessing, optimal cluster selection using the Elbow Method, and cluster evaluation using the Silhouette Score.

---

## 📁 Dataset

- **Source:** `Mall_Customers.csv`
- **Features Used:**
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🚀 Objectives

- Perform customer segmentation using **K-Means**.
- Use **Elbow Method** to find the optimal number of clusters.
- Evaluate clustering performance using **Silhouette Score**.
- Visualize clusters using **PCA** for 2D plotting.

---

## 🧰 Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Steps Performed

1. Load and explore the dataset.
2. Encode categorical features (`Gender`).
3. Normalize features using `StandardScaler`.
4. Use the **Elbow Method** to determine optimal `k`.
5. Fit `KMeans` and generate cluster labels.
6. Evaluate using **Silhouette Score**.
7. Visualize clusters using **PCA** (2D).

---

## 📈 Results

- ✅ **Optimal Clusters (K):** 5  
- 🧩 **Silhouette Score:** ~0.408  
- 📉 PCA Visualization used to represent clusters.




