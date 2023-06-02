# MNIST Image Classification

This project focuses on building a neural network model to classify handwritten digits from the MNIST dataset. It consists of three main parts:

1. Model Definition: The `model.py` file contains the definition of the neural network model using PyTorch's `nn.Module` class. It defines the architecture of the network with convolutional and fully connected layers.

2. Training and Testing: The `main.py` file contains the training and testing code. It includes functions for data transformation, loading the dataset, training the model, and evaluating its performance on the test set. The training loop iterates over the dataset for a specified number of epochs and performs forward and backward propagation to optimize the model's parameters.

3. Utility Functions: The `utils.py` file includes utility functions such as `plot_dataset` for visualizing samples from the dataset, `GetCorrectPredCount` to calculate the number of correct predictions, and `plot_train` to plot the training and testing metrics.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- torchvision
- matplotlib

### Installation

1. Clone the repository:

2. Install the required dependencies:


### Usage

1. Define your desired transformations in the `transformation_config` dictionary in `main.py`. This includes specifying the data augmentation techniques for the training set and the normalization for both the training and test sets.

2. Run the main script to train and test the model:

The script will train the model on the training set, evaluate its performance on the test set, and display the training and testing metrics.



