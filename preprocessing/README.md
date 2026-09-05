# Leakage-Controlled Preprocessing

This folder contains preprocessing procedures used in the leakage-controlled benchmarking framework.

The preprocessing pipeline includes:

- Feature normalization using training-fold parameters
- Fold-internal feature selection
- Label encoding
- Prevention of information leakage between training and validation partitions

All preprocessing operations are performed only within training folds during repeated stratified cross-validation.
