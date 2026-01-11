# Mood-Based Music Therapy Platform 🎧

An NLP-based machine learning project that detects user emotions from text input and recommends suitable music categories to support emotional well-being.

## Features
- Emotion detection using NLP
- TF-IDF vectorization + Logistic Regression
- Achieved ~94% accuracy on test data
- Supports emotions such as joy, fear, anger, and sadness
- Rule-based music recommendation logic

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

## How It Works
1. User inputs a text describing their mood
2. Text is cleaned and vectorized using TF-IDF
3. Machine learning model predicts the emotion
4. Emotion is mapped to music categories for recommendation

## Dataset
Emotion-labeled text dataset (~5,900 samples)

## Results
Model Accuracy: ~94%
