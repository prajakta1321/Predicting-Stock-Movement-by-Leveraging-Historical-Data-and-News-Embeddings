# Predicting-Stock-Movement-by-Leveraging-Historical-Data-and-News-Embeddings

✅ Overview

This project aims to predict short-term stock price movement by combining:

✅ Historical stock market data

✅ Financial news embeddings

Unlike traditional models that rely only on price trends, this approach integrates structured numerical features with unstructured textual data to improve predictive performance.

The project demonstrates an end-to-end Machine Learning pipeline involving data preprocessing, feature engineering, NLP embedding generation, model training, and evaluation.

✅ Objective

To build a classification model that predicts whether a stock will move Up or Down, using:

Technical indicators derived from historical price data

Context-aware embeddings generated from financial news


✅ Methodology
1. Data Collection

Historical stock data  

Financial news articles aligned with stock dates

2. Data Preprocessing

Handling missing values

Date alignment between stock data and news

Feature scaling

Text cleaning  

3. Feature Engineering

From Historical Data:

Daily returns

Rolling averages

Volatility indicators

Momentum-based features

From News Data:

Text embeddings capturing semantic meaning

Sentiment-related contextual signals

4. Feature Integration

Merged:

Numerical technical indicators

News embeddings

Resulting in a combined feature space for model training.

5. Model Training

Supervised classification models

Train-test split

Hyperparameter tuning (if applicable)

6. Model Evaluation

Accuracy

Precision

Recall

