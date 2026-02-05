# Chapter 11: Support Vector Machines (SVM)

This chapter explores Support Vector Machines (SVM), a powerful and versatile supervised learning algorithm used for classification and regression tasks. SVMs are known for their ability to find optimal decision boundaries and work well with both linear and non-linear data.

## Contents
- `Building_the_datasets_for_SVM.ipynb`: Demonstrates how to create and visualize datasets for SVM experiments.
- `Calculating_similarities_SVM.ipynb`: Explains and visualizes kernel functions and similarity calculations.
- `SVM_graphical_example.ipynb`: Step-by-step, visual demonstration of SVM concepts, including margin, support vectors, and decision boundaries.
- `linear.csv`, `one_circle.csv`, `two_circles.csv`, `two_circles_zapata.csv`: Example datasets for SVM experiments and visualizations.

## What are Support Vector Machines?
Support Vector Machines are supervised learning models that find the hyperplane which best separates data into classes. SVMs maximize the margin between classes and can use kernel tricks to handle non-linear data.

### Key Concepts & Visuals
- **Optimal Hyperplane**: SVM finds the line (in 2D) or hyperplane (in higher dimensions) that maximizes the margin between classes.
  
  ![SVM Margin](https://upload.wikimedia.org/wikipedia/commons/2/2a/SVM_margin.png)
- **Support Vectors**: The data points closest to the hyperplane; these determine the position and orientation of the boundary.
- **Margin**: The distance between the hyperplane and the nearest data points from each class. SVM aims to maximize this margin.
- **Kernel Trick**: SVM can use kernel functions (e.g., polynomial, RBF) to project data into higher dimensions, making it possible to separate non-linearly separable data.
  
  ![Kernel Trick](https://upload.wikimedia.org/wikipedia/commons/6/63/Kernel_Machine.svg)
- **Visualizing Boundaries**: Notebooks include plots showing how SVM separates different datasets, including circles and complex shapes.

## Learning Objectives
- Understand the theory and mathematics behind SVMs
- Visualize margins, support vectors, and decision boundaries
- Experiment with different kernels and datasets
- Apply SVMs to real-world and synthetic data
- Interpret SVM results and visualize the impact of parameters

## Usage
Open the notebooks in this folder to:
- Build and visualize datasets for SVM experiments
- See graphical explanations of SVM concepts
- Experiment with kernel functions and observe their effects
- Apply SVMs to various datasets and visualize the results

## Further Reading & Visual Resources
- [Wikipedia: Support Vector Machine](https://en.wikipedia.org/wiki/Support_vector_machine)
- [Scikit-learn: SVM](https://scikit-learn.org/stable/modules/svm.html)
- [StatQuest: SVM (YouTube)](https://www.youtube.com/watch?v=efR1C6CvhmE)
- [3Blue1Brown: SVM Visual Intuition (YouTube)](https://www.youtube.com/watch?v=5RRLv6aT3hE)

---

> **Tip:** For the best learning experience, run the notebooks and interact with the visualizations. Many cells include plots and diagrams to help you understand how SVMs work internally and how kernels transform data.
