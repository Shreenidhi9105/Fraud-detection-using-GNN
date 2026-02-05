
# Fraud Detection using Graph Neural Networks

This repository implements a Graph Neural Network (GNN) based approach
for detecting fraudulent transactions in financial data.

## 📌 Why Graph Neural Networks for Fraud Detection?

Fraud detection problems are inherently **relational**:
- Accounts interact with multiple other accounts
- Fraud often occurs in coordinated patterns, not in isolation
- Traditional ML models treat transactions independently and fail to capture these links

Graph Neural Networks are well-suited for this task because they:
- Model transactions as **nodes and edges**
- Learn hidden relationships between entities
- Detect complex fraud patterns such as collusion and abnormal transaction flows
- Provide better performance on highly imbalanced fraud datasets

---

## Overview
- Transactions are modeled as a graph
- Nodes represent entities or transactions
- Edges represent transactional relationships
- A GNN is used to learn relational patterns for fraud detection

## Technologies Used
- Python
- PyTorch
- PyTorch Geometric
- NetworkX
- Scikit-learn

## Setup
```bash
pip install -r requirements.txt
