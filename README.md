# Text Classification Project: Sentiment Analysis of Movie Reviews

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Implementation](#implementation)
- [Choice of Dataset](#choice-of-dataset)
- [Data Exploration](#data-exploration)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Methodology](#evaluation-methodology)
- [Explore the Notebook](#explore-the-notebook)

## Introduction
Welcome to the Text Classification project focused on Sentiment Analysis of Movie Reviews! In an era marked by global transformations and economic uncertainties, the film industry faces unprecedented challenges. This Jupyter Notebook delves into the realm of sentiment analysis, specifically tailored to movie reviews, aiming to provide valuable insights for the film industry's adaptation and success.

## Objective
The primary objective is to conduct sentiment analysis using text classification models, comparing the effectiveness of different algorithms. The project targets categorizing movie reviews into binary classes of positive or negative sentiments. While not groundbreaking, this research contributes valuable insights for filmmakers, production companies, and stakeholders, aiding in informed decision-making regarding content creation, marketing, and audience engagement.

## Implementation
The project unfolds through data cleaning, simple textual analysis, and the construction of multiple machine learning classification models. These models are trained on a carefully chosen dataset, the [Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/), offering a balanced set of 50,000 reviews. Performance evaluation metrics such as accuracy, precision, recall, and F1-score will be employed to identify the best-performing model.

## Choice of Dataset
The [Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/), sourced from the Stanford Artificial Intelligence Laboratory, was chosen for its size, diversity, and credibility. The dataset, consisting of 25k training and 25k testing reviews, provides a balanced representation of positive and negative sentiments.

## Data Exploration
### Rating Distribution
![Rating Distribution](rating_dist.png)
Description: This image depicts the distribution of ratings for the movie reviews in the dataset.

### Words Distribution Before Stopword Removal
![Words Distribution Before Stopword Removal](words_dist.png)
Description: The distribution of words before stopword removal, lemmatization, changing words to full form, and removing identified features.

### Comparison of Words Distribution After Stopword Removal
![Comparison of Words Distribution After Stopword Removal](word_dis_compare.png)
Description: This image compares the distribution of frequently used words after the removal of stopwords.

### WordNet for Negative and Positive Sentiment
![WordNet for Negative and Positive Sentiment](word_net.png)
Description: WordNet visualization for negative and positive sentiments.

## Machine Learning Models
The following machine learning models were employed for sentiment analysis:
- Recurrent Neural Network (RNN) with L2 Regularization
- Support Vector Machine (SVM)
- Bag of Words
- BERT by Google (Based on [textattack/bert-base-uncased-imdb](https://huggingface.co/textattack/bert-base-uncased-imdb))
- Term Frequency-Inverse Document Frequency (TF-IDF)

## Evaluation Methodology
The project's success will be gauged using metrics such as accuracy, precision, recall, and F1-score. The confusion matrix will offer a detailed breakdown of the model's predictions against actual sentiments. While accuracy remains the primary metric, other considerations will be explored during model optimization.

## Explore the Notebook
Explore the notebook to uncover insights into user sentiments in the film industry, with the potential for transfer learning applications in diverse fields beyond movie reviews. Your journey into understanding and leveraging sentiment analysis begins here!
