# PyTorch Character Language Model

A character-level language model built using PyTorch that learns name patterns from text data and generates realistic new names using embeddings and neural networks.

---

# Overview

This project demonstrates how deep learning can be used for character-level sequence modeling.

The model is trained on a dataset of names and learns how characters are related sequentially. After training, the network can generate entirely new names character-by-character.

The project is implemented from scratch using PyTorch tensors and neural network operations.

---

# Features

- Character-level language modeling
- Custom vocabulary creation
- Character embeddings
- Feedforward neural network
- Sequential next-character prediction
- Randomized name generation
- PyTorch implementation from scratch

---

# Tech Stack

- Python
- PyTorch
- Jupyter Notebook

---

# Project Structure

```text
pytorch-character-language-model/
│
├── names.txt
├── main.ipynb
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# Dataset

The model is trained using:

```text
names.txt
```

which contains thousands of names for learning character patterns.

Example dataset entries:

```text
emma
olivia
ava
isabella
sophia
```

---

# How It Works

The model:

1. Reads names from the dataset
2. Creates a character vocabulary
3. Converts characters into embeddings
4. Learns sequential character relationships
5. Predicts the next character
6. Generates new names using probability sampling

---

# Model Architecture

The project uses:

- Character Embedding Layer
- Hidden Linear Layer
- Tanh Activation
- Softmax Probability Distribution

The network predicts the next character based on previous characters in the sequence.

---

# Training

The model is trained using:

- Cross Entropy Loss
- Gradient Descent
- Backpropagation

Training loss gradually decreases as the model learns character patterns.

---

# Example Generated Names

```text
padmesin
padmesha
padmesaree
padmesh
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/pytorch-character-language-model.git
```

```bash
cd pytorch-character-language-model
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run the Project

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

---

# Requirements

Example `requirements.txt`

```txt
torch
jupyter
matplotlib
```

---

# Learning Concepts

This project helps understand:

- Character embeddings
- Neural networks
- Language modeling
- Backpropagation
- Sequence prediction
- Softmax probabilities
- PyTorch tensor operations

---

# Future Improvements

- Add LSTM architecture
- Add GRU architecture
- Add Transformer models
- Train on larger datasets
- Deploy as web application
- Generate fantasy or custom names

---

# License

MIT License

---

# Author

Padmesh B
