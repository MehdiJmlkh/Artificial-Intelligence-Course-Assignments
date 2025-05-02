# Artificial Intelligence Course Assignments

### CA1: Genetic Algorithm ([Curve Fitting](https://en.wikipedia.org/wiki/Curve_fitting))

This project addresses the problem of curve fitting, where the objective is to determine the coefficients of a polynomial that best fits a set of given points. For example, consider the following points:

$$
a = [0, 1], \quad
b = [1, 0], \quad
c = [2, -5], \quad
d = [-1, -8]
$$

These points lie on the curve defined by the equation $y = 1 + 3x - 5x^2 + x^3$.

### CA2: Reinforcement Learning ([Frozen Lake](https://www.gymlibrary.dev/environments/toy_text/frozen_lake/) & [Taxi](https://gymnasium.farama.org/environments/toy_text/taxi/))

In this assignment, we explore Markov Decision Processes (MDPs) and Reinforcement Learning (RL) through two classic environments from the [Gym](https://gymnasium.farama.org/) library.

* **Part 1:** Solve the [Frozen Lake](https://www.gymlibrary.dev/environments/toy_text/frozen_lake/) environment using **Value Iteration** and **Policy Iteration**.
* **Part 2:** Apply RL techniques to the [Taxi](https://gymnasium.farama.org/environments/toy_text/taxi/) problem.

For each section, we implement the algorithms, evaluate their performance, and suggest possible enhancements.


### CA3: Hidden Markov Model (Music Genre Classification)

In this project, we apply Hidden Markov Models (HMMs) to the task of music genre classification. The dataset includes samples from four distinct genres. The process involves:

- Data Preprocessing & Feature Extraction
- Modeling using the [hmmlearn](https://hmmlearn.readthedocs.io/en/latest/) library
- Implementing HMM from scratch for a deeper understanding


### CA4: Machine Learning (Regression & Classification)

This project focuses on predicting the number of customer purchases in a market. It is divided into three phases:

- Linear Regression from Scratch
- Applying Gradient Descent for Optimization
- Using [Scikit-Learn](https://scikit-learn.org/stable/) for Efficient Modeling


### CA5: Convolutional Neural Networks (Image Classification)

In this assignment, we implement Convolutional Neural Networks (CNNs) for image classification tasks using [PyTorch](https://pytorch.org/). The focus is on:

* Understanding and configuring different layers and activation functions
* Experimenting with various hyperparameters
* Evaluating model performance on image datasets


### CA6: Clustering (Text Clustering)

This project involves clustering a text dataset consisting of news articles from [Asriran](https://www.asriran.com/). The workflow includes:

- Converting text to vector form
- Applying clustering algorithms:

   * KMeans
   * DBSCAN
- Visualizing results using PCA (Principal Component Analysis)
- Evaluating cluster quality using Homogeneity and Silhouette scores
