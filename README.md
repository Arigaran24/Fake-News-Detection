# 📰 Fake News Detection 

## 📌 Project Overview
This project is part of the **RISE Internship – Machine Learning & AI**.  
The objective is to build a Machine Learning model that can **classify news articles as Real or Fake** using **Natural Language Processing (NLP)** techniques.

Fake news on social media misleads people, and this project demonstrates how AI can help identify and flag misleading content.

---

## 🎯 Objectives
- Preprocess textual news data using NLP techniques  
- Convert text into numerical features using **TF-IDF**  
- Train Machine Learning classifiers to detect fake news  
- Evaluate model performance using **Accuracy and F1-Score**

---

## 📂 Dataset
**Fake and Real News Dataset**

- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset  

### Dataset Details:
| Column | Description |
|------|-------------|
| text | News article content |
| label | 0 = Fake, 1 = Real |

---

## ⚙️ Technologies Used
- Python  
- Google Colab  
- Pandas & NumPy  
- Scikit-learn  
- NLP (TF-IDF Vectorization)

---

## 🧠 Machine Learning Models
- **Passive Aggressive Classifier**
- **Support Vector Machine (SVM)**

---

## 🔄 Project Workflow
1. Import libraries and load dataset  
2. Combine fake and real news data  
3. Text preprocessing (cleaning & stopword removal)  
4. Feature extraction using TF-IDF  
5. Train-test data split  
6. Train ML models  
7. Evaluate using Accuracy & F1-score  
8. Predict fake or real news  

---

## 📊 Evaluation Metrics
- Accuracy Score  
- F1 Score  
- Classification Report  

---

## ✅ Results
- Achieved high accuracy (~93–96%)  
- Passive Aggressive Classifier performed efficiently on large text data  
- Successfully classified fake and real news articles  

---

## 🧪 Sample Prediction
```python
predict_news("Breaking: Government announces new education policy")

REAL NEWS
