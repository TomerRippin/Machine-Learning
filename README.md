# Machine Learning & Deep Learning Foundations 🤖

Welcome to my portfolio of machine learning and data mining projects. This repository documents my transition from implementing core deep learning internals from scratch to deploying sophisticated predictive models for real-world datasets.

---

## 🚀 Featured Projects

### 🧠 Deep Learning Internals
* **Custom Autograd Engine & Samplers:** A "from-scratch" implementation of a scalar-valued autograd engine and custom PyTorch samplers. This project explores the mechanics of backpropagation, computational graphs, and data loading optimization.
* **Neural Network Foundations:** Implementation of multi-class Perceptron Learning Algorithms (PLA) and Softmax Regression. Features a comparative analysis of different Gradient Descent variations (**Batch, SGD, and Mini-batch**) using the Fashion-MNIST dataset.

### 🏥 Predictive Health Analytics
* **Stroke Risk Prediction:** A comprehensive data mining project involving extensive EDA, handling imbalanced datasets (using **SMOTE** and **Oversampling**), and implementing CART-based classifiers to identify high-risk profiles.
* **Diabetes Risk Classification:** End-to-end PyTorch implementation for clinical risk assessment. This project focuses on building custom `Dataset` and `DataLoader` classes while addressing critical concepts like **Data Leakage**.

### 📊 Statistical Data Mining
* **Association Rule Mining:** Implementation of the **A-priori Algorithm** to discover frequent itemsets and strong association rules, optimized for interpretability and minimal support thresholds.

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
</p>

---

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `DeepLearning_Custom_Audograd_and_Sampler_Pytorch.ipynb` | Manual backprop implementation and PyTorch Sampler logic. |
| `softmax-regression-different-gradiant-descent.ipynb` | Optimization research on Fashion-MNIST using Softmax. |
| `multi-class-PLA-for-fashion-mnist.ipynb` | Linear classification benchmarks and PLA implementation. |
| `Deep_Learning_Custom_DataLoader_Training.ipynb` | Custom PyTorch pipelines and Diabetes risk classification. |
| `DeepLearning-Basics-simple-pytorch-implementations` | Custom Tensor functions (expand_as, expand, etc...) |
| `Data-Mining-Project-Part1` | Research on imbalanced data and CART models for Stroke prediction. |
| `Data-Mining-Project-Part2` | Neural Network, Clustering and A-priori Algorithms for Stroke Prediction |

---