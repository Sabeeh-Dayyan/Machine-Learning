# **Reinforcement Learning in Machine Learning**

This directory contains implementations of **Reinforcement Learning** algorithms, focusing on **Multi-Armed Bandit Problems**. These algorithms are widely used in online advertising, recommendation systems, and decision-making applications.

---

## 📂 **Directory Structure**
The reinforcement learning algorithms included in this directory are:

| #  | Code File | Algorithm |
|----|----------|------------|
| 1  | `1_upper_confidence_bound.py` | Upper Confidence Bound (UCB) |
| 2  | `2_thompson_sampling.py` | Thompson Sampling |

---

## 📝 **Description of Algorithms**
### 1️⃣ **Upper Confidence Bound (UCB)**
- A reinforcement learning algorithm for solving the **Multi-Armed Bandit Problem**.
- Balances **exploration and exploitation** to maximize rewards.
- Commonly used in online advertising to select the best-performing ad.
- File: `1_upper_confidence_bound.py`

### 2️⃣ **Thompson Sampling**
- A **Bayesian approach** to reinforcement learning.
- Selects actions based on **probability distributions**.
- More efficient than UCB in many real-world scenarios.
- Used in applications like A/B testing and dynamic pricing.
- File: `2_thompson_sampling.py`

---

## 📊 **Dataset**
The dataset used for both algorithms is:

- **File:** `Ads_CTR_Optimisation.csv`
- **Description:** Simulated dataset for an **ad click-through rate (CTR) optimization problem**.
- **Usage:** Helps in determining which advertisement is most effective in engaging users.

---

## 🚀 **How to Run the Code**
1. Clone the repository:
   git clone https://github.com/Sabeeh-Dayyan/Machine-Learning.git
   cd Machine-Learning/Reinforcement Learning

2. Install dependencies:
   pip install -r requirements.txt

3. Run any reinforcement learning model:
   python 1_upper_confidence_bound.py

## **🛠 Requirements**
  1. Python 3.x
  2. Libraries: NumPy, Pandas, Matplotlib, Seaborn

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## **📌 Note**
  1. The same dataset (Ads_CTR_Optimisation.csv) is used for all algorithms in this directory.
  2. File names are numbered for better organization.
  3. Contributions and improvements are welcome! 🚀

