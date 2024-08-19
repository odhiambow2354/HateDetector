# Hate Speech Detection in Google Colab

## Overview

This project is designed to classify tweets into categories such as hate speech, offensive language, and neutral content using machine learning models. This guide walks you through setting up and running the project in Google Colab.

## Features

- **Text Preprocessing**: Includes tokenization, stopword removal, and stemming.
- **Feature Extraction**: Utilizes TF-IDF and Count Vectorizer.
- **Model Training**: Implements various models including Support Vector Machine (SVM) and Logistic Regression.
- **Evaluation**: Provides metrics such as accuracy, precision, recall, and F1-score.
- **Interactive Web Interface**: Allows users to input tweets and get predictions.

## Setting Up in Google Colab

1. **Open Google Colab:**

   Go to [Google Colab](https://colab.research.google.com/) and create a new notebook.

2. **Clone the repository:**

   In a Colab cell, run the following commands to clone the repository and change the directory:

   ```python
   !git clone https:git@github.com:odhiambow2354/HateDetector.git
   %cd HateDetector

   ```

3. **Install dependencies:**

   ```
   !pip install pandas numpy scikit-learn nltk wordcloud textstat gensim gradio

   ```

4. **Upload your dataset:**
   upload the hate_speech.csv file to google colab and start running the cells as provide in the .ipynb file.

5. **Glimpse at the final hosted project with the model here:**
   http://wycliffe.pythonanywhere.com/

6. **Contributing**

   Feel free to contribute to this project. Fork the repository and submit a pull request with your improvements.
