# DCGAN-Image-Generation
# 🧠 Image Generation using Deep Convolutional GAN (DCGAN)

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-DCGAN-blueviolet?style=for-the-badge" alt="DCGAN"/>
  <img src="https://img.shields.io/badge/Dataset-CIFAR--10-blue?style=for-the-badge" alt="CIFAR-10"/>
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-orange?style=for-the-badge" alt="Google Colab"/>
</p>

## 📌 Overview

This project implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate synthetic images using the CIFAR-10 dataset. The model consists of two neural networks — a Generator and a Discriminator — that compete against each other to improve the quality of generated images.

The project demonstrates the working of Generative Adversarial Networks (GANs), image generation, model training, and performance evaluation using loss curves.

## 🎯 Objectives

- Implement a Deep Convolutional Generative Adversarial Network (DCGAN).
- Train the Generator and Discriminator on an image dataset.
- Generate synthetic images using the trained Generator.
- Analyze Generator and Discriminator loss curves.
- Evaluate the visual quality of the generated images.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Platform:** Google Colab
- **Dataset:** CIFAR-10
- **Deep Learning Framework:** TensorFlow/Keras or PyTorch, depending on the implementation
- **Libraries:** NumPy, Matplotlib, and other required dependencies

## 📂 Dataset

The project uses the **CIFAR-10 dataset**, a standard image dataset containing 60,000 color images of size 32 × 32 pixels across 10 classes.

The dataset contains 50,000 training images and 10,000 test images.

🔗 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html

## 🧠 Model Architecture

DCGAN consists of two main neural networks:

### 1. Generator

- Takes a random noise vector as input.
- Uses transposed convolutional layers to generate synthetic images.
- Learns to create images that resemble samples from the training dataset.

### 2. Discriminator

- Takes real or generated images as input.
- Uses convolutional layers to distinguish real images from synthetic images.
- Provides feedback that helps the Generator improve.

### ⚙️ Training Process

1. Load and preprocess the CIFAR-10 dataset.
2. Initialize the Generator and Discriminator.
3. Train the Discriminator to distinguish real and generated images.
4. Train the Generator to produce realistic images that can fool the Discriminator.
5. Record and visualize the loss values.
6. Generate and inspect synthetic images after training.

## 📊 Performance Evaluation

The model is evaluated using:

- **Generator Loss:** Indicates how well the Generator performs against the Discriminator.
- **Discriminator Loss:** Indicates how well the Discriminator distinguishes real images from generated images.
- **Generated Image Quality:** Visual inspection of synthetic images produced by the trained model.

## 📓 Project Notebook

The complete implementation is available in:

📄 `GAN_CIFAR10.ipynb`

Open the notebook using Google Colab to execute the code, train the model, and view the generated outputs.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `GAN_CIFAR10.ipynb` in Google Colab.
3. Install any missing dependencies, if required.
4. Run the notebook cells in sequence.
5. Train the DCGAN model.
6. Observe the generated images and loss curves.

## 📈 Results

After training, the model generates synthetic images based on patterns learned from the CIFAR-10 dataset.

Add the following outputs here after running the notebook:

- Generated synthetic image samples.
- Generator loss curve.
- Discriminator loss curve.

## 🎓 Learning Outcomes

- Understanding the fundamentals of Generative Adversarial Networks.
- Learning the role of Generator and Discriminator networks.
- Implementing convolutional neural networks for image generation.
- Analyzing model training through loss curves.
- Understanding the challenges involved in generating realistic images.

## 🏁 Conclusion

This practical demonstrates the implementation and training of a DCGAN for synthetic image generation. It provides practical insight into adversarial training, convolutional neural networks, and the evaluation of generated images.

---

<p align="center">
  <b>Practical No. 04 | Image Generation using DCGAN</b>
  <br/>
  Deep Learning Laboratory
</p>
