# Conditional Variational Autoenoder on MNIST

CVAE paper: [Semi-supervised Learning with Deep Generative Models](https://proceedings.neurips.cc/paper/2014/hash/d523773c6b194f37b938d340d5d02232-Abstract.html)


## 📌 Project Overview
This project implements a **Conditional Variational Autoencoder (CVAE)** on the **MNIST dataset**. A CVAE is a probabilistic generative model that learns to reconstruct and generate images given a condition, in this case, the digit label.

The goal of this project is to demonstrate the power of **variational inference** in deep learning and how CVAEs can be used for **image generation and representation learning**.

## 🧑‍💻 Technologies Used
- Python 3.10
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

## 🏗 Project Structure

CVAE-MNIST/ │── notebooks/ │ ├── MNIST_CVAE.ipynb # Main notebook with model training and generation │── scripts/ │ ├── train.py # (Optional) Training script │ ├── generate.py # (Optional) Script for generating images │── models/ # (Optional) Trained model checkpoints │── requirements.txt # Dependencies │── README.md # Project documentation │── .gitignore # Files to ignore in GitHub

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/CarmenPastorA/CVAE-MNIST.git
   cd CVAE-MNIST
Set up the environment: Install the required dependencies:


pip install -r requirements.txt
Run the notebook: Open MNIST_CVAE.ipynb in Jupyter Notebook or Google Colab and run the cells.

## 🎯 Results

After training, the model should be able to generate new MNIST digits conditioned on the class label. Example of generated images:
<img src="https://github.com/timbmg/VAE-CVAE-MNIST/blob/master/figs/1519649452.702026/E9-Dist.png" width="400"> | <img src="https://github.com/timbmg/VAE-CVAE-MNIST/blob/master/figs/1519649461.195146/E9-Dist.png" width="400">

## 📌 Future Improvements

Improve latent space representation.
Tune hyperparameters for better image quality.
Experiment with different architectures (e.g., deeper CNN layers).