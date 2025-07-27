# Sentiment Analysis of Tweets

## Project Overview
This project builds a machine learning model to classify tweets as **positive** or **negative** sentiment. It aims to help businesses monitor public opinion on social media for timely insights and decision-making.

## Dataset
The dataset used is the [Sentiment140](https://www.kaggle.com/kazanova/sentiment140) Twitter dataset, containing 1.6 million tweets labeled with sentiment polarity.

The dataset is balanced, with 800,000 positive and 800,000 negative tweets, ensuring fairness in model training and evaluation.

## Methodology
- Text preprocessing: cleaning, tokenization, and stopword removal  
- Feature extraction using TF-IDF vectorization  
- Classification model trained using Logistic Regression  
- Model evaluation with accuracy, precision, recall, and confusion matrix

## Results
The model achieved 78.42% accuracy on the test set. The results demonstrate effective classification of tweet sentiment, useful for social media monitoring.

## Files
- `sentiment_analysis.ipynb`: Jupyter notebook with data processing, model training, and evaluation  
- `model.joblib`: Saved trained model

## How to Run
Open the notebook to explore data, run the model training pipeline, and make predictions on new tweets.

---

Feel free to reach out if you have any questions or feedback!