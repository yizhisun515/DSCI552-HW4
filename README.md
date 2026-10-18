# DSCI 552 - Homework 4

**Course:** DSCI 552 - Machine Learning for Data Science  
**Student:** Yizhi Sun  
**GitHub Username:** yizhisun515

## Overview

This repository contains Homework 4 for DSCI 552 at the University of Southern California.

The assignment focuses on time series classification, feature extraction, logistic regression, regularization, model selection, and discriminant analysis.

## Contents

### 1. Time Series Feature Extraction
- Load and preprocess the AReM dataset.
- Split the dataset into training and test sets.
- Extract time-domain features from six sensor measurements.
- Compute minimum, maximum, mean, median, standard deviation, and quartiles.

### 2. Binary Classification
- Logistic Regression with Recursive Feature Elimination (RFE).
- Stratified cross-validation for model selection.
- L1-penalized Logistic Regression.
- Evaluation using confusion matrices, ROC curves, and AUC.
- Class imbalance analysis using case-control sampling.

### 3. Multiclass Classification
- L1-penalized Multinomial Logistic Regression.
- Gaussian Naive Bayes.
- Multinomial Naive Bayes.
- Model comparison using cross-validation and test error.

### 4. ISLR Exercises
- ISLR 4.8.3: Quadratic Discriminant Analysis.
- ISLR 4.8.7: Bayesian Classification and Posterior Probability.

### 5. Extra Credit
- ISLR 4.8.4: Curse of Dimensionality.
- ISLR 4.8.9: Odds and Probability.

## Repository Structure

```text
DSCI552-HW4/
├── data/
│   └── AReM/
│       ├── bending1/
│       ├── bending2/
│       ├── cycling/
│       ├── lying/
│       ├── sitting/
│       ├── standing/
│       ├── walking/
│       ├── bendingType.pdf
│       └── sensorsPlacement.pdf
├── notebook/
│   └── Sun_Yizhi_HW4.ipynb
├── README.md
└── requirements.txt
```

## Dataset

The AReM (Activity Recognition System Based on Multisensor Data Fusion) dataset contains 88 time series instances across seven activity categories.

Each instance contains six sensor measurements collected over time.

## Requirements

The required Python packages are listed in `requirements.txt`.

Install them using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required Python packages.
3. Open JupyterLab.
4. Open `notebook/Sun_Yizhi_HW4.ipynb`.
5. Run the notebook cells sequentially.

The notebook uses the relative dataset path:

```python
data_path = "../data/AReM"
```

Run the notebook from the `notebook/` directory to ensure the dataset path resolves correctly.
