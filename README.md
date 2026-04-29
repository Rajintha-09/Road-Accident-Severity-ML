# Prediction of Road Accident Severity Using Supervised Machine Learning Techniques

A research-based machine learning study focused on predicting road accident severity using environmental and road condition data.

---

## Project Overview

This repository contains the research paper, dataset reference, and machine learning model developed to analyze and predict **road accident severity**.

The study uses a large-scale United States accident dataset and formulates accident severity as a **binary classification problem (high vs low severity)**.

The project compares different machine learning models and analyzes key factors contributing to severe accidents.

### Key Highlights:
- Road accident severity prediction using supervised machine learning  
- Comparative analysis of Logistic Regression and Random Forest  
- Feature importance analysis  
- Handling large-scale real-world dataset  
- Practical prediction framework for real-world scenarios  

---

## Folder Structure
```
Road-Accident-Severity-ML/
│
├── Research Paper/
│ └── Research Paper.pdf
│
├── Dataset/
│ └── US_Accidents_March23.csv (not included due to size)
│
├── Code/
│ └── road_accidents.html
│
└── README.md
```
---

## Dataset

This study uses the **US Accidents (March 2023) dataset**, which contains over **7.7 million records** with 46 features.

⚠️ **Note:**  
Due to file size limitations on GitHub, the dataset is **not included in this repository**.

You can download the dataset from Kaggle:  
https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

Dataset includes:
- Weather conditions  
- Temperature, humidity, visibility  
- Distance and precipitation  
- Road infrastructure (signals, junctions, crossings)  

Preprocessing steps:
- Handling missing values  
- Label encoding categorical variables  
- Feature selection  

---

## Model Description

The following machine learning models were implemented:

- Logistic Regression  
- Random Forest  

**Random Forest** performed better, especially in detecting high-severity accidents.

---

## Methodology

- Data preprocessing and feature selection  
- Binary classification (high vs low severity)  
- Train-test split (80/20)  
- Model training and evaluation
  
Evaluation metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

- Feature importance analysis using Random Forest  
- Data visualization for pattern analysis  

---

## Key Findings

- Random Forest outperformed Logistic Regression  
- Better detection of high-severity accidents  
- Important features:
  - Temperature  
  - Distance  
  - Humidity  
  - Weather conditions  

- Environmental factors significantly influence accident severity  

---

## Practical Applications

- Traffic monitoring systems  
- Accident risk prediction  
- Emergency response planning  
- Road safety decision-making  

---

## Limitations and Future Work

- Dataset limited to the United States  
- Binary classification reduces detail of severity levels  
- Class imbalance affects prediction of severe accidents  
- Limited features (no driver behavior data)  

Future improvements:
- Multi-class severity prediction  
- Use of deep learning models  
- Inclusion of real-time traffic and behavioral data  
- Advanced imbalance handling techniques  

---

## Authors / Team Members

Chamali Abeysekara  
BSc in Applied Data Science Communication  

Team Members / Contributors:

RL Hewanayaka  
MZM Hussein  
MN Mohamed 


---
