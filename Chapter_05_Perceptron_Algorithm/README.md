# Chapter 05: Perceptron Algorithm

This chapter covers the Perceptron Algorithm, a fundamental building block in machine learning for binary classification tasks. The Perceptron is a type of linear classifier and one of the simplest forms of a feedforward neural network.

## Contents
- `perceptron_algorithm.ipynb`: Jupyter notebook demonstrating the implementation and working of the Perceptron algorithm.

## What is the Perceptron Algorithm?
The Perceptron algorithm is an iterative algorithm for supervised learning of binary classifiers. It updates its weights based on misclassified examples and aims to find a linear decision boundary that separates two classes.

### Key Concepts
- **Linear Separability**: The Perceptron works best when the data is linearly separable.
- **Weight Update Rule**: The weights are updated as follows:
  $$
  w = w + \eta (y - \hat{y})x
  $$
  where $w$ is the weight vector, $\eta$ is the learning rate, $y$ is the true label, $\hat{y}$ is the predicted label, and $x$ is the input vector.
- **Activation Function**: Typically a step function that outputs 1 if the weighted sum is above a threshold, otherwise 0.

## Learning Objectives
- Understand the theory behind the Perceptron algorithm
- Implement the Perceptron from scratch
- Visualize the decision boundary
- Experiment with different datasets

## Usage
Open `perceptron_algorithm.ipynb` in Jupyter Notebook or VS Code to:
- Run the Perceptron algorithm on sample datasets
- Visualize the learning process and decision boundaries
- Modify parameters such as learning rate and number of epochs

## Further Reading
- [Wikipedia: Perceptron](https://en.wikipedia.org/wiki/Perceptron)
- [Deep Learning Book - Perceptron](https://www.deeplearningbook.org/contents/ml.html)
