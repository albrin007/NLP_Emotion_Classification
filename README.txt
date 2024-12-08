Sentiment Analysis with Naive Bayes and SVM
This project demonstrates a text classification pipeline for analyzing emotions from textual data. It preprocesses the data, extracts features using TF-IDF, and trains two machine learning models: Naive Bayes and SVM.

Table of Contents
Project Description
Requirements
Dataset
Usage
Results
Acknowledgements
Project Description
The goal of this project is to classify text data into predefined emotion categories (e.g., anger, joy, fear). The pipeline includes:

Text preprocessing (lowercasing, tokenization, punctuation removal, stopword removal)
Feature extraction using TF-IDF
Model training and evaluation using:
Naive Bayes
Support Vector Machine (SVM)
Requirements
To run this project, you need the following libraries installed:

Python 3.x
pandas
nltk
scikit-learn
Install the required libraries using:

bash
Copy code
pip install pandas nltk scikit-learn
Dataset
The dataset must be a CSV file containing at least two columns:

Comment: The text data to classify
Emotion: The target labels for each text (e.g., "anger", "joy")
Place the dataset in the project directory and ensure its path is correctly specified in the script.

Usage
Clone the repository or download the script.
Ensure the required libraries are installed.
Update the text_column and emotion_column variables in the script to match your dataset's column names.
Run the script:
bash
Copy code
python text_classification.py
Results
The script trains and evaluates two models:

Naive Bayes: Known for its simplicity and efficiency.
SVM: Effective for text classification tasks with high-dimensional data.
Model performance is displayed using accuracy and F1-score metrics.

Acknowledgements
NLTK for text preprocessing tools
scikit-learn for machine learning models