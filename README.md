# Amazon Alexa Sentiment Analysis with LSTM
This repository contains a Python script for sentiment analysis on the Amazon Alexa dataset using Long Short-Term Memory (LSTM) networks. The LSTM model is built using TensorFlow and Keras.

# Dataset
The dataset used for this project is the Amazon Alexa Reviews dataset, which contains verified reviews of Amazon Alexa products along with corresponding feedback ratings. The dataset is in the form of a TSV file (amazon_alexa.tsv), where each row represents a review and its associated feedback rating.

# Requirements
Make sure you have the following libraries installed:
- pandas
- scikit-learn
- TensorFlow
- Keras

# Script Explanation
The script sentiment_analysis.py performs the following tasks:
- Loads the Amazon Alexa dataset.
- Preprocesses the data, including tokenization and padding of text sequences.
- Builds an LSTM model using Keras.
- Compiles the model with the Adam optimizer and binary crossentropy loss.
- Trains the model on the training data with a specified number of epochs and batch size.
- Evaluates the model's performance on the test data.
- Makes predictions on new data.
You can customize the script by adjusting parameters such as the number of epochs, batch size, and learning rate.

# Results
After running the script, you will see the test loss and accuracy of the trained model, as well as predictions on new data.
