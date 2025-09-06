# Unsupervised Learning, Recommender Systems, and Reinforcement Learning

This repository contains Python implementations of several key machine learning algorithms, focusing on Unsupervised Learning, Recommender Systems, and Reinforcement Learning. The projects are based on exercises from the Coursera Machine Learning Specialization by DeepLearning.AI and Stanford University.

## Table of Contents
- [Overview](#overview)
- [Algorithms Implemented](#algorithms-implemented)
  - [Unsupervised Learning](#unsupervised-learning)
  - [Recommender Systems](#recommender-systems)
  - [Reinforcement Learning](#reinforcement-learning)
- [Datasets](#datasets)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Overview

This collection of Jupyter notebooks serves as a practical guide and hands-on implementation of fundamental concepts in modern machine learning. Each notebook focuses on a specific algorithm, providing a step-by-step implementation with detailed explanations of the theory and code.

## Algorithms Implemented

### Unsupervised Learning

- **K-Means Clustering:**
  - An iterative algorithm that partitions a dataset into K distinct, non-overlapping subgroups (clusters) where each data point belongs to only one group.
  - Implemented from scratch to find centroids and assign data points to the nearest cluster.
  - *File: `K_Means.ipynb`*

- **Principal Component Analysis (PCA):**
  - A dimensionality-reduction method that is often used to reduce the dimensionality of large data sets while preserving as much variance as possible.
  - Implemented to find the principal components of a dataset and project it onto a lower-dimensional space.
  - *File: `PCA.ipynb`*

### Recommender Systems

- **Collaborative Filtering:**
  - A method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).
  - Implemented to build a movie recommender system using the MovieLens dataset. The model learns user parameter vectors and movie feature vectors simultaneously to predict ratings.
  - *File: `Collaborative_Filtering_Recommender_Systems.ipynb`*

### Reinforcement Learning

- **Q-Learning:**
  - A model-free reinforcement learning algorithm to learn a quality of actions telling an agent what action to take under what circumstances.
  - Implemented for a simple grid-world environment to demonstrate how an agent can learn an optimal policy by interacting with its environment and receiving rewards.
  - *File: `Q_Learning.ipynb`*

## Datasets

- **Unsupervised Learning:** Sample 2D datasets are used for visualization and demonstration purposes.
- **Recommender Systems:** The MovieLens ml-latest-small dataset, which has been pre-processed for the exercises.

## Dependencies

The projects are implemented in Python 3. The main libraries used are:
- `numpy`
- `tensorflow`
- `matplotlib`
- `pandas`

To install the required packages, you can use pip:
```bash
pip install numpy tensorflow matplotlib pandas
```

## Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/<your-username>/Unsupervised-Learning-Recommenders-Reinforcement-Learning.git
    cd Unsupervised-Learning-Recommenders-Reinforcement-Learning
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You may need to create a `requirements.txt` file or install packages manually as listed in the Dependencies section).*

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

4.  Navigate to the desired notebook file (`.ipynb`) and run the cells to see the implementation and results.

