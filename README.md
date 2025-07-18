# Project-Dendjet
An AI tool for egyptologists to classify sarcophagus wood species using computer vision.

---

## 🏛️ Sobre el Proyecto

Este repositorio contiene el código y los modelos desarrollados para un proyecto de egiptología que busca clasificar la especie de madera de un sarcófago a partir de una fotografía. El objetivo es crear un sistema inteligente que sirva como herramienta de apoyo para investigadores, combinando técnicas de visión por computador con el conocimiento experto de la egiptología.

El proyecto explora y compara dos arquitecturas principales de deep learning:
* **Redes Neuronales Convolucionales (CNN)** como ResNet y EfficientNet.
* **Vision Transformers (ViT)** como el ViT estándar, DeiT y Swin Transformer.

## ✨ Características

* Implementaciones de modelos **CNN** y **ViT** para clasificación de imágenes.
* Código preparado para entrenamiento, validación y prueba sobre datasets personalizados.
* Notebooks de Jupyter (`.ipynb`) para una fácil experimentación y visualización.
* Funciones para evaluar el rendimiento del modelo, incluyendo reportes de clasificación y matrices de confusión.

## 🛠️ Tecnologías Utilizadas

* Python
* PyTorch
* Timm (para los modelos ViT)
* Scikit-learn
* Jupyter Notebook
* Matplotlib & Seaborn

## 🚀 Cómo Empezar

Para poner en marcha una copia local del proyecto, sigue estos pasos.

1.  **Clona el repositorio**
    ```sh
    git clone [https://github.com/tu_usuario/Project-Dendjet.git](https://github.com/tu_usuario/Project-Dendjet.git)
    ```
2.  **Crea tu estructura de datos**
    Asegúrate de tener tus imágenes organizadas en la siguiente estructura dentro de una carpeta `dataset/`:
    ```
    dataset/
    ├── train/
    │   ├── acacia/
    │   └── ...
    ├── val/
    └── test/
    ```
3.  **Abre los notebooks**
    Ejecuta los archivos `.ipynb` en Jupyter Notebook o Google Colab y sigue los pasos indicados.
