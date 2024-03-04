# **Sentiment Analysis for Product Reviews**

**columns** = ['marketplace', 'customer_id', 'review_id', 'product_id', 'product_parent', 'product_title', 'product_category', 'star_rating', 'helpful_votes', 'total_votes', 'vine', 'verified_purchase', 'review_headline', 'review_body', 'review_date', 'sentiment']

## Overview
This project focuses on performing sentiment analysis on product reviews obtained from an e-commerce platform. The goal is to develop a model that can classify each review as positive, negative, or neutral based on the text content. This project aims to enhance understanding of natural language processing and machine learning techniques for sentiment classification.

## Table of Contents
Project Description
Tools Used
High-Level Steps
Deliverables
## Project Description
As an analyst, you will work with a dataset comprising text reviews and associated ratings from an e-commerce platform. The dataset includes various attributes such as customer ID, product ID, review headline, review body, star rating, and sentiment. The main tasks involved in this project include data preprocessing, exploratory data analysis (EDA), model building, evaluation, and developing a sentiment analysis dashboard.

## Tools Used
- Python libraries: Pandas, scikit-learn, spaCy
- Jupyter Notebook for documentation and code development
- GitHub for version control and collaboration
- Streamlit for developing the sentiment analysis dashboard
## High-Level Steps
### Data Preparation: Load the dataset and perform initial exploration to understand its structure and contents.

### Exploratory Data Analysis (EDA): Analyze the distribution of ratings and explore any patterns in the data.

### Data Preprocessing: Clean the text data by removing irrelevant characters, tokenizing, removing stopwords, and lemmatizing.

### Sentiment Labeling: Assign sentiment labels (positive, negative, neutral) based on the associated star ratings.

### Text Vectorization: Convert the preprocessed text data into numerical form using TF-IDF vectorization.

### Model Building: Select a machine learning model (e.g., Support Vector Machine) and train it on the training data.

### Model Evaluation: Assess the performance of the trained model using evaluation metrics such as accuracy, precision, recall, and F1-score.

### Sentiment Analysis Dashboard: Develop a Streamlit web application to visualize the model's performance and provide insights into sentiment analysis results.


