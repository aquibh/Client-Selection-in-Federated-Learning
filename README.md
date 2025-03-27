# Client-Selection-in-Federated-Learning (MSc Project)

**Overview**

This repository contains the implementation of various client selection strategies in Federated Learning (FL) using the Flower framework. The project was developed as part of my MSc dissertation at the University of Glasgow. It introduces and evaluates six client selection methodologies, including the baseline FedAvg and novel probabilistic approaches to improve model accuracy, communication efficiency, and fairness.

**Features**

Implementation of Federated Learning using the Flower (FLWR) framework.

Experiments conducted on **CIFAR-10** and **MNIST** datasets under IID and Non-IID distributions.

Six client selection strategies, including:

- Method 0 FedAvg (Random client selection - baseline)

- Method 1 Personalized Client Selection (Prioritizing underperforming clients)

- Method 2 Dynamic Client Selection with Accuracy Threshold

- Method 3 Performance-Based Client Selection

- Method 4 Top-K Client Selection

- Method 5 Dynamic Client Selection with K and Alpha (α)

Evaluation based on accuracy, loss, and communication rounds.
