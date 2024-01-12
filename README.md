
# Climate Change Sentiment Analysis Using Twitter Data

## Overview
This project analyzes public sentiment on climate change using a text-mining approach on Twitter data, uncovering prevalent sentiments and viewpoints.

## Research Question
What are the sentiments and opinions expressed by the public on social media regarding climate change?

## Objectives
- To perform sentiment analysis of tweets related to climate change.
- To categorize opinions into sentiment classes (positive, negative, neutral).
- To identify key words and phrases in sentiment categories.
- To develop models for classifying sentiment of new tweets.

## Dataset
The initial dataset, containing tweet IDs related to climate change, was sourced from [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/5QCCUU). The actual tweets were then scraped from Twitter using these IDs, providing a dataset of 43,943 tweets for analysis.

## Methodology
The project involves data preprocessing, sentiment analysis using VADER, exploratory data analysis, and developing machine learning models for sentiment classification.

## Tools and Technologies
- Python
- Pandas
- NLTK (VADER)
- Machine Learning Models (Random Forest, Logistic Regression)

## Notebooks and Scripts
- `Sentiment_Analysis.ipynb`: Main analysis notebook.
- `sentiment_analysis.py`: Python script for sentiment analysis.
- `tweet_scrapper.py`: Script used for scraping tweets from Twitter.

## Findings
- A close distribution of positive and negative sentiments was observed.
- Machine learning models showed the feasibility of automated sentiment classification.

## Usage
This project is useful for understanding public opinion dynamics on climate change on social media and can be adapted for similar analyses.
