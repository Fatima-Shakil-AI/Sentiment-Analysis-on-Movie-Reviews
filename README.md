**Sentiment Analysis using LSTM**
This project uses an LSTM (Long Short-Term Memory) neural network to perform sentiment analysis on the IMDB movie review dataset. The goal is to classify reviews as positive or negative, demonstrating the ability of deep learning to understand text and emotions.

**Project Overview**
Sentiment analysis is one of the most popular applications of Natural Language Processing (NLP).
This project leverages TensorFlow and Keras to train an LSTM-based model that learns semantic meaning from movie reviews and predicts whether the sentiment is positive or negative.

**Dataset**
Dataset Used: IMDB Movie Reviews (available directly from Keras datasets)
Classes: Positive (1) and Negative (0)
Training Samples: 25,000
Testing Samples: 25,000

**Model Architecture**
Embedding Layer
LSTM Layer (128 units)
Dense Layer with Sigmoid Activation
Optimizer: Adam
Loss Function: Binary Crossentropy

**Results**
Metric	Value
Training Accuracy	~88%
Validation Accuracy	~86%
Loss	Decreases steadily over epochs
