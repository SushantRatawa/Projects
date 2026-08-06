# Fake News Detection System

A Machine Learning project that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques. The project preprocesses textual data, converts it into numerical features using TF-IDF Vectorization, and trains a Logistic Regression model for binary classification.

## Features
- Text preprocessing and cleaning
- TF-IDF Vectorization
- Fake/Real news classification
- Binary classification using Logistic Regression
- Model evaluation

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Machine Learning Concepts Used
- Natural Language Processing (NLP)
- Text Preprocessing
- TF-IDF Vectorization
- Logistic Regression
- Train-Test Split
- Model Evaluation

## Dataset
fake_news_dataset dataset

The dataset contains news articles labeled as:
- Fake
- Real

Each record consists of the news title,author name,article text, and its corresponding label.

## Project Workflow
1. Load the dataset.
2. Clean and preprocess textual data.
3. Convert text into numerical vectors using TF-IDF Vectorization.
4. Split the dataset into training and testing sets.
5. Train a Logistic Regression classifier.
6. Evaluate model performance.
7. Predict whether a news article is Fake or Real.

## Results
The model successfully classifies news articles as Fake or Real using NLP techniques. TF-IDF Vectorization combined with Logistic Regression provides strong classification performance on the dataset.

## Future Improvements
- Compare multiple classification models such as Naive Bayes, Random Forest, and XGBoost.
- Deploy the model so that it can be used by actual news channels and reporters.
- Use transformer-based models such as BERT for improved accuracy.
- Build a web application for real-time fake news detection.

## Author
Sushant Ratawa
