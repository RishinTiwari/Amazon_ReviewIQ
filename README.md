# Amazon ReviewIQ - Sentiment Analysis and Insights using LLMs

## Overview

The Amazon ReviewIQ project aims to provide valuable insights into customer reviews using state-of-the-art machine learning models, fine-tuned for sentiment analysis. The project leverages models such as RoBERTa, LLaMA, and Mistral to classify reviews into positive and negative sentiments, providing actionable insights for customers and product managers in e-commerce.

##Dataset
To use my web scraped dataset of Amazon product reviews, you can download from my kaggle link : https://www.kaggle.com/datasets/rishintiw/amazon-reviews-scraped-dataset/data

## Project Steps

1. **Data Collection**: 
   - Scraped Amazon product reviews using web scraping techniques.
   - Extracted key data fields such as Review Title, Content, Rating, and more.

2. **Data Cleaning & Preprocessing**:
   - Removed duplicates, handled missing values, and performed text normalization (e.g., tokenization, POS tagging).
   - Used techniques such as stemming and lemmatization to standardize the review text.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of ratings, review lengths, and sentiment trends.
   - Identified patterns in positive and negative reviews for better model training.

4. **Model Training**:
   - Fine-tuned models like **RoBERTa**, **LLaMA**, and **Mistral** on the review dataset to improve sentiment classification accuracy.
   - Performed hyperparameter tuning and adjusted learning rates to enhance model performance.

5. **Model Evaluation**:
   - Evaluated models based on metrics like accuracy, precision, recall, and F1-score.
   - The **RoBERTa** model achieved a high accuracy of 96.40%, demonstrating strong performance in binary sentiment classification.

6. **Dashboard/UI for Insights**:
   - Developed interactive dashboards using tools like Tableau and Dash to visualize sentiment trends.
   - Displayed sentiment analysis results, review volumes, and customer satisfaction trends.

## Key Features
- Fine-tuned **RoBERTa**, **LLaMA**, and **Mistral** models for accurate sentiment classification.
- Built an interactive dashboard for real-time insights.
- Implemented sentiment analysis on large datasets for actionable insights.


## Conclusion

This project provides a comprehensive solution for analyzing customer feedback, enabling better decision-making for both consumers and product managers. By fine-tuning state-of-the-art models and building insightful dashboards, we aim to enhance customer trust and satisfaction in e-commerce.
