# learnflow-mlTask-3
# Speech Recognition with Convolutional Neural Networks

## Overview
This project involves speech recognition using the Google Speech Commands Dataset available on Kaggle. The dataset consists of various spoken commands, including "yes," "no," "up," "down," "left," "right," "stop," "go," and more.

## Dataset

The dataset used in this project is the Google Speech Commands dataset, which is available on Kaggle. It contains audio samples categorized into different classes based on the spoken words.

Dataset Link: https://www.kaggle.com/datasets/neehakurelli/google-speech-commands

## Code Overview

The code is organized into the following sections:

- **Dataset Size and Labels**: Retrieves information about the dataset, including its size and class labels.
- **Data Loading and Preprocessing**: Loads and preprocesses the audio data using the librosa library.
- **Model Architecture**: Defines a CNN model using TensorFlow and Keras.
- **Training the Model**: Trains the defined model on the preprocessed data.
- **Evaluation**: Evaluates the trained model on a test set and prints the classification report and confusion matrix.
- **Single Audio Prediction**: Provides a function to preprocess a single audio file and predict its class using the trained model.

## Dependencies

Python 3.x
TensorFlow
Librosa
NumPy
Scikit-learn
