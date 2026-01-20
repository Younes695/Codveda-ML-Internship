# ⚡ Level 2: Intermediate - Classification & Clustering

## 📄 Overview
In Level 2 of the Codveda Internship, I moved beyond simple regression to explore **Classification** (Supervised Learning) and **Clustering** (Unsupervised Learning). The goal was to solve real-world problems like customer retention and pattern recognition in unlabeled data.

---

## 📂 Directory Structure

| Task | File | Description |
| :--- | :--- | :--- |
| **Task 1** | `logistic_reg.ipynb` | **Customer Churn Prediction** using Logistic Regression. |
| **Task 2** | `kMeans.ipynb` | **Unsupervised Clustering** using K-Means & PCA. |

---

## 🛠️ Tasks Breakdown

### 🔹 Task 1: Customer Churn Prediction (Logistic Regression)
**Objective:** Predict whether a customer will leave (churn) based on their behavior data.

**Key Steps:**
1.  **Data Preprocessing:** Handled missing values and applied `StandardScaler` for feature normalization.
2.  **Model Training:** Implemented **Logistic Regression** for binary classification.
3.  **Evaluation:** Used comprehensive metrics:
    * Confusion Matrix
    * Accuracy, Precision, Recall, F1-Score
    * **ROC-AUC Score** (Receiver Operating Characteristic)

**🚀 Results:**
| Metric | Score |
| :--- | :--- |
| **Accuracy** | *77.81%* |
| **ROC-AUC** | *81.43* |

> **Visualization:** *ROC Curve demonstrating the model's ability to distinguish between classes.*
![ROC Curve](./Task_1_Logistic_Regression/ROC_Curve.png)

---

### 🔹 Task 2: Unsupervised Learning (K-Means Clustering)
**Objective:** Group unlabeled data into distinct clusters to identify underlying patterns.

**Key Steps:**
1.  **Elbow Method:** Used to determine the optimal number of clusters ($k$).
2.  **K-Means Algorithm:** Applied the algorithm to segment data points.
3.  **Dimensionality Reduction:** Used **PCA (Principal Component Analysis)** to visualize high-dimensional data in 2D.
4.  **Evaluation:** Calculated the **Silhouette Score** to measure cluster separation quality.

**🚀 Results:**
* **Optimal Clusters (k):** *2*
* **Silhouette Score:** *0.580*

> **Visualization:** *2D Projection of Clusters using PCA.*
![Clusters Plot](./Task_2_K-Means_Clustering/Silhouette_Analysis.png)

---

## 🧰 Tech Stack
* **Algorithms:** Logistic Regression, K-Means, PCA.
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn.

---

## 💻 How to Run
1.  Navigate to `Level_2_Intermediate`.
2.  Launch Jupyter Notebook or Google Colab.
3.  Run `logistic_reg.ipynb` for the classification task.
4.  Run `kMeans.ipynb` for the clustering task.
