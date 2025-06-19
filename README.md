# Sentiment Analysis App 💬

A simple **Sentiment Analysis Web App** using:

- Logistic Regression Classifier
- TF-IDF Vectorizer
- NLTK for preprocessing
- Streamlit for Web UI

## Features

Analyze sentiment for:
- Single text input  
- CSV file upload  
- Excel (.xlsx) file upload  

Shows:
- Positive / Neutral / Negative counts  
- Model accuracy (78.34%)  
- Download predictions as CSV  

Clean and modern UI with color themes  

## How to Run Locally

## Clone repo
git clone https://github.com/your_username/sentiment-analysis.git
cd sentiment-analysis

## Install dependencies
python -m venv venv
venv\Scripts\activate     # Windows

Then install requirements:
pip install -r requirements.txt

## Run the Streamlit app
streamlit run app.py

## Project Structure
sentiment-analysis/
├── model/
│   ├── logistic_regression_model.pkl
│   ├── tfidf_vectorizer.pkl
├── app.py
├── requirements.txt
└── README.md

## Sentiment Analysis App
 
You can access the live app here:(https://adarshagra-1-sentimental-analysis-app-c7jfry.streamlit.app/)


## Model Information
Model: Logistic Regression
Vectorization: TF-IDF
Dataset: Twitter Airline Sentiment Dataset
Model accuracy: 78.34%

## Future Enhancements
Add more ML models (e.g., SVM, XGBoost)
Add visualizations: WordCloud, sentiment trends over time
Upload multiple files at once

## Author
Adarsh Agrahari.
