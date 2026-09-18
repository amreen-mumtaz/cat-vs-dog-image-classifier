# cat-vs-dog-image-classifier
A Convolutional Neural Network (CNN) based image classification project that classifies images into two categories: cats and dogs.

## Project Overview
This project uses TensorFlow and Keras to build and train a CNN model for binary image classification.
The model learns visual features from cat and dog images and predicts the class of a new image.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Model Architecture
The CNN model consists of:
- 3 Convolutional layers
- 3 Max Pooling layers
- Flatten layer
- Dense layer
- Dropout layer
- Sigmoid output layer

## Data Preprocessing
Images are resized to 150 × 150 pixels and pixel values are rescaled to the range 0–1.
Data augmentation is applied to the training images using:
- Rotation
- Width and height shifting
- Zooming
- Horizontal flipping
Validation images are only rescaled and are not augmented.

## Training
The model was trained using:
- Batch size: 32
- Image size: 150 × 150
- Epochs: 10
- Optimizer: Adam
- Loss function: Binary Crossentropy
- Evaluation metric: Accuracy

## Results
The model achieved approximately 79% validation accuracy during training.

## Dataset path
https://www.kaggle.com/datasets/tongpython/cat-and-dog

├── .gitignore
├── data/
└── results/
