# Image-Classification-with-QNN


# 🧠 Image Classification with Quantum Neural Networks (QNN)

This repository demonstrates hybrid **classical–quantum** approaches for image classification, built in Python using PyTorch and Qiskit. It includes two Jupyter notebooks exploring convolutional neural networks (CNNs), quantum neural networks (QNNs), and a simple quantum circuit simulator.

---

## 📂 Repository Contents


---

## 🧩 Notebooks Overview

### 1. **Image Classification with qSLP.ipynb**
- Implements a hybrid neural network with **quantum single-layer perceptron (qSLP)**
- Uses MNIST (or FashionMNIST) samples
- Demonstrates data encoding into qubits, parameterized quantum layers, measurement, and a final classical output layer
- Showcases training, accuracy/loss plots, and comparison with baseline performance

### 2. **quantum_circuit_simulator.py**
- Simulates parameterized quantum circuits
- Includes functions for qubit initialization, gate operations, and expectation-value measurements
- Used by notebook demos and QNN implementation

### 3. **quantum_circuit_examples.ipynb**
- Walks through circuit construction and measurement using the simulator
- Helps users understand quantum circuit behavior prior to integration into QNN

---

## 🛠️ Requirements

Install the core dependencies:

```bash
pip install torch torchvision qiskit qiskit-machine-learning numpy matplotlib

