# Fake Job Posting Detection Using Random Forest

## Overview

Fake job advertisements have become a growing concern on online recruitment platforms. Fraudulent postings often aim to collect personal information, charge fake fees, or deceive job seekers through misleading employment opportunities.

This project uses Machine Learning and Natural Language Processing (NLP) techniques to automatically classify job postings as either genuine or fraudulent. A Random Forest Classifier is trained on job posting data after converting textual information into numerical features using TF-IDF Vectorization.

The model helps identify suspicious job advertisements and demonstrates the practical application of machine learning in fraud detection and recruitment analytics.

---

## Problem Statement

Online recruitment platforms host thousands of job advertisements daily, making manual verification difficult and time-consuming.

The objective of this project is to build a machine learning model capable of automatically detecting fraudulent job postings based on job descriptions, company information, requirements, and other related features.

---

## Objectives

- Detect fake job advertisements automatically.
- Analyze characteristics of fraudulent postings.
- Apply NLP techniques for text processing.
- Build a Random Forest classification model.
- Evaluate model performance using standard classification metrics.
- Identify important factors contributing to fraud detection.

---

## Dataset Information

### Dataset

Fake Job Postings Dataset

### Records

- Total Records: 17,880
- Total Features: 18

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | Genuine Job Posting |
| 1 | Fraudulent Job Posting |

### Class Distribution

- Genuine Jobs: 17,014 (95.16%)
- Fraudulent Jobs: 866 (4.84%)

The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Machine Learning Algorithm

- Random Forest Classifier

### NLP Technique

- TF-IDF Vectorization

---

## Project Workflow

```text
Dataset Collection
        ↓
Data Understanding
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
TF-IDF Vectorization
        ↓
Train-Test Split
        ↓
Random Forest Training
        ↓
Model Evaluation
        ↓
Feature Importance Analysis