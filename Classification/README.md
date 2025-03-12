# **Classification Models in Machine Learning**

This directory contains the implementation of various **classification algorithms** using Python. All the models are trained and tested using the dataset `Social_Network_Ads.csv`.

---

## 📂 **Directory Structure**
The classification algorithms are structured as follows:

| #  | Code File | Algorithm |
|----|----------|------------|
| 1  | `1_logistic_regression.py` | Logistic Regression |
| 2  | `2_k_nearest_neighbors.py` | K-Nearest Neighbors (KNN) |
| 3  | `3_support_vector_machine.py` | Support Vector Machine (SVM) |
| 4  | `4_kernel_svm.py` | Kernel SVM |
| 5  | `5_naive_bayes.py` | Naïve Bayes |
| 6  | `6_decision_tree_classification.py` | Decision Tree Classification |
| 7  | `7_random_forest_classification.py` | Random Forest Classification |

---

## 📝 **Description of Algorithms**
### 1️⃣ **Logistic Regression**
- A statistical model that predicts binary outcomes.
- File: `1_logistic_regression.py`

### 2️⃣ **K-Nearest Neighbors (KNN)**
- Classifies a new data point based on the majority vote of its neighbors.
- File: `2_k_nearest_neighbors.py`

### 3️⃣ **Support Vector Machine (SVM)**
- Finds the optimal hyperplane for classification.
- File: `3_support_vector_machine.py`

### 4️⃣ **Kernel SVM**
- An advanced version of SVM that applies kernel tricks for non-linearly separable data.
- File: `4_kernel_svm.py`

### 5️⃣ **Naïve Bayes**
- A probabilistic classifier based on Bayes’ Theorem.
- File: `5_naive_bayes.py`

### 6️⃣ **Decision Tree Classification**
- A tree-based model that splits the dataset into subsets using feature conditions.
- File: `6_decision_tree_classification.py`

### 7️⃣ **Random Forest Classification**
- An ensemble model that combines multiple decision trees for better accuracy.
- File: `7_random_forest_classification.py`

---

## 📊 **Dataset**
The dataset used for all classification models is:

- **File:** `Social_Network_Ads.csv`
- **Description:** Contains features related to social network users, helping to predict purchasing behavior.
- **Columns:** User ID, Gender, Age, Estimated Salary, Purchased

---

## 🚀 **How to Run the Code**
1. Clone the repository:

   git clone https://github.com/Sabeeh-Dayyan/Machine-Learning.git
   cd Machine-Learning/Classification

2. Install dependencies:
   pip install -r requirements.txt

3. Run any classification model:
   python 1_logistic_regression.py

## **🛠 Requirements**
  1. Python 3.x
  2. Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## **📌 Note**
  1. All classification models use the same dataset (Social_Network_Ads.csv).
  2. File names are prefixed with numbers for structured readability.
  3. Contributions are welcome! 🚀


