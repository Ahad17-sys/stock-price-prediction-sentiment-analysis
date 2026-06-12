# 📈 Market Trend Forecasting Through Sentiment Analysis of Financial Tweets

Developed an intelligent stock market forecasting system that integrates transformer-based sentiment analysis of financial social media data with historical market indicators. Leveraging RoBERTa and machine learning techniques, the solution enhances trend prediction accuracy and supports data-driven investment insights.

## Overview

This project combines financial tweet sentiment analysis with historical stock market data to predict stock market trends. A fine-tuned RoBERTa model extracts contextual sentiment features from financial tweets, which are integrated with financial indicators and processed using a Random Forest classifier for accurate trend forecasting.

## Key Features

- Financial tweet preprocessing and cleaning
- Sentiment analysis using RoBERTa
- Contextual embedding extraction
- Feature fusion of sentiment and financial indicators
- Random Forest-based stock trend prediction
- Performance evaluation and visualization

## System Architecture

```text
Financial Tweets Dataset          Stock Market Dataset
            │                              │
            └──────── Data Collection ─────┘
                           │
                           ▼
              Data Preprocessing
                           │
                           ▼
                 Fine-tuned RoBERTa
                           │
                           ▼
            Contextual Embedding Extraction
                           │
                           ▼
                  Feature Fusion
      (RoBERTa Embeddings + Financial Features)
                           │
                           ▼
               Random Forest Classifier
                           │
                           ▼
                  Model Evaluation
                           │
                           ▼
                 Stock Trend Prediction
