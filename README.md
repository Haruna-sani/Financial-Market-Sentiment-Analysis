# Financial Sentiment Analysis using Machine Learning and Deep Learning

## Introduction
This project focuses on financial sentiment analysis using various machine learning (ML) and deep learning (DL) models. The dataset consists of labeled financial news articles, which are processed using different Natural Language Processing (NLP) techniques, including Bag of Words, Term Frequency-Inverse Document Frequency (TFIDF), Tokenization and Sequence padding.

## Preprocessing Techniques
- **Bag of Words**: Converts text data into numerical features based on word occurrence.
- **TFIDF**: Assigns weights to words based on their frequency and importance in the text corpus.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Used to balance the dataset for ML models.
- **Tokenization and Sequence padding**: Used for preprocessing the text for the DL algorithms.
- **Class Weights**: Applied to deep learning models to handle class imbalance.

## Machine Learning Models & Accuracies
The following classifiers were used for sentiment classification:

| Model  | Bag of Words Accuracy | TFIDF Accuracy |
|--------|----------------------|---------------|
| Random Forest (RF) | 0.675  | 0.6125 |
| XGBoost (XGB) | 0.6875 | 0.6125 |
| AdaBoost (ADA) | 0.7250 | 0.6125 |

## Deep Learning Models & Accuracies
| Model  | Accuracy |
|--------|----------|
| LSTM | 0.6500 |
| Bi-LSTM | 0.7375 |
| GRU | 0.6625 |

## Accuracy Comparison Plot
![image](https://github.com/user-attachments/assets/976a7418-0fdb-42a1-8087-f252c345d175)

## Conclusion
This project demonstrates the effectiveness of different ML and DL models for financial sentiment analysis. While traditional ML models perform well with Bag of Words, deep learning models, particularly Bi-LSTM, achieve the highest accuracy. Future improvements could involve hyperparameter tuning and exploring transformer-based architectures like BERT.


