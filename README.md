# Denoising Autoencoder on MNIST

This project demonstrates how to use an autoencoder neural network to remove noise from images, using the MNIST dataset. It includes data preprocessing, noise injection, model construction, training, and result visualization.

## Overview

The notebook walks through the process of:
- Loading and preprocessing MNIST digit images
- Adding synthetic noise for training a denoising model
- Building a convolutional autoencoder
- Training and evaluating the model
- Visualizing original, noisy, and denoised images

## Features

- Uses the MNIST dataset for demonstration
- Custom noise generation and data augmentation
- Autoencoder built with Keras and TensorFlow
- Visual comparison of noisy input and reconstructed clean output

## How to Run

This notebook is intended for use with **Google Colab**:

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Run each cell sequentially to execute the full pipeline
3. The notebook will display before-and-after images to demonstrate the denoising effect

## Output

- Visualization of the denoising effect on test images
- Trained autoencoder performance shown through side-by-side image comparisons
