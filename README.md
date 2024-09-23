# MNIST Digit Classification

A Tensorflow neural network model to classify digits from the MNIST dataset, reaching 97.5% accuracy on the test set.

This is my pet project to retain my ML learnings, and also figure out the setup of Jupyter Notebook projects with GitHub. 

## Model Architecture

- **Input layer**:
  - 28x28 pixel images (flattened into 1D vectors)
- **Hidden layers**:
  - Dense layer, 256 units, ReLU activation
  - Dense layer, 32 units, ReLU activation
- **Output layer**:
  - Dense layer, 10 units, softmax activation   

## Performance

- **Accuracy**: 97.5% on MNIST test set
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam, with learning rate of 0.001
- **Metrics**: Sparse Categorical Accuracy

## Dataset

The model is trained on the MNIST dataset, which consists of:
- **Training Set**: 60,000 images 
- **Test Set**: 10,000 images
