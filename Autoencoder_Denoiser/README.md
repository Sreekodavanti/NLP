# Autoencoder for MNIST Dataset

This project implements a basic autoencoder using PyTorch to compress and reconstruct images from the MNIST dataset. The model also demonstrates capabilities for image denoising and generating images from random latent space samples.

## Overview

The autoencoder consists of an encoder that compresses the input images into a lower-dimensional latent space, and a decoder that reconstructs the images from this latent representation. The project showcases:
- Training the autoencoder on the MNIST dataset.
- Denoising capabilities through the addition of Gaussian noise.
- Visualization of the learning process and model performance.

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
