# Twitter Comments Segregation Project

## Overview
This project aims to segregate Twitter comments based on their sentiment (positive, negative, or neutral). It uses natural language processing (NLP) techniques and machine learning algorithms to classify the comments.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

## Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## Data Collection
The dataset used in this project consists of Twitter comments, which were collected using the Twitter API. Each comment is labeled with its corresponding sentiment.

## Data Preprocessing
Data preprocessing steps include:
- Loading the dataset
- Checking for and handling missing values
- Tokenization
- Removing stop words
- Stemming

## Model Training
Various machine learning models were trained, including:
- Multinomial Naive Bayes
- Logistic Regression
- K-Nearest Neighbors (KNN)

The models were evaluated based on their accuracy, precision, recall, and F1-score.

## Model Evaluation
Confusion matrices and classification reports were generated for each model to assess their performance.

## Results
The Multinomial Naive Bayes model achieved the highest accuracy in segregating Twitter comments.

## Future Work
Future improvements include:
- Enhancing the dataset with more diverse comments
- Experimenting with deep learning models
- Implementing real-time sentiment analysis

## License
This project is licensed under the MIT License.
