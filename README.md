# Neural Network From Scratch for MNIST

A fully connected neural network built from scratch using only mathematics and NumPy to classify handwritten digits from the MNIST dataset.

This project does not use TensorFlow, PyTorch, Keras, or any other machine learning framework. Every component of the network, including forward propagation, backpropagation, gradient descent, and parameter updates, is implemented manually to provide a deeper understanding of how neural networks learn.

---

## Features

* Neural network implemented entirely from scratch
* Manual forward propagation
* Manual backpropagation
* Gradient descent optimization
* ReLU activation function
* Softmax output layer
* Cross entropy loss
* Matrix based implementation using NumPy
* MNIST handwritten digit classification

---

## Project Structure

```text
.
├── nn-from-scratch.ipynb
└── README.md
```

---

## Neural Network Architecture

```text
Input Layer (784)
        │
        ▼
Hidden Layer
        │
      ReLU
        │
        ▼
Output Layer (10)
        │
     Softmax
        │
        ▼
 Predicted Digit
```

---

## Concepts Covered

This notebook demonstrates the complete implementation of a feed forward neural network using only linear algebra and calculus.

Topics include:

* Data preprocessing
* Weight and bias initialization
* Forward propagation
* ReLU activation
* Softmax activation
* Cross entropy loss
* Backpropagation
* Gradient descent
* Model evaluation
* Prediction on handwritten digits


## Results

The model learns to recognize handwritten digits by iteratively updating its weights through backpropagation and gradient descent.

The notebook includes:

* Training accuracy
* Loss during training
* Sample predictions
* Visualization of handwritten digits with predicted labels

---

## Mathematical Concepts

The implementation covers the mathematics behind neural networks, including:

* Matrix multiplication
* Linear transformations
* ReLU activation
* Softmax activation
* Cross entropy loss
* Chain rule
* Partial derivatives
* Gradient descent
* Parameter optimization

No automatic differentiation or deep learning frameworks are used.

---

## Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Purpose

Machine learning frameworks simplify building neural networks but often hide the mathematics behind them. This project focuses on implementing every step manually to understand how neural networks learn from data.

It serves as an educational resource for students and developers who want to build a strong foundation in deep learning by implementing the core algorithms themselves.

---

## License

This project is licensed under the MIT License.
