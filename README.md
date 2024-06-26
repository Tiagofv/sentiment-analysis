# IMDB Sentiment Analysis
This project performs sentiment analysis on the IMDB movie review dataset using Hugging Face's Transformers library.
Description
This Python script analyzes the sentiment of movie reviews from the IMDB dataset. It uses a pre-trained model through Hugging Face's pipeline API to classify reviews as positive or negative. The script processes the data in batches for efficiency and provides various evaluation metrics to assess the model's performance.
# Features

Loads the IMDB dataset using Hugging Face's datasets library
Utilizes a pre-trained sentiment analysis model
Implements batch processing for efficient prediction
Provides a progress bar using TQDM for better visibility of the prediction process
Calculates and displays key performance metrics:

Accuracy
Precision
Recall
F1 Score


Generates a confusion matrix for detailed error analysis

# Requirements

Python 3.6+
transformers
datasets
scikit-learn
numpy
tqdm

# Installation

Clone this repository:
Copygit clone https://github.com/tiagofv/sentiment-analysis.git
cd sentiment-analysis

Install the required packages:
Copypip install transformers datasets scikit-learn numpy tqdm


# Usage
Run the script with:
Copypython sentiment_analysis.py
The script will automatically download the IMDB dataset, perform sentiment analysis, and display the results.
Output
The script will display:

Progress of the prediction process
Accuracy, Precision, Recall, and F1 Score of the model
A confusion matrix showing true positives, true negatives, false positives, and false negatives
