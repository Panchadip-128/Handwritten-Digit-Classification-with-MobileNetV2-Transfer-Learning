Handwritten Digit Classification with MobileNetV2 Transfer Learning:
---------------------------------------------------------------------
This project utilizes transfer learning with MobileNetV2, a pre-trained convolutional neural network, to classify handwritten digits from the MNIST dataset. The goal is to demonstrate how to adapt a model trained on a large dataset to a different but related task.

Project Overview:
------------------
In this project, we use the MobileNetV2 architecture, which was originally trained on the ImageNet dataset, to classify digits from the MNIST dataset. This involves:

Preprocessing the MNIST dataset:
----------------------------------
Converting grayscale images to RGB and resizing them to match the input requirements of MobileNetV2.

Building a classification model:
--------------------------------
Using MobileNetV2 as a feature extractor and adding a custom classifier.

Training and evaluating the model:
-----------------------------------
Fine-tuning the model on the MNIST dataset and assessing its performance.

Requirements:
--------------

TensorFlow
NumPy
Matplotlib
