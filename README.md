Vegetable Image Classification
This project focuses on classifying 15 different categories of vegetables using Convolutional Neural Networks (CNN). The model is trained, validated, and tested on a dataset of vegetable images, leveraging various data augmentation techniques to improve performance.

Table of Contents
Dataset
Model Architecture
Data Augmentation
Training
Evaluation
Usage
Results
Dataset
The dataset consists of images of 15 different vegetable categories. Each category contains images for training, validation, and testing.

Training set: 15,000 images
Validation set: 3,000 images
Test set: 3,000 images
Installation
Clone the repository:

Clone the repository from GitHub and navigate to the project directory.
Create a virtual environment and activate it:

Set up a virtual environment and activate it.
Install the required packages:

Install all necessary dependencies from the requirements file.
Model Architecture
The CNN architecture includes:

Convolutional layers for feature extraction
MaxPooling layers for downsampling
Flatten layer to convert the 2D matrix to a vector
Fully connected Dense layers for classification
