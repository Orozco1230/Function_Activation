Here is a well-structured `README.md` for your project in English:

markdown
# Activation Functions for Neural Networks

This repository provides implementations and visualizations of commonly used activation functions in neural networks. These functions are essential in deep learning as they introduce non-linearity to the model and help it learn complex patterns.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

Activation functions are a crucial component of neural networks, determining how neurons in a layer activate based on input. This project includes the following activation functions:

- **ReLU (Rectified Linear Unit)**: Outputs the input if positive; otherwise, outputs zero.
- **Sigmoid**: Maps input values to a range between 0 and 1, often used in binary classification.
- **Tanh (Hyperbolic Tangent)**: Maps input values to a range between -1 and 1, symmetric around zero.
- **Leaky ReLU**: A variant of ReLU that allows small gradients for negative inputs.

These functions are implemented in Python and visualized using Matplotlib.

---

## Features

- Implementations of common activation functions.
- Visualizations of activation functions to understand their behavior.
- Easy-to-use modular structure.

---

## Getting Started

### Prerequisites

Make sure you have Python installed on your system. You will also need the following libraries:

- `numpy`
- `matplotlib`

Install them using pip:

```
pip install numpy matplotlib
```

### Installation

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/LorenzoBlas/activate_functions.git
   ```

2. Navigate to the project directory:
   ```
   cd activate_functions
   ```

3. Create and activate a virtual environment (optional but recommended):
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

---

## Usage

To visualize the activation functions, run the `main.py` script:

```
python main.py
```

This will display plots of each activation function one by one.

---

## Project Structure

```
activate_functions/
│
├── srcs/
│   ├── activation_functions/
│   │   ├── relu.py          # ReLU implementation and visualization
│   │   ├── sigmoid.py       # Sigmoid implementation and visualization
│   │   ├── tanh.py          # Tanh implementation and visualization
│   │   ├── leaky_relu.py    # Leaky ReLU implementation and visualization
│   │   └── __init__.py      # Package initializer
│   └── __init__.py          # Package initializer for srcs
│
├── main.py                  # Main script to run all visualizations
└── README.md                # Project documentation (this file)
```

---

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix:
   ```
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

Please ensure your code follows best practices and is well-documented.

---
