# 📧 SMS Spam Detection

A machine learning project to classify SMS messages as **spam** or **ham (non-spam)** using text data and **Natural Language Processing (NLP)** techniques.

---

## 🔍 Overview

This project builds an SMS spam detection model using text preprocessing, feature extraction, and classification algorithms.  
It helps automatically filter out spam messages from genuine messages.

---

## 📊 Dataset

- **Source:** https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset  
- **Columns:**
  - `target` : Label (0 = ham, 1 = spam)
  - `text` : SMS message content
- **Encoding:** `latin-1`

---

## ⚙️ Steps

1. Data cleaning and preprocessing  
2. Tokenization, stopword removal, and stemming  
3. Feature extraction using  **TF-IDF**  
4. Model training (Naive Bayes / Random Forest / Logistic Regression)  
5. Final model selection: **Multinomial Naive Bayes**
6. Model evaluation using accuracy, precision, recall, and F1-score  

---

## 🧠 Text Preprocessing

- Lowercasing
- Tokenization
- Removing punctuation and numbers
- Stopword removal
- Stemming using **PorterStemmer**

---

## 🛠️ Tools Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## ✅ Results

- Achieved accuracy of **~97%**
- Model performs well on unseen SMS messages
- Low false positive rate for ham messages

![image alt](https://github.com/Anish-Das2003/sms-spam-detection-classifier/blob/9a8c3c92f1de0b81073640b610e8c3a8c3c69962/sms%20detection.png)
---

