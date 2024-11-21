# Text Document Classification

## Overview
This project implements a text document classification model using a dataset of BBC news articles. The model categorizes documents into different labels based on their content, utilizing both deep learning (BERT) and traditional machine learning (TF-IDF with Logistic Regression).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Features](#features)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Prediction](#prediction)
- [PDF Handling with PyPDF2](#pdf-handling-with-pypdf2)
- [License](#license)

## Installation
To run this project, ensure you have the following libraries installed:
```bash
pip install numpy pandas seaborn matplotlib scikit-learn wordcloud nltk spacy transformers torch datasets tensorflow PyPDF2


Usage
Clone the repository:
bash
git clone <repository-url>
cd <repository-directory>

Open the Jupyter Notebook:
bash
jupyter notebook Text_Document_Classification.ipynb

Follow the instructions in the notebook to load the dataset, preprocess the data, visualize results, train the model, evaluate its performance, and classify new documents.
Data Description
The dataset used in this project is sourced from BBC news articles, categorized into several topics:
Business
Entertainment
Politics
Sports
Technology
Features
Data Loading: Automatically loads text files from specified directories.
Data Exploration: Displays basic statistics and visualizations.
Data Cleaning: Identifies and removes duplicates and missing values.
Text Preprocessing: Includes cleaning operations like removing HTML tags and stopwords.
Model Training: Implements BERT and TF-IDF with Logistic Regression for classification.
Data Exploration
The notebook includes sections that explore the dataset's structure, including visualizations of target category distributions.
Data Preprocessing
Preprocessing steps include:
Removing new lines and HTML tags.
Removing punctuation marks and stopwords.
Lemmatization to reduce words to their base form.
Model Training
The project trains a BERT-based model for text classification and also implements a traditional machine learning pipeline using TF-IDF vectorization.
Evaluation
The evaluation process computes various metrics such as accuracy and generates confusion matrices to assess model performance on test data.
Prediction
Functions are provided to classify new text files or PDF documents based on their content using the trained models.
PDF Handling with PyPDF2
The project includes functionality to read PDF files using PyPDF2 to extract text content for classification.
License
This project is licensed under the MIT License - see the LICENSE file for details.
text

### Instructions for Use:
1. Replace `<repository-url>` with the actual URL of your GitHub repository.
2. Save this content as `README.md` in your project directory before pushing it to GitHub.

This README provides a comprehensive overview of your project, making it easy for others (and yourself) to understand how to use it in the future. If you need any further modifications or additions, feel free to ask!
