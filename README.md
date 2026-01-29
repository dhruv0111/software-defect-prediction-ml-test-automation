# Software Defect Prediction Using Machine Learning

This repository contains the implementation and experiments for the research paper:

**Software Defect Prediction Using Machine Learning to Support Test Automation**

📄 Paper (Zenodo, DOI): https://doi.org/10.5281/zenodo.18405705

## Contents
- Dataset: NASA CM1 (PROMISE repository)
- Model: Logistic Regression with class imbalance handling
- Evaluation: Accuracy, Precision, Recall, F1-score

## Abstract
This project explores the application of machine learning techniques for predicting defect-prone software modules using static code metrics. A Logistic Regression model with imbalance-aware learning is evaluated on a real-world software defect dataset to improve recall for defective modules, supporting risk-based test automation.


## Dataset
- Source: NASA CM1 dataset (PROMISE repository)
- Instances: 498 software modules
- Features: 21 static code metrics
- Target: Defective / Non-defective


## Methodology
- Data preprocessing and feature scaling
- Train-test split (80–20)
- Logistic Regression with class-balanced learning
- Evaluation using accuracy, precision, recall, and F1-score


## Results
The imbalance-aware model significantly improves recall for defect-prone modules compared to a baseline model, demonstrating the importance of recall-oriented evaluation in software testing contexts.



## How to Run
bash
pip install -r requirements.txt

## Author
Dhruv Sharma
