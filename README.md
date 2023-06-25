# CIFAR-10-Image-Classification
This GitHub repository contains code for training and evaluating a convolutional neural network (CNN) model on the CIFAR-10 dataset using TensorFlow.


## Dataset

The CIFAR-10 dataset is a collection of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into a training set of 50,000 images and a test set of 10,000 images. The classes are as follows: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Repository Structure

- `main.py`: The main script that loads the CIFAR-10 dataset, preprocesses the data, defines the CNN model architecture, trains the model, evaluates its performance, and generates visualizations of the results.
- `utils.py`: A utility script containing helper functions for visualizing images and performance curves.
- `requirements.txt`: A file listing the required Python packages and their versions.

## Usage

1. Install the required packages by running `pip install -r requirements.txt`.
2. Run `main.py` to train the model and evaluate its performance.
3. The script will display sample images from the CIFAR-10 dataset, normalize the image data, and perform one-hot encoding on the labels.
4. The CNN model architecture is defined and compiled using the Adam optimizer and categorical cross-entropy loss.
5. The model is trained using the training dataset for a specified number of epochs and a batch size.
6. Performance curves (accuracy, precision, and recall) are plotted using the training history.
7. The model's predictions are obtained on the test dataset, and a confusion matrix is computed and plotted.

## Results

The repository provides visualizations of the sample images, the model's architecture summary, and the performance curves during training. Additionally, a confusion matrix is generated to evaluate the model's classification accuracy on the test dataset.

The repository aims to demonstrate how to build and train a CNN model for image classification tasks using TensorFlow and apply it to the CIFAR-10 dataset. Users can modify the model architecture, hyperparameters, and training settings according to their requirements.
