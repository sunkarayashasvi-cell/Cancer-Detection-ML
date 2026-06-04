# Cancer Detection using Machine Learning

## Overview
KNN-based binary classifier to detect malignant vs benign 
breast tumours using the Wisconsin Diagnostic Breast Cancer dataset.

## Dataset
- Source: UCI ML Repository
- Size: 569 samples, 30 features

## Libraries
Python, NumPy, Pandas, Matplotlib, Seaborn, scikit-learn

## Approach
1. EDA — countplot, correlation heatmap
2. Preprocessing — label encoding, train-test split, StandardScaler
3. KNN — Elbow plot to find optimal K=7
4. Evaluation — confusion matrix, precision, recall, F1-score

## Key Results
Accuracy: ~95% | Recall (Malignant): ~96% | F1: ~0.95

## Key Insight
Recall is the critical metric in medical diagnosis — 
missing a cancer case (false negative) is far more 
dangerous than a false alarm.

## Project Context
Group assignment — Introduction to Data Science, IIT Patna.
