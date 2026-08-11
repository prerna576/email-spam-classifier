# Email Spam Classifier

## Project Description

This project is a Machine Learning-based Email Spam Classifier that identifies whether a given email/message is Spam or Ham (Not Spam).

The project involves preprocessing text data, converting text into numerical features using TF-IDF, training different Machine Learning classification algorithms, and comparing their performance to identify a suitable model for spam classification.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- TF-IDF Vectorization
- Machine Learning

## Machine Learning Algorithms

The project explores and compares different classification algorithms, including:

- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Other classification algorithms implemented in the notebook

## Project Workflow

1. Load the email/message dataset.
2. Clean and preprocess the text data.
3. Split the dataset into training and testing sets.
4. Convert text into numerical features using TF-IDF Vectorization.
5. Train multiple Machine Learning classification models.
6. Evaluate and compare the models using appropriate performance metrics.
7. Select the suitable model for spam classification.
8. Save the trained model and TF-IDF vectorizer for future use.

## Project Files

- `Email spam detector using ML.ipynb` - Main project notebook
- `email.csv` - Dataset
- `spam_classifier.pkl` - Saved trained Machine Learning model
- `tfidf_vectorizer.pkl` - Saved TF-IDF vectorizer

## Objective

The objective of this project is to develop an effective Machine Learning system that can automatically classify emails/messages as Spam or Ham.

