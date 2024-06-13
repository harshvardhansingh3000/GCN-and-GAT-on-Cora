# GCN and GAT Implementation on Cora Dataset

This repository contains implementations of Graph Convolutional Network (GCN) and Graph Attention Network (GAT) using the Cora dataset. The models are built using PyTorch and PyTorch Geometric.

## Introduction
The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication is described by a 1433-dimensional feature vector.

Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs) are types of neural networks designed to perform node classification tasks on graph-structured data.
## Results
The models are evaluated on the test set of the Cora dataset. Below are the typical results:

GCN Test Accuracy: ~80%
GAT Test Accuracy: ~80%

## References
- [PyTorch Geometric Documentation](https://pytorch-geometric.readthedocs.io/)
- [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907)
- [Graph Attention Networks](https://arxiv.org/abs/1710.10903)
