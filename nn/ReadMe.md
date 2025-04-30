## 📆 Modules Overview

- **abstract/**: Contains abstract base classes defining interfaces for various components, ensuring consistency across implementations.

- **activation/**: Implements activation functions such as ReLU, Sigmoid, and Tanh, essential for introducing non-linearity into neural networks.

- **dataset/**: Handles data loading and preprocessing, providing utilities to prepare datasets for training and evaluation.

- **layer/**: Defines various neural network layers, including fully connected layers, convolutional layers, and others.

- **loss/**: Implements loss functions like Mean Squared Error (MSE) and Cross-Entropy, crucial for training models by quantifying prediction errors.

- **model/**: Contains model architectures built by assembling layers and activation functions, representing complete neural networks.

- **optim/**: Provides optimization algorithms such as Stochastic Gradient Descent (SGD) and Adam, used to update model parameters during training.

- **trainer.py**: Orchestrates the training process, integrating models, datasets, loss functions, and optimizers to train neural networks effectively.

- **utilities.py**: Offers helper functions and utilities to support various tasks like logging, configuration management, and performance evaluation.
