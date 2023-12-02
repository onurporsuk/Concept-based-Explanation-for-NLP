# A Partial Replication Study of Concept-based Explainability for Neural Network Classifier in NLP

## Overview

This repository contains code and documentation for the replication study titled _A Partial Replication Study of Concept-based Explainability for Neural Network Classifier in NLP_. The study aims to replicate the findings of [COCKATIEL: COntinuous Concept ranKed ATtribution with Interpretable ELements for explaining neural net classifiers on NLP](https://github.com/fanny-jourdan/cockatiel) using the same methodology, dataset, and prediction model.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Contributing](#contributing)

## Dataset

The dataset used for this study is [IMDB Reviews]. It consists of 50,000 reviews. To maintain balance, the dataset consists of an equal number of positive and negative reviews. The dataset can be accessed from [this link](https://huggingface.co/datasets/imdb).

## Methods

### Techniques Used

- **Non-Negative Matrix Factorization (NMF):** Utilized Scikit-learn's NMF implementation to perform factorization.
- **Fine-tuned RoBERTa Model:** This model is a fine-tuned version of roberta-base on the imdb dataset. It can be accessed via [this link](https://huggingface.co/wrmurray/roberta-base-finetuned-imdb).

### Parameter Settings

- **NMF Parameters:**
- These are the hyperparameters of the NMF object used in the replication study:
  - `n_components`: [Value]
  - `max_iter`: [Maximum number of iterations]
  - `alpha_W`: [Regularization parameter for matrix W]

## Results

The results obtained from the replication study can be viewed in the paper: 

## Contributing

Contributions to improve the replication study or address issues are welcome! Feel free to fork the repository, make changes, and submit pull requests.
