# Experimental Framework

This folder contains experimental procedures used in the leakage-aware benchmarking framework.

The experiments include:

- Repeated stratified 5-fold cross-validation
- Nested hyperparameter optimization
- Model comparison experiments
- XGBoost component ablation analysis

Ablation experiments evaluate:

- XGBoost baseline
- XGBoost with feature selection
- XGBoost with SMOTE augmentation
- XGBoost with feature selection and SMOTE augmentation

All experiments use identical validation partitions to ensure fair comparison among models.
