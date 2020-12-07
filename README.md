This repository contains the source code for the article "Convolutional Neural Networks on Small Datasets with Transfer Learning, Synthetic Data Generation, and Data Sampling" submitted to Computers & Geosciences. The dataset used in this paper can be requested from the corresponding author at isleyen@mines.edu.

# CNN_trasferlearning.py
Trains a ResNet CNN for roof fall hazard detection. Images should be separated into "train" and "val" folders prior to using this script. Also, inside these folders, images should be placed under a folder titled with their labels, e.g. "hazard" and "non-hazard". It uses a transfer learning approach with a network trained on ImageNet dataset. The script uses PyTorch library.
Default batch size is 16, and the default number of epochs is 25.
It calculates and prints the confusion matrix.


# GaborFilter.m
Runs a gabor filter and calculates the variance of the filtered image.
Language: Matlab
Library: Image Processing Toolbox, Statistics and Machine Learning Toolbox
Input: Directory of the image files
