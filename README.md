# 📊 Sentiment Analysis on Banking Applications

This repository focuses on sentiment analysis for user reviews of various banking applications. By leveraging **Natural Language Processing (NLP)** techniques and **Machine Learning models**, the goal is to classify and understand user sentiments, providing actionable insights to improve application performance.

---

## 📖 Introduction

Banking applications often receive feedback from users that reflects their experience and satisfaction. This project analyzes these user reviews to classify sentiments into:
- **Positive**
- **Neutral**
- **Negative**

The insights from this analysis can help improve:
- User satisfaction
- Application functionality
- Banking services optimization

---

## 📂 Dataset

The dataset consists of user reviews from various banking applications. Below is the structure of the dataset:

| Column        | Description                                     |
|---------------|-------------------------------------------------|
| **`at`**      | Timestamp of the review                        |
| **`userName`**| The user's name                                |
| **`content`** | The review text                                |
| **`score`**   | Review rating (1-5)                            |
| **`application`** | Name of the banking application            |

### **Dataset Summary**:
- **Number of Reviews**: 6,170
- **Applications Covered**: Multiple banking apps

📂 The dataset is stored in the file: **`dataPerbankan.csv`**

---

## 📊 Results
The project utilizes multiple machine learning models to classify user sentiments. These include:
- 🔍 K-Nearest Neighbors (KNN)
- 🌲 Random Forest
- 🧠 Naive Bayes
- 🔗 Support Vector Machine (SVM)

## Evaluation Metrics:
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

## Visualization:
Key insights are visualized through:
- Confusion Matrices
- Performance Charts
- Data Distribution Plots

