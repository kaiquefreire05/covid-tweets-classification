# Sentiment Analysis on COVID-19 Tweets

Author: [Kaíque Freire dos Santos]<br>
Date: [2024/03/03]

This Jupyter Notebook performs sentiment analysis on tweets related to the COVID-19 pandemic using machine learning techniques. The notebook utilizes Python libraries such as pandas, numpy, matplotlib, seaborn, nltk, scikit-learn, and wordcloud.

## Introduction

With the outbreak of the COVID-19 pandemic, there has been a significant increase in social media discussions surrounding the virus. Understanding the sentiment of these discussions can provide valuable insights into public opinion and attitudes towards the pandemic.

## Data

The dataset used in this analysis consists of tweets collected during the COVID-19 pandemic. It includes information such as the tweet's text, sentiment label, and other relevant metadata.

* **Training Data:** Contains 41,157 tweets with 6 columns.
* **Test Data:** Contains 3,798 tweets with 6 columns.
  
## Data Preprocessing

Before performing sentiment analysis, the following preprocessing steps are applied to the text data:

* Conversion to lowercase
* Removal of user mentions, URLs, hashtags, numbers, punctuation, and non-Latin characters
* Removal of stopwords
* Tokenization

## Exploratory Data Analysis (EDA)

The EDA phase involves the following steps:

* Visualization of tweet distribution across different locations.
* Analysis of the distribution of sentiment labels.
* Visualization of common words used in tweets for each sentiment category using word clouds.

## Model Training

A Multilayer Perceptron (MLP) classifier is trained using the Bag-of-Words approach for text representation. The model is trained on the training data and evaluated on the test data.

## Results

The trained model achieves an accuracy of approximately 82.28% on the test data. Additionally, a confusion matrix is generated to visualize the model's performance across different sentiment categories.

## Conclusion

This notebook demonstrates the process of sentiment analysis on COVID-19 tweets using machine learning techniques. The trained model can be utilized to analyze sentiment trends and public opinion regarding the pandemic on social media platforms.





