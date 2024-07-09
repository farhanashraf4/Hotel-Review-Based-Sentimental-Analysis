# Sentiment Analysis of Hotel Reviews

This project focuses on sentiment analysis of hotel reviews using various deep learning methodologies and word embeddings. The goal is to accurately classify the sentiment of hotel reviews to support customer decision-making.

## Overview

We implemented several deep learning models including Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), Hierarchical Attention Networks (HAN), and Recurrent Model-based Deep Learning (RMDL). We also incorporated different word embeddings such as GloVe, Word2Vec, FastText, and BERT.

### Key Findings

- A MultiChannel Convolutional Neural Network (CNN) using Word2Vec embeddings achieved an accuracy of 93.10%.
- Replacing Word2Vec with FastText embeddings in the CNN resulted in a significant improvement, achieving an accuracy of 98.65%.
- The FastText embeddings enhanced the model's comprehension of the reviews, leading to a 5.55% improvement in sentiment analysis accuracy.

## Methodologies

### Models Used

1. **Convolutional Neural Networks (CNN)**
2. **Recurrent Neural Networks (RNN)**
3. **Hierarchical Attention Networks (HAN)**
4. **Recurrent Model-based Deep Learning (RMDL)**

### Embeddings Used

1. **GloVe**
2. **Word2Vec**
3. **FastText**
4. **BERT**

### Preprocessing Techniques

- Text cleaning (removal of punctuation, stopwords, etc.)
- Tokenization
- Lemmatization
- Embedding layer preparation

## Comparative Study

A comparative study was conducted to evaluate the performance of different models and embeddings. The results are as follows:

| Model         | Embedding | Accuracy |
| ------------- | --------- | -------- |
| CNN           | Word2Vec  | 93.10%   |
| CNN           | FastText  | 98.65%   |

## Usage

### Prerequisites

- Python 3.x
- TensorFlow or PyTorch
- Numpy
- Pandas
- Gensim
- scikit-learn
