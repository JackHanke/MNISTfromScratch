# Neural Networks from Scratch
This repo consists of academic exercises to create all facets of the following neural network architectures from scratch.
- A multilayer perceptron, including
    - Regularization
    - Dropout
- A convolutional neural network

Here scratch means just using Python and NumPy. 

Implementations will be benchmarked on both the classical [MNIST](https://www.tensorflow.org/datasets/catalog/mnist) and [Iris](https://archive.ics.uci.edu/dataset/53/iris) data sets.

## Best Results Achieved

| Model Type | Arch | Regularization | Dropout | Epoch| Lr | Dataset | Acc |
|-|-|-|-|-|-|-|-|
| Ann | (784,) | L2 | 0 | 0 | 0 | MNIST | 0 |
| Ann | (4,) | L2 | 0 | 0 | 0 | Iris | 0 |

## Resources
- [Introduction to Deep Learning](http://neuralnetworksanddeeplearning.com/) by Michael Nielsen

## Project TODOs
- Implement model save and load feature
- Debug CrossEntropy class
- Add dropout
- Add CNN
- Implement Adam Optimizer