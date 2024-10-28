# Building a Sentiment Classifier Based on the Tweet Sentiment Extraction Dataset

This repository contains a machine learning project aimed at classifying the messages in social media into three groups: neutral, positive, negative, depending on the message text. The project demonstrates the machine learning process from text preprocessing for use in ML models to training models and analyzing results.

## Project Overview

### Dataset:

Data from Kaggle competition: https://www.kaggle.com/competitions/tweet-sentiment-extraction/data?select=train.csv
Download dataset from Google Drive: https://drive.google.com/file/d/1m6z3gkNKXAcKtxX5bPRLrJHtlLh7oc9I/view?usp=sharing

### Project Objectives

1. Perform dataset EDA.
2. Perform text data vectorization using both Bag-of-Words and TF-IDF methods.
3. Compare the two vectorization methods.
4. Build a classifier based on the vectorized data.
5. Conduct an error analysis.

The project follows these key steps:

  **Data Gathering**: Collected the data from public dataset.  
  **Exploratory Data Analysis**: Explored the dataset to understand the underlying patterns and trends.  
  **Data Preprocessing**: Preprocessed and vectorized the text for use in the machine learning model.  
  **Data Modelling**: Trained machine learning models using scikit-learn to classify the texts.
    
### Technical Aspects
    
  **Library**: scikit-learn  
  **Algorithms Used**: Logistic Regression, Decision Trees, Random Forests  
  **Output**: The model predicts whether the text is positive, negative or neutral.  

