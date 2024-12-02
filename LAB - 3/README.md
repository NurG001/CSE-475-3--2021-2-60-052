# CSE475 Lab 3: Exploring Ensemble Learning and Explainable AI on Kaggle Datasets (Cyber Threat Detection)

This repository contains the code and report for **Lab 3** of the CSE475 course, which explores the application of ensemble learning techniques and explainable AI (XAI) for cyber threat detection using a Kaggle dataset.

## Contents

1. **CSE475_Lab_3_Exploring_Ensemble_Learning_and_Explainable_AI_on_Kaggle_Datasets(CyberThreatDetection)_Report.pdf**
    - A detailed report describing the methods, implementation, and findings from applying ensemble learning and XAI techniques to a cyber threat detection dataset.
    - The report includes explanations of the models, performance evaluations, and insights from SHAP and LIME explainability methods.
  
2. **CSE475_Lab_3_Exploring_Ensemble_Learning_and_Explainable_AI_on_Kaggle_Datasets(CyberThreatDetection).ipynb**
    - The Python code implementing the machine learning pipeline for the cyber threat detection task.
    - The code includes data preprocessing, training various ensemble models (Random Forest, AdaBoost, Gradient Boosting, Stacking, and Voting Classifier), and using SHAP and LIME for model interpretability.
    - Evaluation of model performance using metrics like accuracy, precision, recall, and F1 score.

## Overview

In this project, we focused on detecting cyber threats using machine learning techniques. Specifically, we applied ensemble learning methods to improve model performance. We used **Bagging** (Random Forest), **Boosting** (AdaBoost and Gradient Boosting), **Stacking**, and **Voting Classifiers**. The project also incorporated **Explainable AI (XAI)** techniques, namely **SHAP** and **LIME**, to make the models' predictions more interpretable.

### Key Steps
- **Dataset**: The dataset used in this project is a labeled cyber threat detection dataset from Kaggle, where each instance represents a network activity, and the target label indicates whether it is "Normal" or "Malicious".
- **Modeling**: We experimented with multiple ensemble methods to combine the predictions of multiple base learners to improve classification accuracy.
- **Explainability**: We used SHAP and LIME to interpret the models' decisions and gain insights into which features were most important in making predictions.
- **Evaluation**: The models were evaluated using standard classification metrics, including accuracy, precision, recall, and F1 score, along with cross-validation to ensure robustness.

## Installation and Requirements

To run the Python code, make sure you have the following libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `shap`
- `lime`

You can install these libraries using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn shap lime

