# Social Media Sentiment Analysis Using Twitter Dataset

## Project Overview
This project focuses on performing **sentiment analysis on Twitter data** to classify opinions expressed in tweets as **positive, negative, or neutral**. The system leverages natural language processing (NLP) and machine learning techniques to extract meaningful insights from unstructured social media data.

---

## Problem Statement
With the massive growth of social media platforms such as Twitter, millions of users post opinions, reviews, and comments daily. These opinions contain valuable information for businesses, researchers, and policymakers, but analyzing them manually is impractical.  
The goal of this project is to develop an automated sentiment analysis system that can classify tweets into sentiment categories and provide actionable insights.

---

## Methodology
The process followed in this project includes:

1. **Data Collection**  
   - Twitter dataset collected from Kaggle and other sources.
   - Tweets are pre-processed by removing URLs, hashtags, special characters, numbers, and stop words.

2. **Preprocessing**  
   - Tokenization  
   - Lemmatization  
   - Stop word removal  
   - Handling negations and repeated characters  

3. **Feature Extraction**  
   - Bag of Words  
   - TF-IDF  
   - N-grams  

4. **Machine Learning Models**  
   - Naive Bayes  
   - Support Vector Machine (SVM)  
   - Long Short-Term Memory (LSTM) for deep learning  

5. **Evaluation**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

---

## Features
- Classifies tweets as Positive, Negative, or Neutral.
- Handles noisy and unstructured Twitter data.
- Provides visualizations for sentiment distribution.
- Scalable for large datasets.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**: NLTK, Scikit-learn, Keras, TensorFlow, Pandas, Matplotlib  
- **Dataset**: Twitter data (from Kaggle and public datasets)  

---

## Getting Started

### Clone the repository
```bash
git clone https://github.com/AnanyaBhaskarNaik/SocialMediaSentimentAnalysis.git
