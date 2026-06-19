Here's a more detailed and professional version suitable for a README or project description:

---

# PINV-RKS Classification

This repository implements a **nonlinear classification framework** by combining **Random Kitchen Sink (RKS) feature mapping** with the **Moore-Penrose Pseudoinverse (PINV)** learning algorithm. The approach transforms input data into a higher-dimensional feature space using random nonlinear mappings, enabling linear separation of complex decision boundaries. The output weights are then computed analytically using the Moore-Penrose pseudoinverse, eliminating the need for iterative optimization or backpropagation.

## Key Features

* **Random Kitchen Sink (RKS) Mapping**

  * Projects input data into a high-dimensional randomized feature space.
  * Approximates nonlinear kernel functions using explicit feature mappings.
  * Enables efficient nonlinear classification with reduced computational complexity.

* **Pseudoinverse (PINV) Learning**

  * Computes output weights in a single step using a closed-form solution.
  * Eliminates gradient descent, backpropagation, and learning-rate tuning.
  * Provides fast training with deterministic results.

## Datasets

The implementation is evaluated on two challenging synthetic datasets:

* **Two Spiral Dataset**

  * A benchmark dataset consisting of two interleaved spirals.
  * Tests the model's ability to learn highly nonlinear decision boundaries.

* **Checkerboard Dataset**

  * Contains alternating class regions arranged in a checkerboard pattern.
  * Evaluates the classifier's capability to separate complex spatial distributions.

## Objective

The primary objective of this project is to demonstrate that **Random Kitchen Sink feature mapping combined with Pseudoinverse learning** can effectively solve nonlinear classification problems **without using backpropagation or iterative training algorithms**. This approach offers a computationally efficient alternative to conventional neural networks while maintaining competitive classification performance.

## Workflow

1. Load the dataset.
2. Apply Random Kitchen Sink (RKS) feature mapping.
3. Compute output weights using the pseudoinverse.
4. Predict class labels for test samples.
5. Evaluate classification accuracy and visualize the decision boundary.

## Advantages

* No backpropagation required.
* Closed-form analytical training.
* Fast training and inference.
* Simple implementation.
* Suitable for nonlinear classification tasks.
* Easily scalable to larger feature dimensions.

---

