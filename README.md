# Fashion Image Generation Using GAN.
---

## Introduction

This repository contains code for training a Generative Adversarial Network (GAN) to generate fashion images using the Fashion MNIST dataset. The implemented GAN architecture consists of a generator network responsible for generating synthetic images and a discriminator network tasked with distinguishing between real and generated images. The project utilizes TensorFlow and Keras for model development and training.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- TensorFlow Datasets
- Matplotlib


### Dataset

The project utilizes the Fashion MNIST dataset, which is available through the TensorFlow Datasets (TFDS) API. The dataset contains grayscale images of various fashion items, such as shirts, dresses, shoes, and bags.

## Model Evaluation

The trained GAN model's performance can be evaluated by assessing the generated fashion images visually or using evaluation metrics such as inception score or Frechet Inception Distance (FID).

## Results

Sample generated fashion images and training logs are available in the `images` and `logs` directories, respectively.

## Model Architecture

The GAN architecture consists of:

- **Generator:** A convolutional neural network (CNN) responsible for generating synthetic fashion images from random noise.
- **Discriminator:** Another CNN tasked with distinguishing between real and generated images.

Both the generator and discriminator networks are trained simultaneously in an adversarial manner.

## Acknowledgments

- Inspiration for GAN architecture and training strategies from research papers and online tutorials.
- Fashion MNIST dataset provided by TensorFlow Datasets.



