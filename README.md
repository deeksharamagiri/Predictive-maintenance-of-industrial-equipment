# Predictive-maintenance-of-industrial-equipment
UE22AM241B – Mathematics for Machine Learning  Course Project 

This project builds a machine learning pipeline to predict machine failure in industrial environments, helping reduce unexpected breakdowns and optimize maintenance schedules.  

The model uses sensor data such as temperature, rotational speed, torque, and tool wear to anticipate failures. 

---

## Overview

- **Goal**: Predict machine failure based on real-time operational metrics
- **Model**: Random Forest Classifier (with Grid Search and Cross-Validation)
- **Scalability**: Uses `joblib` to serialize the model for deployment
- **Custom Logic**: Includes realistic thresholding and failure definition

---

## Dataset

- **Source**: [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)
- **Size**: 10,000 rows × 14 columns
- **Attributes**:
  - Air temperature [K]
  - Process temperature [K]
  - Rotational speed [rpm]
  - Torque [Nm]
  - Tool wear [min]
  - Product type, failure types, etc.

---

## Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `joblib` (for model deployment)


