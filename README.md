# 🧠 Image Classification with Quantum Neural Networks (QNN)

This repository demonstrates hybrid **classical–quantum** approaches for image classification, built in Python using PyTorch and Qiskit. It includes two Jupyter notebooks exploring convolutional neural networks (CNNs), quantum neural networks (QNNs), and a simple quantum circuit simulator.

---

## 📂 Repository Contents

```
.
├── Image Classification with qSLP.ipynb          # Hybrid QNN using qSLP (quantum single-layer perceptron)
├── quantum_circuit_simulator.py                 # Lightweight simulator for parameterized quantum circuits
├── quantum_circuit_examples.ipynb               # Demo notebook for the simulator
└── README.md                                    # (This file)
```

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
```

*(Optional)* If you plan to use a real IBM quantum backend via Qiskit, also install:

```bash
pip install qiskit-ibm-provider
```

---

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/amacaluso/Image-Classification-with-QNN.git
cd Image-Classification-with-QNN
```

2. **Run and explore notebooks:**

- Launch Jupyter: `jupyter notebook`
- Open and run `Image Classification with qSLP.ipynb` to train and evaluate hybrid QNN models
- Optionally run `quantum_circuit_examples.ipynb` for circuit-level demonstrations

3. **Adjust experiments:**

- Tune the number of qubits, layers, and epoch count
- Swap datasets between MNIST and FashionMNIST
- Optionally replace the simulator with Qiskit backends to test on real quantum hardware

---

## 🔬 What You’ll Learn

- **Quantum data encoding & hybrid training pipeline**: blending quantum circuit outputs with classical layers
- **Qiskit–PyTorch integration**: defining parameterized quantum modules within classical frameworks
- **Quantum circuit simulation and measurement**: expectation-value computation without requiring actual quantum hardware
- **Performance comparison**: observe how hybrid quantum models compare with purely classical CNNs

---

## 📈 Results Summary

- qSLP-based hybrid QNN achieves **competitive accuracy** on binary MNIST tasks
- Visualization of **training/validation curves** highlights convergence behavior
- Circuit simulator provides insights into how qubit encoding affects classification

---

## ⚙️ Customization Ideas

- Apply QNN to FashionMNIST or binary subsets of MNIST
- Adjust qubit dimension and circuit depth
- Swap classical MLP head with deeper architectures
- Test on NISQ devices using Qiskit runtime

---

## 🙌 Acknowledgments

- Circuit simulator inspired by foundational QML work (Qiskit Machine Learning tutorials)
- Thanks to the Qiskit community and PyTorch ecosystem for open-source tools and guidance

---

## 📄 Licensing

This project is available under the **MIT License**—see `LICENSE` for details.

---

## 📫 Contact

Questions or feature requests? Feel free to open issues or reach out to the repo owner!
