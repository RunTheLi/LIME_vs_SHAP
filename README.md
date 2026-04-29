# Explainable Spam Detection (LIME + SHAP)

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Explainable AI](https://img.shields.io/badge/XAI-LIME%20%2B%20SHAP-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## Project Overview

This project builds a **Spam Detection model** using Machine Learning and enhances its interpretability using **Explainable AI (XAI)** techniques:

- **LIME (Local Interpretable Model-agnostic Explanations)**
- **SHAP (SHapley Additive exPlanations)**

The goal is not only to classify messages as spam or ham, but also to explain *why* the model makes those predictions.

---

## Objectives

- Build a text classification model for spam detection
- Convert text into numerical features using TF-IDF
- Train a Logistic Regression model
- Explain predictions using LIME and SHAP
- Compare both explainability methods

---

## Techniques Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Logistic Regression
- LIME (Local explanations)
- SHAP (Global + Local explanations)

---

## Workflow
Text Data → Preprocessing → TF-IDF → Model Training → Prediction → LIME + SHAP → Explanation → Visualization

## Requirement
- pandas
- numpy
- scikit-learn
- matplotlib
- lime
- shap
