# BERT-based Text Classification with IMDB Movie Reviews

## Introduction
In my NLP journey, I've been following HuggingFace's NLP course, delving into Transformer models and their applications. One fundamental concept is Encoders, which play a crucial role in NLP tasks. While Encoders and Decoders are often used together in sequence-to-sequence models for generative tasks, they can also be used independently for tasks requiring input understanding, like sentence classification and named entity recognition.

In this project, I implemented the BERT (Bidirectional Encoder Representations from Transformers) model for text classification using the IMDB movie dataset.

**Dataset**: You can download the IMDB dataset from [here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) (50K movie reviews).

## Project Highlights
To deepen my understanding, I took the following steps in this project:

### 1. Custom Dataset Class
I created a custom dataset class to handle the IMDB movie reviews data efficiently. This class is responsible for data loading and preprocessing.

### 2. Custom BERT Classifier
I built a custom BERT-based text classifier for sentiment analysis. The BERT model used here is BERT base. The classifier has the capability to determine the sentiment of movie reviews as positive or negative.

### 3. Training and Evaluation
I trained the BERT model on the IMDB dataset, fine-tuning it for text classification. Evaluation metrics, such as accuracy and classification reports, were used to assess the model's performance.

### 4. Predictions
I tested the model's predictive abilities by inputting text samples and predicting their sentiment.

## Getting Started
To run this project on your own, follow these steps:

1. Clone the repository.
2. Create a virtual environment using `python -m venv venv`.
3. Install the necessary dependencies using `pip install -r requirements.txt`.

Feel free to explore the code and adapt it to your own projects. Enjoy your NLP journey!

## Creator
Drishya Karki# Encoder-Implementation-BERT
