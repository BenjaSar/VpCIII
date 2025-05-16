## Computer Vision III

### Assigments

### Assigment I

#### Embedding and positional embedding

### Assigment II

####  Vision Transformers

##### Structure

```
.
├── VisionTransformer.py    # ViT model
├── train.py                # Training loop
├── utils.py                # Visualization and evaluation
├── TP2.ipynb               # Main Jupyter notebook
├── data/                   # CIFAR-10 download path
└── README.md
```
# Vision Transformer (ViT) on CIFAR-10

This project implements a custom Vision Transformer (ViT) from scratch and trains it on the CIFAR-10 image classification dataset. It also includes tools for model evaluation and visualization.

## 🚀 Features

- Pure PyTorch implementation of a Vision Transformer
- Patch embedding using Conv2D
- Learnable positional encoding
- Multi-layer Transformer encoder
- Support for GPU acceleration (CUDA)
- Training and evaluation on CIFAR-10
- Visualization of predictions

---

## 🧠 Model Architecture

- Input Size: 32×32 RGB
- Patch Size: 4×4 or 8×8
- Embedding Dimension: 8 (customizable)
- Multi-head Self-Attention
- MLP Feed-Forward Network
- Learnable Positional Encoding
- Final MLP classifier for 10 classes (CIFAR-10)

---

## 📦 Requirements

Create and activate a conda environment:

```bash
conda create -n vit-cifar10 python=3.9 -y
conda activate vit-cifar10
