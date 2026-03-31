# ADALINE: Logic Gates & Biological Classification

An implementation of the **Adaptive Linear Neuron (ADALINE)** model to solve diverse binary classification problems. This project explores the **Widrow-Hoff (Delta)** learning rule through two distinct lenses: Boolean logic and simulated biological data.

## Project Structure

This repository contains two primary notebooks:

1. **`ADALINE_AND.ipynb`**: Implements the classic **AND Gate**. This demonstrates how ADALINE finds a decision boundary for rigid, perfectly separable logical inputs.
2. **`ADALINE.ipynb`**: Applies ADALINE to a **Bird Species Dataset**. This involves a simulated classification task -distinguishing between two bird species based on features like wing span and weight - showcasing the model's performance on "natural" data.


An implementation of the **Adaptive Linear Neuron (ADALINE)** model to solve the **AND Gate** logic problem. This project demonstrates the fundamentals of Gradient Descent and the Widrow-Hoff learning rule.

## Project Description
This repository contains a Python implementation of the ADALINE neural network. Unlike a standard Perceptron, ADALINE uses a linear activation function to minimize Mean Squared Error (MSE), providing a more stable and "centered" decision boundary for linearly separable datasets.

### Key Features
* **Dual Optimization Algorithms:** Implements both **Stochastic Gradient Descent (SGD)** (updating weights per sample) and **Batch Gradient Descent (BGD)** (updating weights per epoch) for direct comparison.
* **Comparative Convergence Analysis:** Tracks and plots the Mean Squared Error (MSE) trajectories side-by-side to illustrate the stability of Batch versus the speed of Incremental learning.
* **Dynamic Visualization:** Includes `matplotlib` animations showing the real-time geometric shift of the decision boundaries, highlighting SGD against BGD.
* **Detailed Traceability:** Comprehensive `pandas` DataFrames logging the exact state of weights, bias, and continuous error at every step of the training process.
  
---

## Setup Instructions

### 1. Prerequisites
Ensure you have **Python 3.8+** and **Git** installed on your machine.
* **Linux/macOS:** Usually pre-installed or available via `apt`, `pacman`, or `brew`.
* **Windows:** Download from [python.org](https://www.python.org/downloads/).

### 2. Clone the Repository
Open your terminal or command prompt and run:

```
git clone https://github.com/Sr-RopBrian/ADALINE # or git clone git@github.com:Sr-RopBrian/ADALINE.git
cd ADALINE
```

### 3. Environment Setup

Create an isolated virtual environment to avoid dependency conflicts.
**On Linux/macOS:**
```
python3 -m venv .venv
source .venv/bin/activate
```

**On Windows::**
```
python -m venv .venv
.venv\Scripts\activate
```

### 4. Install Dependencies
Once the environment is active, install the required libraries:
```
pip install -r requirements.txt
```

### 5. Running the Project

This project is designed to run in a Jupyter Notebook environment.

1. Launch your preferred editor (VS Code, Code-OSS, or PyCharm).

2. If using VS Code / Code-OSS:

    - Open ADALINE.ipynb or ADALINE_AND.ipynb
    - When prompted, select the Python interpreter located in the .venv folder.

3. Alternatively, launch Jupyter Lab directly:
```
jupyter lab
```
