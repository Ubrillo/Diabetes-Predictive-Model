# Diabetes Predictor

A machine learning classification model that predicts diabetes likelihood from patient health data, built as part of a Machine Learning and Neural Computing university module. Uses Principal Component Analysis (PCA) for dimensionality reduction and a Support Vector Machine (SVM) for classification, achieving 80% accuracy.

## Overview

Diabetes is often diagnosed late due to subtle early indicators across multiple health metrics. This project explores whether a classical ML approach — dimensionality reduction followed by a margin-based classifier — can effectively flag at-risk patients from structured health data, while also serving as a practical exercise in the full ML workflow: EDA, preprocessing, modelling, and evaluation.

## Features

- **Exploratory Data Analysis (EDA)** — Analysis of feature distributions, correlations, and class balance to understand the dataset before modelling.
- **Dimensionality Reduction** — PCA applied to reduce feature space while preserving variance, improving model efficiency and reducing noise.
- **SVM Classification** — Support Vector Machine trained to classify patients as diabetic or non-diabetic.
- **Model Evaluation** — Performance assessed using Accuracy, Precision, Recall, F1-Score, and AUC (Area Under Curve) rather than accuracy alone, to account for class imbalance.
- **Documented Results** — Technical methodology and findings written up alongside the code.

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| Data Handling | Pandas, NumPy |
| Modelling | Scikit-Learn (SVM, PCA) |
| Evaluation | Scikit-Learn metrics |

## Methodology

1. **Data Exploration** — Examined the dataset's feature distributions, missing values, and class balance.
2. **Preprocessing** — Cleaned and scaled features ahead of dimensionality reduction.
3. **PCA** — Reduced the feature space to the most informative components while retaining variance.
4. **Model Training** — Trained an SVM classifier on the reduced feature set.
5. **Evaluation** — Assessed performance using Accuracy, Precision, Recall, F1-Score, and AUC, achieving **80% accuracy**.

## Results

| Metric | Score |
|---|---|
| Accuracy | 80% |
| Precision | 85% |
| Recall | 68% |
| F1-Score | 75% |
| AUC |  |


## Getting Started

### Prerequisites
- Python 3.10+
- Jupyter Notebook (if running as a notebook)

### Installation
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
```

### Running the Project
```bash
jupyter notebook diabetes_predictor.ipynb
```
*(or `python main.py` if structured as a script)*

## Project Structure
```
.
├── data/                  # Dataset
├── notebooks/              # EDA and model development
├── diabetes_predictor.ipynb
└── requirements.txt
```

## What I Learned

This project strengthened my understanding of the end-to-end machine learning pipeline — from EDA through to dimensionality reduction, model training, and rigorous evaluation beyond a single metric. Using PCA alongside SVM also gave me hands-on insight into how reducing feature complexity affects classifier performance, which is directly relevant to applied data science and ML engineering work.

## Author

**Ubrillo** — [GitHub](https://github.com/<your-username>) · [LinkedIn](#)
