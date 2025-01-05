# ML Projects

This repository contains multiple machine learning projects focused on solving real-world problems using various algorithms.

## 1. Movie Recommender System
This project uses a Restricted Boltzmann Machine (RBM) model, enhanced with Autoencoders, to recommend movies based on user preferences. The dataset is the MovieLens dataset, consisting of 100,000 ratings from 943 users on 1,682 movies.

### Key Features:
- Uses RBM and Autoencoders to improve recommendation accuracy.
- MovieLens data includes ratings, demographic info, and user preferences.

## 2. Fraud Detection
This project uses Self-Organizing Maps (SOM) for fraud detection in credit card applications. The dataset contains applications from 691 users.

### Key Features:
- Utilizes Self-Organizing Maps to identify fraudulent applications.
- Dataset consists of 691 credit card applications with user details.

## 3. Stock Price Prediction
This project uses Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) units to predict Google stock prices. The dataset spans from 1/3/12 to 12/30/16.

### Key Features:
- Uses LSTM to forecast stock prices based on historical data.
- The dataset includes Google stock prices from 2012 to 2016.

## 4. Text Classification of YouTube Comments
This project classifies 250,000 Romanized English YouTube comments into three categories: "Doubt," "Feedback," and "Irrelevant."

### Key Features:
- Tackles noisy, Romanized English text, overcoming inconsistent grammar and spelling variations.
- Models trained include RNN-LSTM and fine-tuned BERT Base Uncased.
- Preprocessed data and utilized TF-IDF, Word2Vec, SVM, KNN, and Random Forest.
- Achieved 0.6968 accuracy with RNN-LSTM, outperforming BERT Base Uncased (0.43).

## Setup

To set up the projects locally, follow these steps:
1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the respective Python scripts for each project.


