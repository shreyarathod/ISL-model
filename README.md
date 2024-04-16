# Indian Sign Language Interpretation Convolutional Neural Network Model

## Brief Description

This project is a convolutional neural network (CNN) model designed for interpreting Indian Sign Language (ISL). The model takes images of a hand as input, analyzes the image, performs feature extraction, and eventually outputs the letter or number the sign stands for. 


## Tech Stack

- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Seaborn

## Dataset

The dataset used for training the model consists of Indian Sign Language (ISL) images. It contains a total of 42,000 images, with each sign having approximately 1,200 images. The dataset provides a diverse range of hand gestures representing different letters and numbers in Indian Sign Language.

## Preprocessing

Before feeding the images into the model, the following preprocessing steps were applied:

- **Grayscale Conversion**: The input images were converted to grayscale to simplify the image data and reduce computational complexity.
  
- **Gaussian Blurring**: Gaussian blurring was applied to reduce noise and smooth out the images, helping the model focus on important features.
  
- **Thresholding**: Thresholding was used to binarize the images, separating the background from the foreground and enhancing the contrast, which aids in feature extraction.

## Model

The model architecture consists of convolutional layers followed by dropout, normalization, pooling and dense layers. This architecture enables the model to learn hierarchical representations of features from the input images and make accurate predictions. 

