# Face Generation Using GAN

**Implementing a Deep Convolutional Generative Adversarial Network (DCGAN) to Generate Synthetic Faces**

This project focuses on building a Deep Convolutional Generative Adversarial Network (DCGAN) to generate realistic images of human faces. The model is trained on the CelebA dataset, which contains over 200,000 celebrity images labeled with 40 attribute labels.

---

## Project Overview

- **Objective**: Develop a DCGAN model to generate synthetic faces that resemble real human faces.
- **Dataset**: Utilizes the CelebA dataset, a large-scale face attributes dataset with over 200,000 celebrity images.
- **Framework**: Built using PyTorch for model development and training.

---

## Repository Structure

- **DCGAN-Training-Solution.ipynb** — Jupyter notebook for building and training the DCGAN model.
- **dlnd_face_generation_starter.ipynb** — Starter notebook for setting up the environment and initial configurations.
- **requirements.txt** — File containing the necessary Python packages for the project.
- **tests.py** — Script for testing the trained model and generating synthetic images.
- **train_samples.pkl** — Pickle file containing sample training data.
- **README.md** — This file.

---

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

`pip install -r requirements.txt`

---

## Running the Notebooks

1. Clone the repository:
   
   `git clone https://github.com/hamidghasemi69/Face-Generation-Using-GAN.git`
   `cd Face-Generation-Using-GAN`

2. Open the Jupyter notebooks:
   
   `jupyter notebook`

3. Follow the instructions in the notebooks to build, train, and evaluate the DCGAN model.

---

## Results

The trained model generates synthetic images of human faces that closely resemble real photographs. Sample outputs can be found in the train_samples.pkl file.

# Face-Generation-Using-GAN
Building a Deep Convolutional Generative Adversarial Network) to Generate Fake Image from Real Celebrity Images.

# Project Overview: Implementing a Face Generation Neural Network Using DCGAN
In this project, I implemented a Deep Convolutional Generative Adversarial Network (DCGAN) using the CelebFaces Attributes dataset (CelebA). The goal of this project was to train a generator network capable of producing realistic images of faces. To achieve this, I defined and trained a DCGAN architecture. For those interested in the underlying architecture, the details can be found in the [DCGAN paper](https://arxiv.org/pdf/1511.06434.pdf). Below are examples of the generated images, along with the corresponding generator and discriminator losses.


* Sixteen generated faces
<img width="589" alt="gan_out" src="https://github.com/hamidghasemi69/Face-Generation-Using-GAN/assets/22797186/b9254beb-d212-40f6-982f-f729f1f5b6bd">



* Loss
<img width="281" alt="gan_loss" src="https://github.com/hamidghasemi69/Face-Generation-Using-GAN/assets/22797186/cd00a153-0fe5-4d21-9c64-22f5d560daf8">


---

## Acknowledgements

- `CelebA Dataset`: A large-scale face attributes dataset used for training the model.

- `PyTorch`: An open-source machine learning library used for building and training the DCGAN model.


---

## Contact & Contributions

- Author: `Hamid Ghasemi`

- Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.



