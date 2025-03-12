# **Association Rule Learning in Machine Learning**

This directory contains the implementation of **Association Rule Learning** algorithms, which are used to uncover interesting relationships between variables in large datasets. These algorithms are commonly applied in market basket analysis and recommendation systems.

---

## 📂 **Directory Structure**
The association rule learning algorithms included in this directory are:

| #  | Code File | Algorithm |
|----|----------|------------|
| 1  | `1_apriori.py` | Apriori Algorithm |
| 2  | `2_eclat.py` | ECLAT Algorithm |

---

## 📝 **Description of Algorithms**
### 1️⃣ **Apriori Algorithm**
- A classic algorithm used for **frequent itemset mining** and **association rule learning**.
- Uses a breadth-first search strategy to identify relationships in transactional datasets.
- Helps businesses understand purchasing patterns.
- File: `1_apriori.py`

### 2️⃣ **ECLAT Algorithm**
- **Equivalence Class Clustering and Bottom-Up Lattice Traversal (ECLAT)** is a more efficient approach to finding frequent itemsets.
- Uses a **depth-first search** strategy for frequent pattern mining.
- Generally faster than Apriori for large datasets.
- File: `2_eclat.py`

---

## 📊 **Dataset**
The dataset used for both algorithms is:

- **File:** `Market_Basket_Optimisation.csv`
- **Description:** Contains transactional data from a retail store. Each row represents a transaction, and each column represents an item purchased.
- **Usage:** Helps identify frequently bought-together items, enabling optimized product placement and targeted marketing strategies.

---

## 🚀 **How to Run the Code**
1. Clone the repository:
   
   git clone https://github.com/your-username/Machine-Learning.git
   cd Machine-Learning/Association Rule Learning

2. Install dependencies:
   pip install -r requirements.txt

3. Run any association rule learning model:
   python 1_apriori.py

## **🛠 Requirements**

  1. Python 3.x
  2. Libraries: NumPy, Pandas, Matplotlib, Seaborn, Mlxtend

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## **📌 Note**

  1. The same dataset (Market_Basket_Optimisation.csv) is used for all algorithms in this directory.
  2. File names are numbered for better organization.
  3. Contributions and improvements are welcome! 🚀


