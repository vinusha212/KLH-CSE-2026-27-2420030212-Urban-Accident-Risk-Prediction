# Urban Traffic Accident Risk Assessment and Prediction Using Machine Learning

## Team Members

- **Anjali Kasarla** – 2420030170  


- **Vinusha Muppala** – 2420030212  


- **Lasya Geethika** – 2420030678  


## Supervisor

**Dr. Katanguri Swanthana (CSE)**

---

## Project Overview

Urban traffic accidents are influenced by several factors, including traffic conditions, vehicle speed, weather, road conditions, time, location, and accident-related characteristics. Because these factors can occur together and vary across different traffic situations, identifying accident risk using individual factors can be difficult.

This project proposes a machine learning-based framework for **urban traffic accident risk assessment and prediction**. The framework processes available traffic and accident-related information, prepares the data for analysis, creates relevant features, selects useful predictors, and applies machine learning classification techniques.

The system classifies traffic conditions into three accident-risk levels:

- **Low Risk**
- **Medium Risk**
- **High Risk**

The project also incorporates explainability techniques to understand the factors contributing to model predictions. A Streamlit-based dashboard is used to provide an interactive interface for prediction and visualization.

---

## Abstract

This project develops a Machine Learning framework for assessing and predicting urban traffic accident risk using traffic, weather, road, and accident-related information. The framework follows a structured process involving data collection, preprocessing, exploratory analysis, feature engineering, feature selection, machine learning model development, evaluation, and explainability.

Different machine learning classification models are considered, including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine. These models are used to classify traffic conditions into Low, Medium, and High accident-risk categories. The models are compared using standard evaluation measures such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

Natural Language Processing techniques can also be applied when textual accident information is available. Explainable AI techniques such as SHAP and LIME are incorporated to analyse the contribution of features to model predictions. The final system provides an interactive dashboard through which users can enter relevant traffic conditions, obtain an estimated risk category, and analyse the factors associated with the prediction.

---

## Objectives

The main objectives of the project are:

- To analyse urban traffic and accident-related data.
- To preprocess and clean the available dataset.
- To handle missing, duplicate, and inconsistent records.
- To process numerical and categorical traffic-related variables.
- To extract useful information from time and location attributes.
- To apply NLP techniques to relevant textual accident information.
- To perform feature engineering and feature selection.
- To develop machine learning models for accident-risk classification.
- To compare the performance of different classification algorithms.
- To classify traffic situations into Low, Medium, and High risk.
- To use explainability techniques to understand model predictions.
- To develop an interactive dashboard for prediction and analysis.

---

## Technologies Used

### Programming Language

- Python

### Data Processing

- Pandas
- NumPy

### Machine Learning

- Scikit-learn

### Natural Language Processing

- NLP
- TF-IDF where applicable

### Explainable AI

- SHAP
- LIME

### Data Visualization

- Matplotlib
- Seaborn

### Dashboard

- Streamlit

### Development Environment

- Jupyter Notebook

### Version Control

- Git
- GitHub

---

## Proposed Methodology

The proposed framework follows the workflow below:

```text
Data Collection
       ↓
Data Preprocessing
       ↓
Exploratory Data Analysis
       ↓
NLP Analysis
       ↓
Feature Engineering
       ↓
Feature Selection
       ↓
Machine Learning Model Training
       ↓
Risk Classification
       ↓
Model Evaluation
       ↓
Explainability Analysis
       ↓
Interactive Dashboard
       ↓
Testing and Analysis
