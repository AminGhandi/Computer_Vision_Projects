# Image Classification

In this project, we aim to create a fundamental model for image classification. We employ standard techniques such as basic augmentation, normalization, and regularization to enhance the model's accuracy and stability.

## Problem Definition

The task involves analyzing x-ray images of lungs and classifying them, using computer vision modeling techniques, into two categories: pneumonia-affected or normal. Given the critical nature of healthcare problems, it is preferable for the model to overpredict. The model should strive for the highest possible accuracy, ideally achieving nearly 100% recall with a high precision score. It is crucial to diagnose any potential infection and avoid misclassifying an infected lung as healthy due to minor discrepancies. Instead of a softmax function determining the class, softmax logits can often be used to make the prediction. This decision is crucial and is based on experience with the data and the model's behavior.

## Data

The project involves creating an image classifier for a dataset comprising x-ray images of pneumonia-affected and normal lungs. The dataset will be downloaded and placed in our local directory, accessible by the Python compiler. The open-source data used in this problem set can be found [here](https://www.kaggle.com/tolgadincer/labeled-chest-xray-images).

## Approach Overview

1. Download data from the source and place it in the root directory.
2. Check for data sanity, configurable information such as shape, size, and distribution of the images.
3. Initialize data loader functionalities for training and testing.
4. Define the model architecture and validate it.
5. Define the functions for training and testing.
6. Define the optimizer for training and other training information such as regularizers, epochs, batches, etc.
7. Train and check for loss and accuracy patterns to understand the stability of the architecture and model training process.
8. Decide over multiple stages of improvements or changes, which one to select for further tuning or production.
