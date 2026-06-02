# LUAD Stage Classification Using Deep Learning

This repository contains code and project materials for a deep learning class project.

## Project Aim

The aim of this project is to classify lung adenocarcinoma samples into low-stage and high-stage groups using RNA gene-expression data.

## Data

The project uses gene-expression data and metadata from:

- TCGA-LUAD
- GSE72094

The label is based on cancer stage group:

- Low-stage LUAD
- High-stage LUAD

Raw and processed datasets are not uploaded to this public repository. They are stored separately for privacy and file-size reasons.

## Planned Workflow

1. Prepare data-ready tables by merging gene-expression data with stage labels.
2. Train an MLP baseline model.
3. Evaluate model performance using ROC-AUC, F1-score, precision, recall, and confusion matrix.
4. Apply feature-importance methods to identify important genes.
5. Later, apply GraphSAGE/GNN using gene-gene relationship information.

## Main Models

- Multilayer Perceptron (MLP)
- GraphSAGE / Graph Neural Network

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

## Notes

This repository is currently public for class project sharing. Dataset files are not included in the repository.
