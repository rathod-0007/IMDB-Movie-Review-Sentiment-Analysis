# 🎬 IMDB Movie Review Sentiment Analysis

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://imdb-movie-review-sentiment-analysis-0007.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Overview
This project is a **Sentiment Analysis Web Application** built using **Streamlit** and **Machine Learning**. It analyzes IMDB movie reviews and classifies them as either **Positive** or **Negative** based on the textual content. 

The application uses a pre-trained model trained on the [IMDB 50K Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) to provide real-time sentiment predictions.

## 🚀 Live Demo
Check out the live application here:  
👉 **[IMDB Sentiment Analysis App](https://imdb-movie-review-sentiment-analysis-0007.streamlit.app/)**

## ✨ Features
- **Real-time Analysis**: Instant sentiment classification of user-inputted text.
- **Confidence Score**: Displays the probability/confidence of the prediction.
- **Interactive UI**: Clean and simple interface powered by Streamlit.
- **Preprocessing**: Automatic text cleaning (tokenization, stop-word removal) before inference.

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Streamlit**: For building the web interface.
- **Scikit-learn / TensorFlow**: For model training and inference.
- **NLTK / Spacy**: For Natural Language Processing tasks.
- **Pandas & NumPy**: For data manipulation.

## 📂 Project Structure
```bash
IMDB-Movie-Review-Sentiment-Analysis/
├── data/                   # Dataset files (if applicable)
├── models/                 # Pre-trained models (.pkl, .h5)
├── src/                    # Source code for preprocessing and training
├── app.py                  # Main Streamlit application
├── requirements.txt        # List of dependencies
├── README.md               # Project documentation
└── .gitignore              # Ignored files
