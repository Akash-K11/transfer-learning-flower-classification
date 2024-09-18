# Flower Classification with Transfer Learning

This project demonstrates transfer learning using TensorFlow and the Xception model for classifying flower images from the "tf_flowers" dataset.

## Overview

The code implements a two-phase transfer learning approach:
1. Transfer Learning: Adapting the top layers of a pre-trained Xception model to the flower dataset.
2. Fine-tuning: Further training the entire model for improved performance.

## Requirements

- TensorFlow 2.x
- TensorFlow Datasets

## Code Structure

- Data loading and preprocessing
- Model architecture setup
- Two-phase training:
  - Transfer learning phase
  - Fine-tuning phase

## Results

The model is trained for 5 epochs in the transfer learning phase and 10 epochs in the fine-tuning phase. Check the output for accuracy and loss metrics.