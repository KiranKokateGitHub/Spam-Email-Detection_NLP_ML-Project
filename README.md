# Spam-Email-Detection_NLP_ML-Project
## Introduction:

* This project provides a step-by-step guidance to build an efficient SMS spam classification model using the SMS Spam Collection dataset. By the end of this notebook, you'll have a powerful tool to help you filter out unwanted messages and ensure that your text messaging experience is smoother and safer. </span>

* The primary goal of this project is to develop a predictive model that accurately classifies incoming SMS messages as either ham or spam. We will use the SMS Spam Collection dataset, which consists of 5,574 SMS messages tagged with their respective labels. </span>

## Dataset
The dataset used for this project can be found on Kaggle. It contains a collection of email messages labeled as either 'spam' or 'ham'. 

Here is a link to dataset
https://www.kaggle.com/datasets/team-ai/spam-text-message-classification/data

## Installations
To run this project locally, you'll need to install the necessary dependencies, including libraries such as NumPy, Pandas, Matplotlib, WordCloud, NLTK, and Scikit-learn. Additionally, NLTK datasets like stopwords and punkt are required for text processing aslo installed CountVectorizer and TfidfVectorizer.
  
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

## Modeling
Various machine learning models were trained and evaluated to determine the best-performing algorithm for spam classification. The models tested include:

* Support Vector Classifier (SVC)
* Random Forest (RF)
* Naive Bayes (NB)
* Gradient Boosting
* Adaboost
* Logistic Regression
* Bagging Classifier
  
The text data was vectorized using methods like **CountVectorizer** and **TfidfVectorizer**. The dataset was then split into training and testing sets to assess model performance.

## Evaluation

The performance of the models was evaluated using metrics such as accuracy, precision, recall, and F1-score.

* **Support Vector Classifier (SVC)** and **Random Forest (RF)**: Both models achieved the highest accuracy of approximately **97.58%**.
* Naive Bayes (NB): Stood out with a perfect precision score, indicating zero false positives.
* Other models, including Gradient Boosting, Adaboost, Logistic Regression, and Bagging Classifier, also demonstrated competitive performance with accuracy scores ranging from 94.68% to 96.03%.


## Conclusion

The project successfully implemented several machine learning models for spam email classification. **The Support Vector Classifier and Random Forest models demonstrated the best overall performance**. The Naive Bayes model, with its perfect precision, is particularly effective in scenarios where minimizing false positives is crucial. 
