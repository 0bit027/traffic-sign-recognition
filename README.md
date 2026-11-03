# Traffic Sign Recognition using CNN

## Overview

This project focuses on traffic sign classification using a Convolutional Neural Network (CNN) implemented with TensorFlow and Keras.

The model is trained and evaluated using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset, which contains 43 different classes of traffic signs.

The goal is to develop a deep learning model capable of recognizing traffic signs from input images.

## Dataset

- Dataset: German Traffic Sign Recognition Benchmark (GTSRB)
- Number of classes: 43
- Training data: A balanced subset containing 200 randomly selected images per class
- Test data: 12,630 images

The dataset is not included in this repository.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Model Training

A Convolutional Neural Network (CNN) was developed for image classification.

The model was trained for 30 epochs using the prepared training dataset. Its performance was evaluated on a separate test dataset.

## Results

**Test Accuracy: 90.82%**

Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The confusion matrix provides an overview of correctly and incorrectly classified traffic signs across all 43 classes.

## How to Run

1. Clone this repository.
2. Download and prepare the GTSRB dataset separately.
3. Open `AIProjekat.ipynb` using Jupyter Notebook or Google Colab.
4. Configure the dataset paths.
5. Run the notebook cells to train and evaluate the model.

## Future Improvements

- Experiment with different CNN architectures.
- Apply data augmentation techniques.
- Improve classification performance on challenging classes.
- Explore real-time traffic sign recognition.

## Applications

Traffic sign recognition is an important component of Advanced Driver Assistance Systems (ADAS) and autonomous driving technologies.

This project demonstrates a practical application of deep learning and computer vision in the automotive domain.
