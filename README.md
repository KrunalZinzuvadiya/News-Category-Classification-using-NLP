# News Category Classification using NLP

## Overview
This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify news articles into predefined categories. The model learns from textual data and predicts the category of a given news article based on its content.

## Features
- **Data Preprocessing:**  
  - Tokenization, punctuation removal, stop word removal.  
  - Text normalization using stemming and lemmatization.  
  - Converting text into numerical representations using TF-IDF or word embeddings.  

- **Machine Learning Models Used:**  
  - Logistic Regression  
  - Naïve Bayes (MultinomialNB)  
  - Support Vector Machine (SVM)  
  - Random Forest Classifier  

- **Performance Evaluation:**  
  - Accuracy, Precision, Recall, and F1-score metrics to evaluate model performance.  
  - Comparison of different ML models for the best classification accuracy.  

## Dataset
The dataset consists of news articles labeled into categories such as:
- **Politics**  
- **Sports**  
- **Technology**  
- **Entertainment**  
- **Business**  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn nltk scikit-learn
