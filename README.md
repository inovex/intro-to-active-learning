# Intro to Active Learning

Example code accompanying the blog post [Intro to Active Learning](https://www.inovex.de/blog/intro-to-active-learning/).

This notebook contains implementations of:

* Uncertainty Sampling with
  - least confidence
  - minimum margin
  - entropy criterion

* Query-by-Committee with
  - vote entropy
  - consensus entropy
  - maximum disagreement

* Expected Model Change for gradient-based learning
  - including a simple polynomial classification model

* Density weighting with KDEs

## How to run

You can run this notebook in Jupyter Notebook (or Jupyter Lab), provided you have
the following dependencies installed:

- numpy
- scipy
- matplotlib
- scikit-learn
- seaborn
- jax (only needed for expected model change)


You can also import this into a [Colab](https://colab.research.google.com), which comes with all these already installed.
