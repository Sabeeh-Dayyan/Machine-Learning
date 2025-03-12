# **Regression Models in Machine Learning**

This directory contains various **regression algorithms** implemented in Python, along with corresponding datasets. Each algorithm is structured systematically with its dataset and implementation script.

## 📂 **Directory Structure**
The files are organized in a sequential manner for better readability:

| #  | Dataset File | Code File | Algorithm |
|----|-------------|----------|------------|
| 1  | `1.a_Salary_Data_SLRM.csv` | `1.b_simple_linear_regression.py` | Simple Linear Regression |
| 2  | `2.a_50_Startups_MLRM.csv` | `2.b_multiple_linear_regression.py` | Multiple Linear Regression |
| 3  | `3.a_Position_Salaries_PRM.csv` | `3.b_polynomial_regression.py` | Polynomial Regression |
| 4  | `4.a_Position_Salaries_SVR.csv` | `4.b_support_vector_regression.py` | Support Vector Regression |
| 5  | `5.a_Position_Salaries_DTR.csv` | `5.b_decision_tree_regression.py` | Decision Tree Regression |
| 6  | `6.a_Position_Salaries_RFR.csv` | `6.b_random_forest_regression.py` | Random Forest Regression |

## 📝 **Description of Algorithms**
### 1️⃣ **Simple Linear Regression**
- Models the relationship between a single independent variable and a dependent variable.
- File: `1.b_simple_linear_regression.py`

### 2️⃣ **Multiple Linear Regression**
- Extends simple linear regression to multiple independent variables.
- File: `2.b_multiple_linear_regression.py`

### 3️⃣ **Polynomial Regression**
- Captures non-linear relationships by adding polynomial features.
- File: `3.b_polynomial_regression.py`

### 4️⃣ **Support Vector Regression (SVR)**
- Uses Support Vector Machines for regression tasks.
- File: `4.b_support_vector_regression.py`

### 5️⃣ **Decision Tree Regression**
- Utilizes decision trees to model complex relationships.
- File: `5.b_decision_tree_regression.py`

### 6️⃣ **Random Forest Regression**
- An ensemble technique that combines multiple decision trees for better accuracy.
- File: `6.b_random_forest_regression.py`

## 📊 **Datasets**
Each regression algorithm has its respective dataset for training and evaluation. The dataset files are prefixed with `.a_` and stored alongside the corresponding scripts.

## 🚀 **How to Run the Code**
1. Clone this repository:  
   
   git clone https://github.com/Sabeeh-Dayyan/Machine-Learning.git
   cd Machine-Learning/Regression

2. Install dependencies (if needed):
   pip install -r requirements.txt
   
3. Run any regression model:
   python 1.b_simple_linear_regression.py

## **🛠 Requirements**
  Python 3.x
  Libraries: NumPy, Pandas, Matplotlib, Scikit-Learn 

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.
