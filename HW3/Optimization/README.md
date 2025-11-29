# Optimization Techniques 📘

## Overview
This module contains two complementary notebooks that explore optimization methods used in training neural networks.  
The first notebook focuses on **implementing popular optimizers from scratch**, while the second demonstrates how these optimizers behave when **training a neural network on the MNIST dataset**.  
Together, they provide a complete, practical understanding of gradient-based optimization.

---

## Workflow

### 1️⃣ Implementing Optimizers From Scratch  
(Notebook: `Optimization_Algorithms.ipynb`)
1. Load required libraries and set up the computation environment  
2. Review the role of optimization in machine learning  
3. Implement core optimizers manually:
   - Stochastic Gradient Descent (SGD)
   - SGD with Momentum  
   - RMSProp  
   - Adagrad  
   - Adam  
4. Test each optimizer using dummy gradients  
5. Compare weight-update behaviors across optimizers  
6. Analyze intuition behind momentum, adaptivity, and learning-rate dynamics  

---

### 2️⃣ Applying Optimizers to MNIST  
(Notebook: `Optimization_MNIST.ipynb`)
1. Load and preprocess the MNIST dataset  
2. Build a simple fully connected neural network **from scratch**  
   - Weight initialization  
   - Activation functions  
   - Forward propagation  
   - Cross-entropy loss  
3. Implement backpropagation manually  
4. Train the model with different optimizers:
   - SGD  
   - Momentum  
   - RMSProp  
   - Adagrad  
   - Adam  
5. Plot and compare:
   - Training/validation loss curves  
   - Accuracy across optimizers  
6. Discuss convergence speed and generalization differences  

---

## Key Concepts
- Gradient-based optimization  
- Learning-rate scheduling  
- Momentum and adaptive methods  
- Manual implementation of optimizers  
- Neural network training from scratch  
- MNIST classification  
- Behavior and trade-offs of different optimizers  
