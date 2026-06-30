# Hand Gesture Recognition

This project was completed as **Task 4** of the **SkillCraft Technology Machine Learning Internship**.
The objective is to build a hand gesture recognition model that can classify different hand gestures from image data for gesture-based interaction systems.

## Project Overview

The implementation uses the **LeapGestRecog** hand gesture dataset from Kaggle and trains a Convolutional Neural Network (CNN) in **Google Colab**.
To keep training practical, a smaller subset of the dataset was created and used for model development and evaluation.

## Workflow

- Download dataset from Kaggle using the Kaggle API.
- Create a smaller train/validation subset.
- Preprocess images using resizing, grayscale conversion, and normalization.
- Train a CNN model for multi-class hand gesture classification.
- Evaluate performance using accuracy, classification report, and confusion matrix.

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Kaggle API

## Outcome

This project demonstrates a complete computer vision workflow, from dataset preparation to model training and evaluation, while keeping the implementation lightweight enough for internship submission purposes.
