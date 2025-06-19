# 💳 Detecting Frauds in Financial Transactions

> A Machine Learning-powered system to identify suspicious financial activities and enhance transactional security through predictive analytics.

---

## 📌 Overview

This project focuses on detecting fraudulent activities in financial transactions using multiple **classification algorithms**. With imbalanced datasets being a major challenge, techniques like **SMOTE** are employed to ensure model robustness. Each model is evaluated using a **confusion matrix** to analyze performance across key metrics like precision, recall, and F1-score — which are crucial for fraud detection tasks.

---

## 🔍 Features

- In-depth Exploratory Data Analysis (EDA)  
- Data preprocessing and class balancing with **SMOTE**  
- Implementation and evaluation of multiple machine learning models  
- Confusion matrix visualizations to assess performance  
- Focused on minimizing false negatives (frauds missed)

---

## 🧠 Models Used

The following models were implemented and compared:

1. 🌲 **Random Forest Classifier**  
2. ⚡ **XGBoost Classifier**  
3. 📊 **K-Nearest Neighbors (KNN)**  
4. 📉 **Histogram-Based Gradient Boosting Classifier**  
5. 🌳 **Decision Tree Classifier**

Each model was analyzed using:

- **Confusion Matrix**  
- **Classification Report**  
- **ROC-AUC Score**

---

## 🛠️ Tech Stack

- Python  
- Jupyter Notebook  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost  
- Imbalanced-learn (for SMOTE)

---

## 📁 Project Structure
  ```php
📦 Detecting-Frauds-in-Financial-Transaction/
│
├── 📄 Detecting Frauds in Financial Transaction.ipynb
└── 📄 README.md



# Detecting-Frauds-in-Financial-Transaction

Many individuals and organizations today rely heavily on financial transactions, leading to an exponential increase in the volume and complexity of these transactions. Consequently, the risk of fraudulent activities—such as credit card fraud, identity theft, and money laundering—has risen significantly. Traditional rule-based fraud detection systems struggle to adapt to the rapidly evolving patterns of fraudulent behaviour, thereby underscoring the necessity for machine learning techniques in advanced fraud analysis. This system develops a robust model designed to predict and prevent fraud by meticulously analysing historical transaction data. Utilizing supervised learning methods such as Decision Trees and Random Forests, the model classifies transactions as either legitimate or suspicious. Feature engineering plays a pivotal role in this process, enabling the identification of critical trends related to time, location, transaction type, and user behaviour. The system evaluates sophisticated algorithms, including Random Forest and Gradient Boosting, based on comprehensive performance metrics such as accuracy, precision, and recall. By addressing the dynamic challenges of fraud detection, this approach illustrates how machine learning can significantly enhance the security and efficiency of financial institutions. The implementation effectively identifies anomalies and prevents fraudulent transactions, providing a vital tool in safeguarding financial systems against the threats posed by fraudulent activities.

