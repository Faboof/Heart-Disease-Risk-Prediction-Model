
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
