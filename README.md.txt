# AG News Classification

## Overview

A Natural Language Processing project for classifying news articles into four different categories using machine learning and neural network models.

The four categories are:

* World
* Sports
* Business
* Sci/Tech

## Dataset

AG News Classification Dataset.

The dataset is downloaded using KaggleHub.

## Technologies

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Seaborn
* WordCloud
* TF-IDF
* Logistic Regression

## Preprocessing

The news title and description were combined into a single text field.

The text was preprocessed using:

* Lowercasing
* HTML and URL removal
* Removing non-alphabetic characters
* Stopword removal
* Lemmatization

## Feature Extraction

TF-IDF was used to transform the news articles into numerical feature vectors.

Unigrams and bigrams were used to capture both individual words and short phrases.

## Classification Model

A multiclass Logistic Regression classifier was trained to classify news articles into four categories:

1. World
2. Sports
3. Business
4. Sci/Tech

## Neural Network

A simple feedforward Neural Network was also implemented using Keras.

The network contains:

* Dense layer with 128 neurons
* Dropout
* Dense layer with 64 neurons
* Dropout
* Output layer with 4 classes

Early stopping was used during training to help prevent overfitting.

## Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report
* Confusion Matrix

## Visualization

The project includes:

* Confusion Matrix
* Word Clouds
* Frequent words by category

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open:

`AG_News_Classification.ipynb`

Run the notebook cells sequentially.

## Project Structure

```text
AG-News-Classification/
│
├── AG_News_Classification.ipynb
├── README.md
└── requirements.txt
```
