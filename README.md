# 🧠 Image Classification with Quantum Neural Networks (QNN)

This repository demonstrates hybrid **classical–quantum** approaches for image classification, built in Python using Qiskit. It includes a Jupyter notebook exploring quantum neural networks (QNNs), and quantum circuit simulations.

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
pip install -r requirements.txt   
```

---

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/amacaluso/Image-Classification-with-QNN.git
```

2. **Run and explore notebooks:**

- Launch Jupyter: `jupyter notebook`
- Open and run `Image Classification with qSLP.ipynb` to train and evaluate hybrid QNN models


---

## 🔬 What You’ll Learn

- **Quantum data encoding & hybrid training pipeline**: blending quantum circuit outputs with classical layers
- **Quantum circuit simulation and measurement**: expectation-value computation without requiring actual quantum hardware

---

## 📈 Results Summary

- qSLP-based hybrid QNN achieves **competitive accuracy** on binary MNIST tasks
- Visualization of **training/validation curves** highlights convergence behavior

---


## 📄 Licensing

This project is available under the **Apache 2.0**—see `LICENSE` for details.

---

## 📫 Contact

Questions or feature requests? Feel free to open issues or reach out to the repo owner!
