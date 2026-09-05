# Bonn EEG Leakage-Aware Benchmarking

This repository contains the source code for the study:

"A Leakage-Aware Feature-Based Benchmarking Framework of Tree-Based and Non-Tree Models for Multiclass Bonn EEG Classification"

## Overview

This project implements a leakage-controlled benchmarking framework for multiclass EEG classification using the University of Bonn EEG dataset.

The study evaluates several machine learning models under a repeated stratified cross-validation framework with strict prevention of data leakage.

## Evaluated Models

The following machine learning algorithms are evaluated:

- Random Forest
- XGBoost
- LightGBM
- Support Vector Machine (SVM-RBF)
- Multilayer Perceptron (MLP)

Additional component analysis:
- XGBoost + Feature Selection
- XGBoost + SMOTE
- XGBoost + Feature Selection + SMOTE

## Dataset

Dataset:
University of Bonn EEG Dataset

Characteristics:
- 500 EEG segments
- 5 classes (A–E)
- 181 handcrafted EEG features

## Experimental Framework

The evaluation pipeline includes:

- Training-fold normalization
- Fold-internal feature selection
- Training-only SMOTE augmentation
- Nested hyperparameter optimization
- Repeated Stratified 5-fold Cross Validation
- Statistical comparison
- SHAP-based feature interpretation

## Reproducibility

The repository provides:

- Feature extraction scripts
- Data preprocessing pipeline
- Model training scripts
- Evaluation procedures
- Statistical analysis
- SHAP interpretation code

## Software Environment

Main libraries:

- Python
- Scikit-learn
- XGBoost
- LightGBM
- Imbalanced-learn
- SHAP
