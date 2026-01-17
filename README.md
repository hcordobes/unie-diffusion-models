# Diffusion Models

## Description
This lab provides a full architecture and training example using Diffusion Models. It is developed using TensorFlow. It follows, with minor adaptations, the code presented at 

## Tasks
This example will:
* use MNIST data as training data
* define an encoding and decoding architecture using a variational scheme
* make a full training
* generate new sample data using the decoder

## Environment
This example runs within a **Google Colab T4 instance**. To open this notebook on Google Colab please use [this URL](https://colab.research.google.com/github/hcordobes/unie-vae/blob/main/src/vae.ipynb). 
As this is a private repository, Google Colab will request an OAuth2 authorization to use your credentials to access this resource on a pop-up. Grant access and the exercise should be available to you.

## Project structure

```bash
.
├── datasets/
│ └── MNIST Dataset License - GPL v3.0.txt
├── src/
│ ├── LICENSE  # MIT License
│ └── dm.ipynb  # Full exercise
├── requirements.txt
└── README.md
```

## Licenses
- **Notebook**: MIT License
- **Data**: MNIST GPL v3.0
