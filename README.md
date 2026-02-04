# Sentiment Analysis of Real-time Flipkart Product Reviews

## 📌 Project Overview
This project analyzes real-time customer reviews from Flipkart and classifies them into **Positive** or **Negative** sentiments using Natural Language Processing (NLP) and Machine Learning techniques.

## 🎯 Objective
- Classify customer reviews into positive or negative
- Identify customer pain points from negative reviews
- Deploy the trained model as a web application

## 🗂 Dataset
- Product: YONEX MAVIS 350 Nylon Shuttle
- Total Reviews: 8,518
- Source: Flipkart (pre-scraped dataset provided)

## ⚙️ Technologies Used
- Python
- NLTK
- Scikit-learn
- TF-IDF
- Streamlit
- AWS EC2

## 🧠 Modeling Approach
- Text preprocessing (cleaning, lemmatization)
- Feature extraction using TF-IDF
- Model training with Logistic Regression / SVM
- Evaluation using F1-Score
- Hyperparameter tuning using GridSearchCV

## 🌐 Deployment
- Deployed using Streamlit
- Hosted on AWS EC2
- Accessible via public IP on port 8501

## ▶️ How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
