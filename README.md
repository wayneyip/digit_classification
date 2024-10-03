# MNIST Digit Classification

A Tensorflow neural network model to classify digits from the MNIST dataset, reaching 99.4% accuracy on the test set.

I started this project to do hands-on experimentation with my theoretical learnings, and also to give myself a gentle introduction to CNNs.    

## Model Architecture

- **Input layer**:
  - 28x28 pixel images 
- **Hidden layers**:
  - 2D convolutional layer, 32 filters, size 5x5, ReLU activation
  - 2D convolutional layer, 64 filters, size 5x5, ReLU activation
  - 2D convolutional layer, 64 filters, size 3x3, ReLU activation
- **Output layer**:
  - Dense layer, 10 units, softmax activation   

## Performance

- **Accuracy**: 99.4% on MNIST test set
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam, learning rate 0.001
- **Metrics**: Sparse Categorical Accuracy

## Dataset

The model is trained on the MNIST dataset, which consists of:
- **Training Set**: 60,000 images 
- **Test Set**: 10,000 images
