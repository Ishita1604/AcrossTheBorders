# AcrossTheBorders: Sentiment Analysis and Fraud Job Detection

This project aims to analyze and classify the sentiments of tweets related to Syrian refugees residing in Turkey and detect fraudulent job tweets using Natural Language Processing (NLP) techniques.

## Problem Statement

Due to the ongoing conflict in Syria, many Syrians continue to seek refuge in Turkey. This immigration has resulted in the development of resentment in Turkey towards the refugees, leading to global concern. This hatred has often manifested as social backlash, especially via Twitter. Additionally, many Syrian refugees are targeted by Turkish criminals through fraudulent job offers.

## Proposed Solution

To address the issues of online hatred and fraudulent job offers, we propose the following solutions:

### Sentiment Analysis

We developed a Machine Learning (ML) model to perform sentiment analysis on tweets regarding Syrian refugees in Turkey. The model classifies tweets into three categories: positive, negative, or neutral. This analyzed data can be used by the Turkish government to identify and potentially take legal action against individuals spreading hatred online.

### Fraud Job Detection

We also created a separate ML model to detect fraudulent job tweets targeting Syrian refugees. By identifying and flagging these tweets, we aim to protect refugees from exploitation and help authorities take appropriate action against perpetrators.

## Project Structure

The project is structured into two main components:

1. **Sentiment Analysis**:
    - Data Collection: Gathering tweets related to Syrian refugees in Turkey.
    - Data Preprocessing: Cleaning and preparing the data for analysis.
    - Model Training: Training a sentiment analysis model using various ML algorithms.
    - Sentiment Classification: Classifying tweets into positive, negative, or neutral categories.

2. **Fraud Job Detection**:
    - Data Collection: Gathering tweets that may include job offers targeting Syrian refugees.
    - Data Preprocessing: Cleaning and preparing the data for analysis.
    - Model Training: Training a model to detect fraudulent job offers using NLP techniques.
    - Fraud Detection: Identifying and flagging potentially fraudulent job tweets.

## Implementation Details

### Sentiment Analysis

- **Data Collection**: Using Twitter API to collect tweets containing specific keywords related to Syrian refugees.
- **Data Preprocessing**:
  - Removing special characters, links, and stop words.
  - Tokenization and lemmatization.
- **Model Training**:
  - Using algorithms such as LinearSVC.
  - Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.
- **Classification**: Applying the trained model to classify the sentiments of new tweets.

### Fraud Job Detection

- **Data Collection**: Using Twitter API to collect tweets containing job-related keywords and filtering those targeting Syrian refugees.
- **Data Preprocessing**:
  - Similar steps as sentiment analysis preprocessing.
- **Model Training**:
  - Using algorithms such as Random Forest.
  - Evaluating model performance using appropriate metrics.
- **Detection**: Applying the trained model to detect and flag fraudulent job offers in new tweets.

## Tools and Technologies

- Programming Language: Python
- Libraries: scikit-learn, NLTK, pandas, NumPy, TensorFlow/Keras
- Data Collection: Twitter API
- Data Visualization: Matplotlib, Seaborn
- Development Environment: Jupyter Notebook, Google Colab

## Future Work

- Improving the accuracy of the sentiment analysis and fraud detection models.
- Expanding the dataset to include more diverse and extensive tweet samples.
- Implementing a real-time monitoring system for detecting online hatred and fraudulent job offers.
- Collaborating with governmental and non-governmental organizations to take action based on the analyzed data.

## Conclusion

The AcrossTheBorders project addresses the critical issues of online hatred and fraudulent job offers targeting Syrian refugees in Turkey. By leveraging the power of NLP and ML, this project aims to provide actionable insights to authorities and protect vulnerable communities from exploitation and abuse.