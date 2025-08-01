# 📰 Fake News Prediction using Machine Learning
A machine learning application that classifies news articles as real or fake using Natural Language Processing (NLP) techniques and a logistic regression model.

🚀 Project Overview
This project addresses the problem of fake news detection by training a model to classify the authenticity of news articles. It includes data preprocessing, TF-IDF vectorization, model training, and a Streamlit-powered user interface for real-time predictions.

💻 Tech Stack
Python
scikit-learn – For logistic regression and model evaluation
Streamlit – For building the interactive web interface
Pandas / NumPy – Data handling and transformations
TF-IDF Vectorizer – For text feature extraction
Pickle – For saving the trained model and vectorizer

📄 What's Inside
fake_news_model.pkl
Trained logistic regression model saved with Pickle.

vectorizer.pkl
TF-IDF vectorizer used to convert input text to feature vectors.

app.py
Main Streamlit app that accepts user input and displays predictions.

requirements.txt
Contains required Python libraries:

streamlit
pandas
numpy
scikit-learn

🧠 How It Works
News text is entered by the user in the app.
The input is processed using a saved TF-IDF vectorizer.
The logistic regression model predicts:
0 → Fake news
1 → Real news
The result is displayed immediately in the UI.
Japanjot Singh
Data Scientist & ML Enthusiast
📬 sjapanjots@gmail.com
