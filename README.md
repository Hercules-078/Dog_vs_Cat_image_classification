# Dog vs Cat Image Classification
## Overview
A deep learning project for binary image classification that distinguishes between dog and cat images using Convolutional Neural Networks and transfer learning approaches.

## Custom CNN Model
Built a Convolutional Neural Network from scratch with Dropout and Batch Normalization layers.\
Performance:\
Training Accuracy: 97.00% | Training Loss: 0.0855\
Validation Accuracy: 77.28% | Validation Loss: 1.0421

## Transfer Learning without Data Augmentation
Implemented transfer learning using pre-trained models with data augmentation techniques.\
Performance:\
Training Accuracy: 92.86% | Training Loss: 0.1697 \
Validation Accuracy: 91.48% | Validation Loss: 0.1993

## Transfer Learning with Fine-Tuning
Applied fine-tuning to the pre-trained model for optimized performance.\
Performance:\
Training Accuracy: 99.89% | Training Loss: 0.0052\
Validation Accuracy: 95.20% | Validation Loss: 0.1859

## Tech Stack
Python | TensorFlow/Keras | NumPy | Matplotlib | OpenCV
## Key Results
Progressive improvement: 77.28% → 91.48% → 95.20% validation accuracy
