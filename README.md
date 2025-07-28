# 🧠 GAN (Generative Adversarial Network) – Deep Learning Project

This project implements a Generative Adversarial Network (GAN) using TensorFlow to generate synthetic images by learning the distribution of a real image dataset. It includes building and training custom Generator and Discriminator models from scratch, and visualizing the generated outputs over time.

---

## 📌 Project Overview

Generative Adversarial Networks (GANs) are one of the most exciting advancements in deep learning. They consist of two neural networks:
- **Generator:** Creates fake images from random noise.
- **Discriminator:** Distinguishes real images from generated (fake) ones.

Both models are trained together in a minimax game, where the generator improves to fool the discriminator and the discriminator improves to detect fakes.

---

## 🔍 Features

- Loads image data using `tensorflow_datasets`
- Preprocesses and normalizes images for training
- Builds a custom Generator and Discriminator using `tf.keras`
- Trains GAN using adversarial loss
- Visualizes training progress using `matplotlib` and `ipywidgets`
- Saves generated images during training

---

## 🛠️ Tech Stack / Libraries

- Python
- TensorFlow / Keras
- TensorFlow Datasets (TFDS)
- Matplotlib
- ipywidgets

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gan-deep-learning.git
cd gan-deep-learning
