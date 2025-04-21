# 📧 SpamSniper - Spam Detection using Machine Learning

**SpamSniper** is a Spam Detection System that uses Natural Language Processing (NLP) and Machine Learning to classify SMS messages as spam or not spam (ham). The goal is to help automate email/message filtering and improve user security and experience.

---

## 🔍 Project Overview

- **Dataset**: SMS Spam Collection from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Tech Stack**: Python, Scikit-learn, Pandas, TF-IDF
- **Models Used**: Naive Bayes, SVM, Random Forest
- **Evaluation**: Accuracy, Precision, Recall, F1-Score

---

## 🧠 Techniques Used

- Text cleaning & preprocessing
- Tokenization
- TF-IDF Vectorization
- Model training & comparison
- Performance metrics visualization
- Model serialization with `joblib`

---

## 📁 Folder Structure


---

## 🧪 Sample Output

| Model         | Accuracy | Precision | Recall | F1 Score |
|---------------|----------|-----------|--------|----------|
| Naive Bayes   | 97.1%    | 96.5%     | 95.9%  | 96.2%    |
| SVM           | 96.8%    | 96.3%     | 95.2%  | 95.7%    |
| Random Forest | 96.2%    | 94.7%     | 95.0%  | 94.8%    |

---

## ▶️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/vulk123/SpamSniper.git
cd SpamSniper
pip install -r requirements.txt
jupyter notebook spam_detection.ipynb
import joblib
model = joblib.load('models/spam_model.joblib')


