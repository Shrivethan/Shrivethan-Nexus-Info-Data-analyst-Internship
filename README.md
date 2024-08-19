# Nexus-Info-Data-analyst-Internship

**Phase I: Project 1 - Iris Dataset Analysis (Easy Level)**

Project Overview
The Iris dataset is one of the most famous datasets used for machine learning and statistical analysis. This project aims to analyze the Iris dataset and apply basic machine learning algorithms to predict flower species based on their characteristics.

Objectives
Utilize the Iris dataset to perform a basic data science task.
Conduct a Simple Exploratory Data Analysis (EDA) to gain insights into the dataset.
Tasks
Data Collection and Loading:

Obtain the Iris dataset from a reliable source (e.g., scikit-learn, UCI Machine Learning Repository).
Load the dataset using pandas.
Exploratory Data Analysis (EDA):

Perform preliminary analysis to understand the structure and characteristics of the dataset.
Explore basic statistics, such as mean, median, standard deviation, etc., for each feature.
Visualize the data using graphs (scatter plots, histograms, pair plots) to identify relationships between features and species.
Data Preprocessing:

Handle missing values, if any.
Encode categorical variables (if required).
Scale or normalize the features.
Model Building:

Split the dataset into training and testing sets.
Choose suitable machine learning models for classification (e.g., Decision Trees, Logistic Regression).
Train the models using the training data.
Model Evaluation:

Evaluate the trained models using appropriate metrics on the test data.
Compare the performance of different models to identify the best-performing one.
Approach
Loaded the dataset into a Jupyter notebook using read_csv.
Implemented various mathematical and statistical operations on the dataset using Python libraries.
Conducted basic data exploration (EDA) with matplotlib and seaborn.
Applied machine learning algorithms like Logistic Regression and Decision Trees.
Evaluated models using metrics such as accuracy, precision, and recall.
Phase I: Project 2 - Weather Analysis (Medium Level)
Project Overview
The Weather Analysis project aims to analyze weather data to predict weather patterns based on various characteristics. This project involves a more detailed analysis and application of machine learning algorithms compared to the Iris dataset project.

Objectives
Utilize the weather dataset to perform a data analysis task.
Conduct a comprehensive Exploratory Data Analysis (EDA) to gain insights into the dataset.
Tasks
Data Collection and Loading:

Obtain the weather dataset from a reliable source.
Load the dataset using pandas.
Exploratory Data Analysis (EDA):

Perform preliminary analysis to understand the structure and characteristics of the dataset.
Explore basic statistics for each feature.
Visualize the data using graphs to identify relationships between features.
Data Preprocessing:

Handle missing values, if any.
Encode categorical variables (if required).
Scale or normalize the features.
Model Building:

Split the dataset into training and testing sets.
Choose suitable machine learning models for classification (e.g., Decision Trees, Random Forests, Support Vector Machines).
Train the models using the training data.
Model Evaluation:

Evaluate the trained models using appropriate metrics on the test data.
Compare the performance of different models to identify the best-performing one.
Model Deployment:

Select the best model based on evaluation results.
Deploy the chosen model to make predictions on new or unseen data.


# Twitter Sentiment Analysis - Internship Project Phase 2

## Overview
This project focuses on analyzing Twitter sentiment using Python, involving data preprocessing, model development, and evaluation. The process steps include:

1. **Importing Libraries & Packages:** Essential libraries like Pickle, WordCloud, and WordNetLemmatizer are used.
2. **Importing Dataset:** The Twitter dataset is loaded, with sentiment and text columns extracted and preprocessed.
3. **Preprocessing Text:** Steps include lowercasing, replacing URLs, emojis, usernames, removing non-alphabets, stopwords, and lemmatizing.
4. **Analysis of the Text:** Word clouds display frequent positive and negative words.
5. **Splitting The Data:** Data is split into training and testing sets (80:20).
6. **TF-IDF Vectorizer:** Converts text documents into vectors.
7. **Transforming Dataset:** Data transformed into `x_train` and `x_test`.
8. **Create & Evaluate Model:** Four models are used: MultinomialNB, BernoulliNB, LinearSVC, and Logistic Regression.
9. **Saving & Using Models:** The vectorizer and Logistic Regression model are saved for future sentiment predictions.

## Results
- **Logistic Regression** achieved the highest accuracy (81.26%) among the models used.

## Usage
Load the saved vectorizer and Logistic Regression model to predict sentiments of new texts.
Approach
Loaded the dataset into a Jupyter notebook using read_csv.
Implemented various mathematical and statistical operations on the dataset using Python libraries.
Conducted comprehensive data exploration (EDA) with matplotlib and seaborn.
Applied machine learning algorithms like Logistic Regression and Decision Trees.
Evaluated models using metrics such as accuracy, precision, and recall
