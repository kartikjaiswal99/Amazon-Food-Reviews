# Amazon Fine Food Reviews Analysis

This project involves applying machine learning algorithms to predict whether Amazon fine food reviews are positive. Techniques include text preprocessing, vectorization (BoW, TF-IDF, Word2Vec), and models like KNN, Naive Bayes, Logistic Regression, SVM, Decision Trees, Random Forests, and XGBoost.

## Data Source
- **Dataset**: [Kaggle - Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)

## Dataset Overview
- **Number of reviews**: 568,454
- **Number of users**: 256,059
- **Number of products**: 74,258
- **Timespan**: Oct 1999 - Oct 2012
- **Number of Attributes**: 10

### Attribute Information
- **Id**
- **ProductId** - Unique identifier for the product
- **UserId** - Unique identifier for the user
- **ProfileName**
- **HelpfulnessNumerator** - Number of users who found the review helpful
- **HelpfulnessDenominator** - Number of users who indicated whether they found the review helpful or not
- **Score** - Rating between 1 and 5
- **Time** - Timestamp for the review
- **Summary** - Brief summary of the review
- **Text** - Text of the review

## Objective
Determine whether a review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).

### Methodology
- **Positive Review**: Rating of 4 or 5
- **Negative Review**: Rating of 1 or 2
- **Neutral Review**: Rating of 3 (ignored)

## Exploratory Data Analysis (EDA)
- **Text Preprocessing**
- **Text Vectorization**
  - Bag of Words (BoW)
  - Bi-Grams and n-Grams
  - TF-IDF
  - Word2Vec
  - Avg Word2Vec
  - TFIDF weighted Word2Vec

## Applying TSNE
- **Text BoW vectors**
- **Text TFIDF vectors**
- **Text Avg Word2Vec vectors**
- **Text TFIDF weighted Word2Vec vectors**

## Machine Learning Models

### KNN (K-Nearest Neighbors)
- **Brute Force**
  - BoW
  - TFIDF
  - Avg Word2Vec
  - TFIDF Word2Vec
- **KD-Tree**
  - BoW
  - TFIDF
  - TFIDF Word2Vec

### Naive Bayes
- **Multinomial Naive Bayes**
  - BoW
  - TFIDF

### Logistic Regression
- **Logistic Regression**
  - BoW
  - TFIDF
  - Avg Word2Vec
  - TFIDF Word2Vec

### Linear SVM
- **Applying Linear SVM**
  - BoW
  - TFIDF
  - Avg Word2Vec
  - TFIDF Word2Vec

### RBF SVM
- **Applying RBF SVM**
  - BoW
  - TFIDF
  - Avg Word2Vec
  - TFIDF Word2Vec

### Decision Trees
- **Applying Decision Trees**
  - BoW
  - TFIDF
  - Avg Word2Vec

### Random Forests
- **Applying Random Forests**
  - BoW
  - TFIDF
  - Avg Word2Vec
  - TFIDF Word2Vec

### Gradient Boosting using XGBoost
- **Applying XGBoost**
  - BoW
  - TFIDF
  - Avg Word2Vec

