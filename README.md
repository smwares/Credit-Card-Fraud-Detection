# Credit Card Fraud Detection

[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge)](https://jupyter.org/)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge)](https://www.python.org/)
[![CC-0 License](https://img.shields.io/badge/License-CC--0-green?style=for-the-badge)](https://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge)](https://github.com/coderhersh/Credit-Card-Fraud-Detection)
[![Visual Studio Code](https://img.shields.io/badge/Editor-Visual%20Studio%20Code-blue?style=for-the-badge)](https://code.visualstudio.com/)

## Project Overview

This machine learning project focuses on Credit Card Fraud Detection. The dataset used for this project is sourced from Kaggle and contains transactions made by European cardholders in September 2013. The goal is to develop a machine learning model capable of detecting fraudulent transactions based on the provided parameters. To protect user privacy, the original dataset features are not disclosed. Instead, the dataset consists of numerical input variables resulting from a PCA transformation, with 'Time' and 'Amount' being the only non-transformed features. The 'Class' feature indicates whether a transaction is fraudulent (1) or not (0).

## About the Dataset

- The dataset contains transactions made by credit cards.
- Transactions occurred over two days.
- There are 492 frauds out of 284,807 transactions.
- The dataset is highly unbalanced, with frauds accounting for 0.172% of all transactions.
- Features V1 through V28 are PCA-derived principal components.
- 'Time' represents the time elapsed between transactions.
- 'Amount' denotes the transaction amount.

Given the class imbalance, accuracy is best measured using the Area Under the Precision-Recall Curve (AUPRC) rather than a confusion matrix accuracy, which is not meaningful for unbalanced classification.

## Dataset Link

🏠 [Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

## Installation Guide


