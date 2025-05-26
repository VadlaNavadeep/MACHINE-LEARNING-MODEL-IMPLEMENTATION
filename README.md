# MACHINE-LEARNING-MODEL-IMPLEMENTATION
# 📧 Spam Email Detector using Scikit-learn

A simple yet effective machine learning model to classify emails/messages as **Spam** or **Ham (Not Spam)** using a **Naive Bayes classifier**. Built with Python, Scikit-learn, and Jupyter Notebook.

---

## 📂 Project Overview

This project demonstrates:
- Loading and exploring the **SMS Spam Collection Dataset**
- Preprocessing and vectorizing text data using **TF-IDF**
- Training a **Multinomial Naive Bayes** model
- Evaluating model performance with accuracy, confusion matrix, and classification report
- Predicting custom messages

---

## 🧠 Algorithm

We use **Multinomial Naive Bayes**, a popular model for text classification tasks, due to its efficiency and high accuracy for spam detection.

---

## 📁 Dataset

- Dataset: [SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- Source (used in this notebook):  
  `https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv`
- Format: Tab-separated values (TSV)  
- Columns:
  - `label`: `ham` or `spam`
  - `message`: The actual SMS/email text

---

## 🚀 How to Run

### 📌 Requirements

Install the required libraries:
numpy, pandas , and scikit learn

## 📌 Run in Jupyter Notebook

- Clone the repo or download the `.ipynb` file  
- Open it with **Jupyter Notebook** or **JupyterLab**  
- Run the cells step by step

---

## 📊 Model Evaluation

- **Accuracy**: ~97% (may vary slightly)
- **Evaluation Metrics**:
  - Precision
  - Recall
  - F1-Score
- **Confusion Matrix**: Visualized using Seaborn

---

## 🔍 Try it Yourself

You can test custom messages with:

```python
predict_spam("You have won $1000! Call now to claim.")
predict_spam("Are we still meeting at 5 today?")

Accuracy: 0.973
              precision    recall  f1-score   support

         Ham       0.98      1.00      0.99       965
        Spam       0.96      0.85      0.90       150

