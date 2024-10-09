# Electricity Theft Detection Using Machine Learning

This project focuses on developing a **cost-effective data-driven approach for detecting electricity theft** using machine learning (ML) and deep learning (DL) techniques. The project compares various models, including Decision Trees, Support Vector Machines (SVM), and Neural Networks, to identify the most efficient method for electricity theft detection.

## Table of Contents

- Introduction
- Project Overview
- Modeling Techniques
- Performance Evaluation
- Installation
- Usage
- Results
- Future Directions
- Contributors

## Introduction

Electricity theft is a significant issue for utility companies, leading to financial losses and grid inefficiencies. Traditional detection methods such as manual inspections and hardware-based solutions can be costly and inefficient. This project proposes a **data-driven approach** to detect anomalies in electricity consumption patterns, improving accuracy and scalability through machine learning and deep learning models.

## Project Overview

### Key Objectives:
1. **Detect electricity theft** using consumption patterns.
2. Compare the performance of various ML models.
3. Improve detection efficiency using advanced techniques like CNNs and time series forecasting.

### Dataset:
The dataset includes electricity consumption data from smart meters and other user-specific characteristics. Data preprocessing involved handling missing values, normalizing features, and addressing outliers.

## Modeling Techniques

The following machine learning and deep learning techniques were implemented in this project:

- **Decision Trees**: High accuracy and interpretability, making them suitable for theft detection.
- **Support Vector Machines (SVM)**: Effective in identifying complex patterns but sometimes prone to overfitting.
- **Neural Networks (NN)**: Advanced architectures such as CNN and LSTM were used to capture non-linear patterns in data.
- **Time Series Forecasting**: Useful in predicting future consumption patterns to identify theft.

## Performance Evaluation

The models were evaluated using various metrics:

- **Accuracy**: The percentage of correct predictions.
- **Precision**: Proportion of true positives out of all positives.
- **Recall**: Proportion of true positives identified.
- **F1 Score**: Balance between precision and recall.
- **Confusion Matrix**: Visualization of model performance.

| Model           | Accuracy | Precision | Recall | F1-Score |
|-----------------|----------|-----------|--------|----------|
| Decision Tree   | 99.96%   | 100%      | 99.85% | 99.92%   |
| SVM             | 78.71%   | 84.67%    | 16.76% | 28.89%   |
| Neural Networks | 83.56%   | 67.40%    | 53.18% | 59.29%   |

## Installation

### Requirements:
- Python 3.8+
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`, `tensorflow` (for deep learning models)
