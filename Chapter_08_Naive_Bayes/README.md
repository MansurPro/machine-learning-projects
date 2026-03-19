# Chapter 08: Naive Bayes

This chapter covers the Naive Bayes algorithm, a family of simple yet effective probabilistic classifiers based on Bayes' theorem and the assumption of feature independence. Naive Bayes is commonly used for tasks such as text classification, spam detection, and more.

## Contents
- `Coding_naive_Bayes.ipynb`: A Jupyter notebook demonstrating the implementation and application of Naive Bayes classifiers.

## Overview

Naive Bayes classifiers are supervised learning algorithms that apply Bayes' theorem with the "naive" assumption that features are independent given the class label. Despite this simplification, Naive Bayes often achieves strong performance in practice.

### Key Concepts

- **Bayes' Theorem**: Updates the probability estimate for a hypothesis as new evidence is observed:
  $$
  P(y|X) = \frac{P(X|y)P(y)}{P(X)}
  $$
  where $P(y|X)$ is the posterior probability, $P(X|y)$ is the likelihood, $P(y)$ is the prior, and $P(X)$ is the evidence.
- **Naive Assumption**: Assumes all features are conditionally independent given the class label, simplifying computations.
- **Types of Naive Bayes**:
  - *Gaussian Naive Bayes*: For continuous data
  - *Multinomial Naive Bayes*: For discrete counts (e.g., text data)
  - *Bernoulli Naive Bayes*: For binary/boolean features

## Learning Objectives

- Understand the theory and mathematics behind Naive Bayes
- Implement Naive Bayes classifiers from scratch
- Apply Naive Bayes to real-world datasets
- Evaluate model performance and recognize its strengths and limitations

## How to Use

Open `Coding_naive_Bayes.ipynb` in Jupyter Notebook or VS Code to:

- Follow a step-by-step implementation of Naive Bayes
- Experiment with different types of Naive Bayes classifiers
- Apply the algorithm to sample datasets and analyze the results

## Additional Resources

- [Wikipedia: Naive Bayes Classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
- [Scikit-learn: Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [Deep Learning Book – Probabilistic Models](https://www.deeplearningbook.org/contents/prob.html)
