YouTube Comments Sentiment Analysis using SVM

This project is a Machine Learning model developed to perform sentiment analysis on YouTube comments using the Support Vector Machine (SVM) algorithm. The goal of this project is to classify comments into Positive, Negative, or Neutral sentiments. The model was trained using a labeled dataset of YouTube comments and achieved more than 85% accuracy after proper preprocessing and training.

In this project, the complete machine learning pipeline was followed. First, the dataset was loaded using pandas and checked for missing values and incorrect data. Data cleaning was performed by removing special characters, converting text to lowercase, and eliminating unnecessary symbols. After cleaning, Exploratory Data Analysis (EDA) was done to understand the dataset structure, number of samples, and distribution of sentiment classes.

Text preprocessing techniques such as tokenization, stopword removal, and stemming were applied to prepare the text data for machine learning. Feature extraction was done using TF-IDF Vectorizer to convert text into numerical form. Feature scaling was applied to improve the performance of the SVM model.

The Support Vector Machine (SVM) algorithm was used to train the model. After training, the model was tested on unseen data and achieved accuracy greater than 85 percent, which shows that the model performs well for sentiment classification.

Dataset used in this project contains YouTube comments and their sentiment labels. The dataset was used for training and testing the machine learning model.

Technologies used in this project include Python, Pandas, NumPy, Matplotlib, Scikit-learn, and NLTK.

Project steps:

Dataset loading
Data cleaning
Exploratory Data Analysis (EDA)
Text preprocessing
Feature extraction using TF-IDF
Feature scaling
Model training using SVM
Accuracy evaluation

Files included in the project:

SVM_85_Accuracy.ipynb
YoutubeCommentsDataSet.csv
requirements.txt
README.md

This project demonstrates how machine learning can be used for sentiment analysis of social media data and can be extended further using deep learning and NLP techniques.

Author: Mohd Nadeem
MCA Data Science Student
Machine Learning Project
