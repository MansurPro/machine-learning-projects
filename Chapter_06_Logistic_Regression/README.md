# Chapter 06: Logistic Regression

This chapter explores Logistic Regression, a widely used algorithm for binary and multiclass classification problems. Logistic Regression models the probability that a given input belongs to a particular class using the logistic (sigmoid) function.

## Contents
- `logistic_regression.ipynb`: Notebook demonstrating the implementation and theory of logistic regression.
- `Sentiment_analysis_IMDB.ipynb`: Notebook applying logistic regression to sentiment analysis on the IMDB dataset.
- `IMDB_Dataset.csv`: Dataset containing movie reviews and sentiment labels for the sentiment analysis task.

## What is Logistic Regression?
Logistic Regression is a statistical method for predicting binary outcomes from data. It estimates the probability that an instance belongs to a particular class using the sigmoid function:

$$
\sigma(z) = \frac{1}{1 + e^{-z}}
$$
where $z = w^T x + b$.

### Key Concepts
- **Sigmoid Function**: Maps any real-valued number into the (0, 1) interval, representing probability.
- **Loss Function**: Uses binary cross-entropy (log loss) for optimization.
- **Gradient Descent**: Commonly used to optimize the weights.
- **Multiclass Extension**: Can be extended to multiclass problems using one-vs-rest or softmax regression.

## Learning Objectives
- Understand the mathematical foundation of logistic regression
- Implement logistic regression from scratch
- Apply logistic regression to real-world datasets (e.g., IMDB sentiment analysis)
- Evaluate model performance using accuracy, precision, recall, and ROC curves

## Usage
Open the notebooks in this folder to:
- Learn the theory and math behind logistic regression
- Run code examples and visualize results
- Perform sentiment analysis on the IMDB dataset

## Further Reading
- [Wikipedia: Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
- [Scikit-learn: Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
- [Deep Learning Book - Logistic Regression](https://www.deeplearningbook.org/contents/ml.html)
