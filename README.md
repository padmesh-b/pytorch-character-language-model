# Character Level Name Generator

A character-level deep learning model built using PyTorch that learns patterns from names and generates new realistic names character-by-character.

---

# Overview

This project demonstrates how neural networks can learn sequential character patterns using embeddings and feedforward neural networks.

The model is trained on a dataset of names and predicts the next character in a sequence to generate entirely new names.

Example generated names:

```text
padmesh
padmesin
padmesha
padmesaree
```

---

# Features

- Character-level language modeling
- Custom vocabulary creation
- Character embedding layer
- Feedforward neural network
- Next-character prediction
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
character-level-name-generator/
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

# Model Architecture

The project uses:

- Character Embeddings
- Hidden Linear Layer
- Tanh Activation
- Softmax Probability Distribution

The network predicts the next character based on previous characters.

---

# Training Process

The model:

1. Reads names from dataset
2. Creates character vocabulary
3. Converts characters into embeddings
4. Trains using Cross Entropy Loss
5. Generates new names using probability sampling

---

# Example Output

```text
padmesin
padmesha
padmesaree
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/character-level-name-generator.git
```

```bash
cd character-level-name-generator
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Project

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

---

# Future Improvements

- Add LSTM architecture
- Add GRU architecture
- Train on larger datasets
- Deploy as web app
- Add temperature sampling controls
- Generate fantasy names

---

# Learning Concepts

This project helps understand:

- Character embeddings
- Neural networks
- Language modeling
- Backpropagation
- Sequence prediction
- Softmax probabilities

---

# License

MIT License

---

# Author

Padmesh B
