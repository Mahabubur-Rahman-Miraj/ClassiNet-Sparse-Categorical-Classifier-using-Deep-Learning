# ClassiNet: Sparse Categorical Classifier using Deep Learning

ClassiNet is a deep learning-based classification project designed to categorize data into multiple classes using a feed-forward neural network architecture. The model is built using TensorFlow/Keras and employs Sparse Categorical Cross-Entropy as its loss function, making it ideal for multi-class classification tasks.

## Features
- Multi-class classification using a feed-forward neural network.
- Uses the Adam optimizer for efficient model training.
- Includes ReLU activation for hidden layers and Softmax for the output layer.
- Tracks accuracy during training and evaluates performance on test data.

## Model Architecture
1. **Input Layer**: Dense layer with 12 units and ReLU activation.
2. **Hidden Layer**: Dense layer with 8 units and ReLU activation.
3. **Output Layer**: Dense layer with 10 units (number of classes) and Softmax activation.

## Loss Function
The project uses `SparseCategoricalCrossentropy`, which is suitable for multi-class classification when labels are provided as integers.

## Optimizer
- **Adam Optimizer**: The model is trained using the Adam optimizer with a learning rate of 0.01, which ensures efficient gradient-based optimization.

## Data
The model is designed to be trained on labeled multi-class data. You will need to supply `X_train`, `y_train`, `X_test`, and `y_test` datasets.

## Installation and Setup

### Prerequisites
- Python 3.7 or above
- TensorFlow
- Keras
- NumPy

### Install the required dependencies:

```bash
pip install tensorflow keras numpy
