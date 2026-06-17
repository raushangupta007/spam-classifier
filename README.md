# 📨 Email and SMS Spam Classifier 📱

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![NLTK](https://img.shields.io/badge/NLP-NLTK--Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)

An end-to-end Natural Language Processing (NLP) and Machine Learning project designed to classify SMS and email messages as either **Spam** or **Ham** (Legitimate) with high precision.

---

## 🎯 Key Highlights
* **🧠 High Accuracy:** Achieved a stellar **97.2% Accuracy** on the test dataset.
* **🛡️ 100% Precision:** Optimized specifically for Naive Bayes to achieve **1.0 Precision**, ensuring legitimate emails (Ham) are never accidentally misclassified as Spam.
* **💻 Interactive UI:** Integrated with a clean, user-friendly frontend using **Streamlit** for real-time message testing.

---

## 🚀 Production Deployment
🌍 **Live Application:** [live](https://spam-classifier-app-gecu.onrender.com/)

---

## ⚙️ Project Workflow & Lifecycle

1. **Data Cleaning:** Handled missing values, duplicates, and performed text lowercasing.
2. **Text Preprocessing:** Tokenization, removal of special characters, stop words, and punctuation. Applied **Stemming** via NLTK to reduce words to their base forms.
3. **Vectorization:** Converted textual data into numerical features using **TF-IDF Vectorizer** (Term Frequency-Inverse Document Frequency).
4. **Model Training & Tuning:** Evaluated multiple algorithms including Logistic Regression, Support Vector Machines (SVM), and Multinomial Naive Bayes.

---

## 📊 Model Performance Evaluation

| Model | Accuracy | Precision |
| :--- | :---: | :---: |
| **Multinomial Naive Bayes** | **97.2%** | **1.0 (100%)** |
| Support Vector Machine (SVM) | 96.5% | 0.98 |
| Logistic Regression | 95.8% | 0.96 |

> **Note:** Even though some models showed similar accuracy, **Multinomial Naive Bayes** was selected as the final model due to its flawless precision score, which is critical for spam detection.

---

## 🛠 Tech Stack Used

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, NLTK, Seaborn, Matplotlib
- **Deployment/UI:** Streamlit
- **Environment:** Jupyter Notebook / VS Code

---
