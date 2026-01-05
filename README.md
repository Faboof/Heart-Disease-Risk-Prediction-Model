
# Overview

This project analyzes a health dataset and builds a simple risk scoring model to estimate the probability that an individual has heart disease.

The project focuses on basic data preprocessing, predictive modeling, and risk segmentation, with an emphasis on interpreting model results in an actuarial-style framework rather than purely clinical prediction.

The goal of this project is to practice end-to-end risk modeling and translate model outputs into meaningful risk tiers and pricing-style relativities using a real-world dataset.

---

# Dataset

**Source:** *(https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction)*

**To do:**
1. Download the dataset CSV file.
2. Update the file path in the script to match your local machine.

**Dataset details:**
- Several hundred patient records
- Demographic and clinical features
- Binary target variable indicating presence of heart disease (Yes / No)
- Realistic class imbalance between low-risk and high-risk individuals

---

# Methodology

The analysis follows a simple and transparent modeling approach:

- Cleaned and prepared the dataset for modeling
- Converted categorical variables into numeric indicators
- Trained a logistic regression model to estimate individual heart disease risk
- Evaluated model performance using accuracy and ROC-AUC
- Grouped individuals into low, medium, and high risk tiers based on predicted probabilities
- Compared average predicted risk across tiers to derive pricing-style risk relativities

This approach mirrors common practices in actuarial pricing, underwriting, and risk segmentation.

---

# Results Summary

- Model accuracy of approximately **75%**
- ROC-AUC of approximately **0.83**, indicating strong separation between higher- and lower-risk individuals
- Clear risk differentiation across tiers:
  - Low-risk group average predicted risk ≈ **7%**
  - High-risk group average predicted risk ≈ **96%**
- High-risk individuals showed over **14×** the expected risk relative to the low-risk baseline (toy example)

---

# Requirements

- **Python:** 3.7+ (recommended: 3.8 / 3.9 / 3.10)

**Libraries:**
- pandas
- numpy
- scikit-learn

---

# Installation

```bash
pip install pandas numpy scikit-learn
