# Growsense – Smart Crop Recommendation System

Growsense is a smart crop recommendation system that combines **machine learning**, **soil health parameters**, and **environmental data** to suggest optimal crops along with confidence scores.  
The project is designed for **precision agriculture**, focusing on analysis, model performance, and practical system design.

---

## Overview
The system recommends suitable crops based on:

- **Soil nutrients**: Nitrogen (N), Phosphorus (P), Potassium (K)
- **Soil property**: pH level
- **Environmental conditions**: temperature, humidity, rainfall

Tree-based machine learning models were evaluated, with **Random Forest** selected as the final model due to strong performance and stability.

---

## System Highlights
- Supports **calibrated IoT sensor inputs** for soil nutrients  
- Accepts **real-time or fetched weather data**  
- Hybrid input design (sensor data + static/manual fallback)  
- Provides:
  - Primary crop recommendation  
  - Confidence score  
  - Top alternative crops  
- Lightweight explainability using feature influence  

---

## Machine Learning Workflow
- Exploratory Data Analysis (EDA)
- Feature preprocessing and validation
- Train–test split with stratification
- Model comparison:
  - Decision Tree
  - Random Forest
- Cross-validation and overfitting checks
- Feature importance analysis
- Final model training and inference

---

## Models Used
- **Decision Tree Classifier**
- **Random Forest Classifier**

Evaluation methods include:
- Accuracy score
- Confusion matrix
- Cross-validation

---

## Repository Structure
```text
growsense/
├── notebook/
│   └── growsense.ipynb
├── models/
│   ├── crop_model.pkl
│   └── label_encoder.pkl
├── requirements.txt
└── README.md

## Dataset Note
This project uses a publicly available **Crop Recommendation dataset** commonly shared on Kaggle for educational and research purposes.

The dataset includes soil nutrients, weather conditions, and crop labels.  
**The dataset itself is not included in this repository.**

## Purpose
- Applied machine learning practice
- Model evaluation and comparison
- Understanding feature influence in agricultural recommendations

This project is intended for **learning, demonstration, and portfolio purposes**.
