# 💳 Credit Card Fraud Detection using Random Forest

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning**.  
It applies **data preprocessing**, **imbalanced data handling (SMOTE)**, and **classification modeling** to identify fraudulent activities effectively.

---

## 🧠 Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn  
- **Visualization Tools:** Matplotlib, Seaborn  
- **Dataset Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Environment:** Google Colab  
- **Model Used:** Random Forest Classifier  

---

## ⚙️ How It Works
1. Downloaded dataset directly from Kaggle using **KaggleHub** for easy reproducibility.  
2. Preprocessed and standardized the features for better model performance.  
3. Balanced the dataset using **SMOTE (Synthetic Minority Oversampling Technique)**.  
4. Trained and evaluated the **Random Forest** classifier to identify fraudulent transactions.  
5. Visualized results with **confusion matrix** and **classification report**.

---

## 📊 Key Features
- Detects fraud transactions in a highly imbalanced dataset.  
- Demonstrates use of **SMOTE** to handle data imbalance.  
- Showcases **data preprocessing**, **model training**, and **evaluation** steps.  
- Can be extended with more ML algorithms for comparison.

---

## 🚀 How to Run
1. Open the notebook in **Google Colab**.  
2. Install dependencies:
   ```bash
   !pip install kagglehub imbalanced-learn
