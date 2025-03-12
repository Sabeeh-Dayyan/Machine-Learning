# **Natural Language Processing (NLP) in Machine Learning**

This directory contains an implementation of **Natural Language Processing (NLP)** techniques, specifically for sentiment analysis using a **Bag of Words (BoW) model**. The dataset used consists of restaurant reviews, and the goal is to classify reviews as **positive or negative** based on their content.

---

## 📂 **Directory Structure**
The NLP-related files included in this directory are:

| File | Description |
|------|------------|
| `natural_language_processing.py` | Python script implementing NLP for sentiment analysis |
| `Restaurant_Reviews.tsv` | Dataset containing restaurant reviews for training and testing |
| `README.md` | Documentation for the NLP implementation |

---

## 📝 **Description of Implementation**
### **Natural Language Processing for Sentiment Analysis**
- **Dataset:** The `Restaurant_Reviews.tsv` file contains restaurant reviews labeled as **positive or negative**.
- **Text Preprocessing:** Includes tokenization, stemming, and stop-word removal.
- **Feature Extraction:** Implements the **Bag of Words (BoW) model** for vectorizing text data.
- **Classification Model:** Uses a machine learning model (e.g., Naïve Bayes, Logistic Regression, or Random Forest) to classify reviews.

---

## 📊 **Dataset**
- **File:** `Restaurant_Reviews.tsv`
- **Format:** Tab-Separated Values (TSV)
- **Description:** Contains restaurant reviews with their corresponding sentiment labels (positive or negative).

---

## 🚀 **How to Run the Code**
1. Clone the repository:
   git clone https://github.com/Sabeeh-Dayyan/Machine-Learning.git
   cd Machine-Learning/NLP

2. Install dependencies:
   pip install -r requirements.txt

3. Run any reinforcement learning model:
   python natural_language_processing.py

## **🛠 Requirements**
  1. Python 3.x
  2. Libraries: NumPy, Pandas, NLTK, Scikit-Learn, Matplotlib

## **📜 License**
  This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

## **📌 Note**
  1. The same dataset (Restaurant_Reviews.tsv) is used for all NLP experiments in this directory.
  2. Ensure that all dependencies are installed before running the script.
  3. Contributions and improvements are welcome! 🚀

