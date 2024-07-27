# Hate Speech Detection on Twitter

This project focuses on the detection of hate speech on Twitter using various natural language processing (NLP) and machine learning techniques. The project explores different feature extraction methods, including TF-IDF, sentiment analysis, and Doc2Vec, and evaluates multiple machine learning models to determine the most effective approach.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Feature Extraction](#feature-extraction)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Visualization](#visualization)
- [Confusion Matrix](#confusion-matrix)
- [Conclusion](#conclusion)

### Installation
To run this project, you need to have Python installed along with the necessary libraries. You can install the required libraries using the provided command.

### Dataset
The dataset used in this project is `HateSpeechData.csv`, which contains tweets labeled as hate speech, offensive speech, or neither. The dataset is loaded and a new column `text length` is added to represent the length of each tweet.

### Data Preprocessing
The preprocessing steps include:
1. Removal of punctuation and capitalization
2. Tokenizing
3. Removal of stopwords
4. Stemming

### Feature Extraction
#### Word Cloud
Visualizing the most commonly used words in the dataset through a word cloud.

#### TF-IDF
TF-IDF feature extraction to transform the text data into numerical features.

#### Sentiment Analysis
Using VADER sentiment analysis to extract sentiment-related features from the tweets.

#### Doc2Vec
Training a Doc2Vec model and extracting document vectors to represent the tweets in vector space.

### Model Training and Evaluation
#### Logistic Regression
Training and evaluating a logistic regression model for hate speech detection.

#### Random Forest
Training and evaluating a random forest classifier for hate speech detection.

#### Naive Bayes
Training and evaluating a Naive Bayes classifier for hate speech detection.

#### Support Vector Machine (SVM)
Training and evaluating a Support Vector Machine for hate speech detection.

#### Comparison of Models
Visualizing the accuracy of different models to compare their performance.

### Results
The accuracy and performance of each model are presented in a comparison chart. The logistic regression and support vector machine models performed better than the others.

### Visualization
#### Word Cloud
Word clouds for the entire dataset and for hate and offensive speech specifically.

### Confusion Matrix
The confusion matrix helps to understand the misclassifications made by the model. It provides insights into the performance of the model by showing the true and predicted values for each class.

### Conclusion
This project demonstrates the effectiveness of various NLP techniques and machine learning models in detecting hate speech on Twitter. The results highlight the importance of feature extraction methods and model selection in achieving high accuracy and reliable performance in hate speech detection tasks.
