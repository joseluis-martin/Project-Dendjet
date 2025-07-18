# Project-Dendjet

"Dendro" (from Greek, related to trees/wood) and "Djet" (Egyptian hieroglyph meaning "eternity").

An AI tool for egyptologists to classify sarcophagus wood species using computer vision.

---

## 🏛️ About The Project

This repository contains the code and models for an Egyptology project aimed at classifying the wood species of a sarcophagus from a photograph. The goal is to create an intelligent system to support researchers by combining computer vision techniques with expert Egyptological knowledge.

The project explores and compares two main deep learning architectures:
* **Convolutional Neural Networks (CNNs)** like ResNet and EfficientNet.
* **Vision Transformers (ViTs)** like the standard ViT, DeiT, and Swin Transformer.

## ✨ Features

* Implementations of **CNN** and **ViT** models for image classification.
* Code prepared for training, validation, and testing on custom datasets.
* Jupyter Notebooks (`.ipynb`) for easy experimentation and visualization.
* Functions to evaluate model performance, including classification reports and confusion matrices.

## 🛠️ Technologies Used

* Python
* PyTorch
* Timm (for ViT models)
* Scikit-learn
* Jupyter Notebook
* Matplotlib & Seaborn

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/your_username/Project-Dendjet.git](https://github.com/your_username/Project-Dendjet.git)
    ```
2.  **Set up your data structure**
    Make sure your images are organized in the following structure within a `dataset/` folder:
    ```
    dataset/
    ├── train/
    │   ├── acacia/
    │   └── ...
    ├── val/
    └── test/
    ```
3.  **Run the notebooks**
    Open the `.ipynb` files in Jupyter Notebook or Google Colab and follow the indicated steps.
