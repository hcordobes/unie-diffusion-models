# Diffusion Models

## Description
This lab provides a full architecture and training example using Diffusion Models. It is developed using TensorFlow. It follows, with minor adaptations, the code present at the official Keras documentation.

## Tasks

### DDIM flower example (MAIN exerciese)

The file ddim.ipynb contains the example from Keras documentation by András Béres. It contains a good explanation of the steps. It runs a DDIM schema (remember, faster than DDPM as it takes a non-Markovian approximation which allows some step-skipping).
The executon of this code takes around 2 hours on a T4 instance in Google Colab.

This example will:
 * use oxford_flowers102 dataset
 * define a U-Net architecture
 * use an advanced encoding of noise variance (similar to the positional encoding present in Transformer architectures)
 * use a quality metric called Kernel Inception Distance 

### MNIST example

WORK IN PROGRESS

Example exercise by [Vedant Jumle](https://medium.com/@vedantjumle)

This example will:
* use MNIST data as training data
* define an encoding and decoding architecture using a variational scheme
* make a full training
* generate new sample data using the decoder

## Environment
These examples run within a **Google Colab T4 instance**. To open this notebook on Google Colab please use [this URL](https://colab.research.google.com/github/hcordobes/unie-diffusion-models/blob/main/src/Diffusion%20Models%20MNIST.ipynb). 
As this is a private repository, Google Colab will request an OAuth2 authorization to use your credentials to access this resource on a pop-up. Grant access and the exercise should be available to you.

## Project structure

```bash
.
├── datasets/
│ └── LICENSE.txt
├── src/
│ ├── ddim.ipynb # Flowers exercise
│ ├── LICENSE.txt  # MIT License
│ └── Diffusion Models MNIST.ipynb  # MNIST exercise
└── README.md
```

## Licenses
- **Notebook flowers**: Apache 2.0
- **Data**: no explicit license, public usage for academic purposes
- **Notebook MNIST**: MIT License
- **Data**: MNIST GPL v3.0
