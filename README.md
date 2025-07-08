# NeuralNetwork-from-Scratch
# 🧠 Neural Network from Scratch — With Full Math Intuition

This repository contains a **from-scratch implementation of a fully connected neural network**, built using only **Python and NumPy** — no PyTorch, TensorFlow, or external ML libraries. Every line of code is backed by **hand-derived math**, making this a great educational project for anyone diving into deep learning.

---

## 🚧 Why I Built This

Before diving into libraries like PyTorch or TensorFlow, I wanted to understand what’s **under the hood** — how neural networks actually work, how gradients flow, and how backpropagation updates happen step by step.

This repo represents my journey from **"just using libraries"** to **"building the machinery myself"**.

---

## 🔍 Features

- ✅ Manual forward propagation  
- ✅ Hand-coded backpropagation (no autograd!)  
- ✅ Fully vectorized implementation using NumPy  
- ✅ Support for any number of layers  
- ✅ Binary classification demo task  
- ✅ Full mathematical derivation of:
  - Linear transformations (`Z = W·X + b`)
  - Activation functions (Sigmoid, ReLU)
  - Loss functions (MSE, Binary Cross-Entropy)
  - Gradient Descent updates
- ✅ Jupyter Notebook with visual + math walkthrough

---

## 🧮 Math Included

This isn't just code — it includes **step-by-step derivations** of:

- 🟡 Chain rule for backpropagation  
- 🟢 Partial derivatives w.r.t. weights and biases  
- 🔵 Activation gradients  
- 🟠 Loss gradients  
- 🟣 Update rules: `θ = θ - α ∇L(θ)`

These are explained clearly in the [Jupyter Notebook](./notebook.ipynb) and markdown cells.

---
