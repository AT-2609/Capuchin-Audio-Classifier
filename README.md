# Capuchin-Audio-Classifier

This project builds a deep learning pipeline to detect Capuchin bird calls from forest audio recordings using Convolutional Neural Networks (CNNs) and spectrogram analysis.

Overview
The system processes raw audio files, converts them into spectrograms, and trains a CNN model to classify whether a Capuchin call is present. It then performs sliding-window inference on long forest recordings and outputs detection counts in a CSV file.

Features
Audio preprocessing with TensorFlow
Spectrogram generation (STFT)
CNN-based binary classification
Sliding window prediction on long recordings
Post-processing and grouping of detections
Export of results to results.csv
Tech Stack
Python
TensorFlow / Keras
NumPy
Google Colab
Git & GitHub
How It Works
Load and preprocess audio clips
Convert audio to spectrograms
Train CNN model on labeled clips
Run inference on forest recordings
Group consecutive detections
Export results to CSV
Output
The final output is a results.csv file containing:

Recording filename
Number of detected Capuchin calls
Author
Built as a deep learning audio classification project using TensorFlow.

I added a requirements.txt so anyone can reproduce or deploy the project using pip install -r requirements.txt.
