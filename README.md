# MNIST Handwritten Digit Classification using TensorFlow & Keras 🔢🧠

This repository features a Deep Learning computer vision project focused on multi-class image classification. Built using **TensorFlow** and **Keras**, the model flattens and processes 28x28 grayscale pixel matrices to accurately identify handwritten digits from 0 to 9.

## 📌 Project Overview
The MNIST dataset is the definitive benchmark for computer vision systems. This project maps handwritten numerical pixels to their respective class targets. By skipping traditional computer vision models, this workflow maps spatial pixel data into an automated Multilayer Perceptron (MLP/ANN) infrastructure to execute discrete probability distributions across 10 label indicators.

## 🛠️ Tech Stack & Tools
- **Frameworks:** TensorFlow 🔥 | Keras
- **Programming Languages:** Python
- **Data Engineering & Visualization:** NumPy, Pandas, Matplotlib, Seaborn
- **Environment:** Google Colab / Kaggle Notebooks

## ⚙️ Model Architecture & Pipeline
- **Image Preprocessing:** Handled 2D dimensional structural scaling (normalizing pixel values from [0-255] to [0-1]) for high-performance weight stabilization.
- **Topology:** Multi-layered Dense Network using `nn.Flatten()` to transform the 28x28 spatial matrices into 784-dimensional flat vectors, followed by hidden layers utilizing `ReLU` activations.
- **Output Setup:** A 10-node final classification layer paired with a `Softmax` execution function to evaluate multi-class distribution probabilities.
- **Optimization Stack:** Configured utilizing the `Adam` optimizer optimizer and supervised tracking via Sparse Categorical Cross-Entropy (`sparse_categorical_crossentropy`) loss functions.

## 📁 Project Structure
```text
├── mnist_classification_ANN-keras.ipynb  # Core image processing and ANN classifier notebook
└── README.md                             # Comprehensive project layout documentation
```

---
*Feel free to explore the notebook and star ⭐ this repository if you find it helpful!*

