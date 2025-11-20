# Deep Learning Face Recognition Project

This project focuses on building a face-recognition system by extending existing Convolutional Neural Networks (CNNs) with additional layers and retraining them on a custom dataset.
The goal is to classify images into three categories:

- Tim

- Unknown Person

- Object

Several state-of-the-art CNN architectures are fine-tuned and compared using different optimizers.

## Project Overview

Instead of training a model from scratch, this project uses transfer learning.
Pretrained CNNs are extended with new layers:

- Fully connected layers

- Batch normalization

- Dropout

- Final classification head (3-class softmax)

The networks are retrained on a labeled image dataset and evaluated for accuracy, loss, and generalization capacity.

## Models Used

The following pretrained architectures are used as base models:

- ResNet-50

- ResNet-101

- ResNet-152

- Inception-V3

Each architecture is trained twice, once with each of the following optimizers:

- ADAM

- RMSProp
