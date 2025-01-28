# oose - Speech Emotion Recognition (SER)

Overview

Speech Emotion Recognition (SER) is a project developed to classify human emotions from audio recordings. This system aims to bridge the gap between human expression and machine understanding by utilizing advanced signal processing and machine learning techniques. It has applications in human-computer interaction, mental health monitoring, and affective computing.

Features

Emotion Analysis: Classifies emotions such as happiness, sadness, anger, and more.
Real-Time Processing: Supports processing audio inputs for real-time applications.
Robust Architecture: Built to generalize across diverse speakers and emotional contexts.


Technologies Used

Programming Language: Python
Libraries/Frameworks:
TensorFlow or PyTorch for deep learning.
Scikit-learn for machine learning and model evaluation.
Librosa for audio feature extraction.
NumPy and Pandas for data manipulation.
Matplotlib or Seaborn for visualization.


Dataset (from Kaggle): TESS (Toronto Emotional Speech Set)


System Workflow

1. Data Collection: Utilize TESS dataset for diverse emotional expressions.

2. Data Preprocessing: Noise reduction, normalization, and feature extraction (e.g., MFCCs).

3. Model Training: Implement deep learning models (CNN/RNN) to identify emotions.

4. Evaluation: Use metrics like accuracy, precision, recall, and F1 score.

5. Testing: Includes unit, integration, and usability testing for functionality and robustness.



Dependencies

Python 3.x

Required packages:

tensorflow
numpy
pandas
librosa
matplotlib
scikit-learn

Install them using:

pip install -r requirements.txt


Implementation Highlights

Preprocessing Module: Cleans and processes raw audio data.
Feature Extraction: Extracts key features like pitch and rhythm using Librosa.
Machine Learning Models: Implements and trains CNNs/RNNs for emotion detection.
Integration: Includes an API for emotion prediction, enabling future integration with chatbots or interactive systems.
