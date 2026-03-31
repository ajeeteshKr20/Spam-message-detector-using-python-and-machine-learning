Spam Email/SMS Classifier (Machine Learning Mini Project)

This project is a simple implementation of spam detection using machine learning. The main goal of the project is to classify text messages into two categories: Spam or Ham (Not Spam).
I created this project to understand the basic workflow of text preprocessing, feature extraction, and model building using Python

Objective of the Project

The aim of this project is: 1 To learn how to work with text data in Python 2 To understand how TF-IDF converts text into numbers 3 To build a simple machine learning model 4 To test and evaluate a model’s performance 5 To apply ML in real-world problems like spam filtering


Files Included in the Project

1 spam_classifier.py → Main Python code
2 spam_data.csv → Dataset (optional)
3 README.md → Project documentation
4 STATEMENT.txt → Declaration file
5 spam_nb_model.joblib → Saved ML model
6 tfidf_vectorizer.joblib → Saved TF-IDF vectorizer

Tools and Libraries used 

1 Python
2 Pandas
3 Scikit-learn
4 TF-IDF Vectorizer
5 Naive Bayes Classifier
6 VS Code

How the Project Works

1. Loading the Dataset

The program tries to load a file named spam_data.csv.
If the file is missing, then a small built-in sample dataset is used so that the program can still run without errors.

2. Preprocessing the Data

The preprocessing steps include: Converting the labels “ham” and “spam” into numbers (0 and 1) Cleaning unwanted values if needed Splitting the data into training and testing sets Converting text messages to numerical vectors using TF-IDF

3. Training the Model

The model used in this project is the Multinomial Naive Bayes classifier. This model is simple, fast, and usually performs well for text classification.

4. Evaluating the Model

The program prints: Accuracy score
Precision, Recall, F1-Score
Confusion Matrix These results help us understand how well the model is working.

5. Predicting New Messages

The script also includes a function to test new messages.
You can type anything and the model will predict if it is spam or ham.

How to Run the Project

Step 1: Install the required libraries

Step 2: Run the Program

Step 3: (Optional) Add Your Own Dataset

Make a CSV file named spam_data.csv with the format
