# Vegetable Image Classification

This project focuses on classifying 15 different categories of vegetables using Convolutional Neural Networks (CNN). The model is trained, validated, and tested on a dataset of vegetable images, leveraging various data augmentation techniques to improve performance.

## Table of Contents
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Data Augmentation](#data-augmentation)
- [Training](#training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Results](#results)

## Dataset

The dataset consists of images of 15 different vegetable categories. Each category contains images for training, validation, and testing.

- **Training set:** 15,000 images
- **Validation set:** 3,000 images
- **Test set:** 3,000 images

## Model Architecture

The CNN architecture includes:
- Convolutional layers for feature extraction
- MaxPooling layers for downsampling
- Flatten layer to convert the 2D matrix to a vector
- Fully connected Dense layers for classification

## Data Augmentation

The training images are augmented using the following techniques:
- Rotation
- Shear
- Horizontal and vertical flipping
- Rescaling

## Training

The model is compiled using the Adam optimizer and trained for 50 epochs with checkpoints and TensorBoard callbacks.

## Evaluation

The model is evaluated on the test set to determine its accuracy and performance. The evaluation metrics include accuracy, precision, recall, and F1 score.

## Usage

To classify a new image, the model can be loaded and used to predict the class of the image. The image needs to be preprocessed to match the input size expected by the model.

## Results

The model achieved high accuracy on both the validation and test datasets. Data augmentation significantly improved the model's ability to generalize. The results demonstrate the effectiveness of using CNNs for image classification tasks.

