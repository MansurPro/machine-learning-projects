# Chapter 08: Naive Bayes

This chapter introduces the Naive Bayes algorithm, a family of simple yet powerful probabilistic classifiers based on Bayes' theorem with the assumption of feature independence. Naive Bayes is widely used for text classification, spam detection, and many other applications.

## Contents
- `Coding_naive_Bayes.ipynb`: Jupyter notebook demonstrating the implementation and application of the Naive Bayes algorithm.

## What is Naive Bayes?
Naive Bayes classifiers are a group of supervised learning algorithms based on applying Bayes' theorem with a strong (naive) assumption that features are independent given the class label. Despite this simplification, Naive Bayes often performs surprisingly well in practice.

### Key Concepts
- **Bayes' Theorem**: Provides a way to update the probability estimate for a hypothesis as more evidence is available:
  $$
  P(y|X) = \frac{P(X|y)P(y)}{P(X)}
  $$
  where $P(y|X)$ is the posterior probability, $P(X|y)$ is the likelihood, $P(y)$ is the prior, and $P(X)$ is the evidence.
- **Naive Assumption**: Assumes all features are independent given the class label, which simplifies computation.
- **Types of Naive Bayes**:
  - Gaussian Naive Bayes (for continuous data)
  - Multinomial Naive Bayes (for discrete counts, e.g., text)
  - Bernoulli Naive Bayes (for binary/boolean features)

## Learning Objectives
- Understand the theory and mathematics behind Naive Bayes
- Implement Naive Bayes classifiers from scratch
- Apply Naive Bayes to real-world datasets
- Evaluate model performance and understand its strengths and limitations

## Usage
Open `Coding_naive_Bayes.ipynb` in Jupyter Notebook or VS Code to:
- Learn the step-by-step implementation of Naive Bayes
- Experiment with different types of Naive Bayes classifiers
- Apply the algorithm to sample datasets and analyze results

## Further Reading
- [Wikipedia: Naive Bayes Classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
- [Scikit-learn: Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [Deep Learning Book - Probabilistic Models](https://www.deeplearningbook.org/contents/prob.html)
