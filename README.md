# Spam-Email-Detection_NLP_ML-Project
## Introduction:

* This project provides a step-by-step guidance to build an efficient SMS spam classification model using the SMS Spam Collection dataset. By the end of this notebook, you'll have a powerful tool to help you filter out unwanted messages and ensure that your text messaging experience is smoother and safer. </span>

* The primary goal of this project is to develop a predictive model that accurately classifies incoming SMS messages as either ham or spam. We will use the SMS Spam Collection dataset, which consists of 5,574 SMS messages tagged with their respective labels. </span>

## Dataset
The dataset used for this project can be found on Kaggle. It contains a collection of email messages labeled as either 'spam' or 'ham'. 

Here is a link to dataset
https://www.kaggle.com/datasets/team-ai/spam-text-message-classification/data

## Installation
To run this project locally, you'll need to install the necessary dependencies, including libraries such as NumPy, Pandas, Matplotlib, WordCloud, NLTK, and Scikit-learn. Additionally, NLTK datasets like stopwords and punkt are required for text processing.
  
## Data Preprocessing

The preprocessing steps involved:

1. **Column Renaming**: The dataset's columns were renamed for clarity.
2. **Label Encoding:** The target labels were encoded to numerical values.
3. **Feature Engineering:** Features such as the number of characters, words, and sentences in each message were extracted.
4. **Text Preprocessing:**
      * Conversion of text to lowercase.
      * Tokenization of text into individual words.
      * Removal of special characters, stopwords, and punctuation.
       * Stemming of words to their root form.
  
These steps helped to standardize and clean the data, making it suitable for model training.
