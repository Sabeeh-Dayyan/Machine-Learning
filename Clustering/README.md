# **Clustering Models in Machine Learning**

This directory contains implementations of **unsupervised learning clustering algorithms** using Python. These models analyze customer segmentation based on the dataset `Mall_Customers.csv`.

---

## 📂 **Directory Structure**
The clustering algorithms are structured as follows:

| #  | Code File | Algorithm |
|----|----------|------------|
| 1  | `1_k_means_clustering.py` | K-Means Clustering |
| 2  | `2_hierarchical_clustering.py` | Hierarchical Clustering |

---

## 📝 **Description of Algorithms**
### 1️⃣ **K-Means Clustering**
- A centroid-based clustering algorithm that partitions data into **K clusters**.
- Uses an iterative approach to minimize the sum of squared distances within each cluster.
- File: `1_k_means_clustering.py`

### 2️⃣ **Hierarchical Clustering**
- A tree-based clustering algorithm that builds a **hierarchical structure** of clusters.
- Can be **Agglomerative (bottom-up)** or **Divisive (top-down)**.
- File: `2_hierarchical_clustering.py`

---

## 📊 **Dataset**
The dataset used for both clustering models is:

- **File:** `Mall_Customers.csv`
- **Description:** Contains information about mall customers, such as age, income, and spending score, which helps in customer segmentation.
- **Columns:** Customer ID, Gender, Age, Annual Income (k$), Spending Score (1-100)

---

## 🚀 **How to Run the Code**
1. Clone the repository:
     git clone https://github.com/Sabeeh-Dayyan/Machine-Learning.git
     cd Machine-Learning/Clustering

2. Install dependencies:
     pip install -r requirements.txt

3. Run any clustering model:
    python 1_k_means_clustering.py

## **🛠 Requirements**

1. Python 3.x
2. Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, Scipy

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## **📌 Note**
  1. The same dataset (Mall_Customers.csv) is used for all clustering models.
  2. The file names are numbered for better organization.
  3. Contributions and suggestions are welcome! 🚀

