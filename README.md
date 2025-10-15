# CNN Facial Recognition Project

This repository contains the implementation of a Convolutional Neural Network (CNN) model for facial recognition. The model classifies images of faces into different categories based on a labeled dataset.

## Project Overview

Facial recognition is a key technology in security and authentication systems. This project implements a custom CNN architecture to accurately classify face images while addressing overfitting through data augmentation and regularization.

## Features

- Custom CNN architecture with convolutional, batch normalization, activation, and pooling layers.
- Data augmentation techniques including rotation, shifts, shearing, zoom, and flips.
- Training and validation on a labeled facial image dataset.
- Performance evaluation including accuracy, precision, recall, and F1 score.
- Visualization of training loss and accuracy through epochs.

## Files in the Repository

- `CNN_Facial_recognition.ipynb`: Jupyter notebook with complete code for data loading, model building, training, testing, and evaluation.
- `CNN-Report.pdf`: Report explaining the theoretical background, methodology, architecture details, and evaluation results.

## Installation

1. Install required packages:

pip install tensorflow keras pandas numpy matplotlib scikit-learn tqdm plotly


## Usage

- Run the Jupyter notebook `CNN_Facial_recognition.ipynb` to train and evaluate the model.
- The notebook includes detailed steps for preprocessing, model definition, data augmentation, and performance analysis.

