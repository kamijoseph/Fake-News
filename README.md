# Fake News Detection using LSTM and Word2Vec
## Overview

This project implements a fake news detection system leveraging Word2Vec embeddings and an LSTM-based neural network. It classifies news articles into:

*Fake news* (class = 0)

*Real news* (class = 1)

Remark: The model is trained on a publicly available dataset of fake and real news articles.
---

## Features

### Data preprocessing:

Text normalization (lowercasing, special character removal)

Publisher extraction

Concatenation of title and text

### Visualization:

Distribution of news subjects

WordCloud representation of common words

Text vectorization:

Word2Vec embeddings trained on dataset

Tokenization and sequence padding for LSTM input

LSTM-based classification

### Model evaluation:

Accuracy

Precision, recall, and F1-score
---

## Model artifacts:

Trained LSTM model

Tokenizer

Word2Vec embeddings

## Dataset:
### Real:
https://raw.githubusercontent.com/laxmimerit/fake-real-news-dataset/main/data/True.csv
### Fake:
https://raw.githubusercontent.com/laxmimerit/fake-real-news-dataset/main/data/Fake.csv

The datasets above includes text, title, and subject fields, later processed and labeled for binary classification.
---

## Results

The LSTM model demonstrates strong performance in distinguishing fake vs real news.

Evaluation metrics include accuracy, precision, recall, and F1-score.

WordCloud visualizations highlight the most frequent words in fake and real news articles.
---

### License
This project is released under the MIT License.
