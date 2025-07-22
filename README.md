# Machine-Learning-Project-Language_Detection_Model

# 🌍 Language Detection Web App

Can a machine detect what language you're typing — without knowing the meaning of your words?

This project answers that question with a simple yet powerful web application that uses **Naive Bayes classification** to detect the language of a given text input.

This project is a real-time language detection web app built using traditional machine learning techniques. It demonstrates how simple NLP tools like CountVectorizer and Multinomial Naive Bayes can be used to classify natural languages without translation or deep models.

The model is trained on labeled sentences in various languages and learns to identify language based on patterns, frequency of characters, and structure of words — not meaning. The result is a lightweight, fast, and surprisingly accurate model deployed using Streamlit.

✨ Highlights:
Converts raw text into numerical features using CountVectorizer

Classifies the language using MultinomialNB from scikit-learn

Saves model and vectorizer using pickle for reuse

Simple and responsive web interface built with Streamlit

Accepts user input and displays the predicted language instantly



## 🧠 What It Does

This web app allows users to enter any sentence, and it predicts the **language** it belongs to, based on training data. It does this without understanding the meaning — purely by analyzing word patterns and frequency.



## 🚀 Tech Stack

| Tool           | Purpose                                      |
|----------------|----------------------------------------------|
| `Python`       | Core programming language                    |
| `pandas`       | Data loading and handling                    |
| `scikit-learn` | Model training (`MultinomialNB`, `CountVectorizer`) |
| `Streamlit`    | Web application framework                    |
| `pickle`       | Saving model and vectorizer for deployment   |



