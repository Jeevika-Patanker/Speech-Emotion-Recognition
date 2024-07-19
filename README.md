# Speech-Emotion-Recognition
This project develops a speech emotion recognition (SER) system using deep learning techniques. The system is trained on the RAVDESS dataset, consisting of audio recordings of actors expressing different emotions. Mel-Frequency Cepstral Coefficients (MFCCs) are extracted as input features for a Convolutional Neural Network (CNN) model. 
Speech Emotion Recognition (SER) using Deep Learning

Project Overview:-


This project aims to develop a speech emotion recognition (SER) system using deep learning techniques. The system is trained on the RAVDESS dataset, which consists of audio recordings of actors expressing different emotions. The goal is to classify the emotions expressed in the audio recordings into one of the eight categories: happy, sad, angry, neutral, surprised, calm, fearful, and disgusted.


Dataset:-


The RAVDESS dataset is used for this project, which consists of 1440 audio recordings of 24 actors (12 male and 12 female) expressing eight emotions.


Features Extraction:-


Mel-Frequency Cepstral Coefficients (MFCCs) are extracted from the audio recordings using the Librosa library. The MFCCs are then used as input features for the deep learning model.


Model Architecture:-


A Convolutional Neural Network (CNN) model is used for this project. The model consists of several convolutional and max-pooling layers, followed by fully connected layers. The output layer is a softmax layer with eight neurons, corresponding to the eight emotions.


Training:-


The model is trained on the training set using the Adam optimizer and categorical cross-entropy loss function. The model is trained for 100 epochs with a batch size of 64.


Results:-


The model achieves an accuracy of 79-80% on the test set.


Code:-


The code for this project is written in Python using the Keras and TensorFlow libraries. The code is organized into several sections:

Data loading and preprocessing, 

Feature extraction, 

Model architecture,

Training, 

Evaluation


Requirements:-

Python 3.x, 
Keras 2.x, 
TensorFlow 2.x, 
Librosa 0.8.x, 
Scikit-learn 0.24.x, 
Seaborn 0.11.x, 
Matplotlib 3.4.x.


How to Run:-

Clone the repository,  
Install the required libraries,  
Run the code using Python 3.x.
