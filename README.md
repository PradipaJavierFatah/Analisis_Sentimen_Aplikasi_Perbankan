Sentiment Analysis on Banking Applications
This repository contains a project focused on sentiment analysis for user reviews of various banking applications. By leveraging Natural Language Processing (NLP) techniques and machine learning models, the goal is to classify and understand user sentiments to provide actionable insights.

Introduction
Banking applications often receive feedback from users that reflect their experience and satisfaction. This project analyzes user reviews to classify sentiments as positive, negative, or neutral. The insights from this project can help improve user satisfaction and application performance.

Dataset
The dataset includes user reviews of banking applications with the following columns:

at: Timestamp of the review.
userName: The user's name.
content: The review text.
score: Review rating (1-5).
application: Name of the banking application.
Summary:
Number of Reviews: 6,170
Applications Covered: Multiple banking apps.
The dataset can be found in the file dataPerbankan.csv.

Usage
Open the main notebook:

bash
Copy code
jupyter notebook Analisis_Sentimen_Aplikasi_Perbankan.ipynb
Follow the steps in the notebook:

Data Preprocessing: Clean the review text for analysis.
Visualization: Explore the dataset distribution and review scores.
Model Training: Train and evaluate machine learning models.
Run the notebook cells sequentially to execute the analysis.

Results
This project applies several machine learning models, including:

K-Nearest Neighbors (KNN)
Random Forest
Naive Bayes
Support Vector Machine (SVM)
Comparative evaluation is performed using metrics such as accuracy, precision, recall, and F1-score.

Confusion matrices and other visualizations are provided in the notebook to illustrate model performance.

