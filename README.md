# ADALINE: Logic Gate Implementation

An implementation of the **Adaptive Linear Neuron (ADALINE)** model to solve the **AND Gate** logic problem. This project demonstrates the fundamentals of Gradient Descent and the Widrow-Hoff learning rule.

## Project Description
This repository contains a Python implementation of the ADALINE neural network. Unlike a standard Perceptron, ADALINE uses a linear activation function to minimize Mean Squared Error (MSE), providing a more stable and "centered" decision boundary for linearly separable datasets.

### Key Features
* **Stochastic Gradient Descent (SGD):** Weight updates occur after every training sample.
* **Visualization:** Includes animations of the decision boundary shifting in real-time.
* **Traceability:** Detailed logging of weights, bias, and MSE per epoch.

---

## Setup Instructions

### 1. Prerequisites
Ensure you have **Python 3.8+** and **Git** installed on your machine.
* **Linux/macOS:** Usually pre-installed or available via `apt`, `pacman`, or `brew`.
* **Windows:** Download from [python.org](https://www.python.org/downloads/).

### 2. Clone the Repository
Open your terminal or command prompt and run:

```
git clone [https://github.com/Sr-RopBrian/ADALINE](https://github.com/Sr-RopBrian/ADALINE) # or git clone git@github.com:Sr-RopBrian/ADALINE.git
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