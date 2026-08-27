Urban Traffic Accident Risk Assessment and Prediction Using Machine Learning

Team Members

Anjali Kasarla – 2420030170


Vinusha Muppala – 2420030212


Lasya Geethika – 2420030678


Supervisor

Dr. Katanguri Swanthana (CSE)

Abstract

This project develops a Machine Learning framework for predicting urban traffic accident risk using traffic, weather, road, and accident-related information. The system applies machine learning and natural language processing techniques to classify traffic situations into three risk levels: Low, Medium, and High. Explainability techniques such as SHAP and LIME are incorporated to understand the factors contributing to predictions. A web-based dashboard is used to present risk predictions and analytical results.

Objectives

Predict urban traffic accident risk using machine learning.

Classify traffic situations into Low, Medium, and High risk levels.

Process traffic, weather, road, and accident-related information.

Apply NLP techniques to relevant textual accident information.

Compare different machine learning models.

Provide interpretable predictions using SHAP and LIME.

Present predictions and analysis through a web dashboard.

Technologies Used

Programming: Python

Data Processing: Pandas, NumPy

Machine Learning: Scikit-learn

Natural Language Processing: NLP

Explainable AI: SHAP, LIME

Data Visualization: Matplotlib, Seaborn

Dashboard: Streamlit

Development: Jupyter Notebook

Version Control: GitHub

Methodology

Data Collection
      ↓
Data Preprocessing
      ↓
NLP Analysis
      ↓
Feature Engineering
      ↓
Feature Selection
      ↓
ML Model Training
      ↓
Risk Classification
      ↓
SHAP/LIME Explanation
      ↓
Dashboard
      ↓
Testing & Evaluation

Machine Learning Models

The project considers the following machine learning models:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

The models are evaluated and compared to determine their performance for accident-risk classification.

Risk Classification

The system classifies traffic conditions into three risk categories:

Low Risk

Medium Risk

High Risk

Explainable AI

The project uses explainability techniques to understand the factors influencing model predictions.

SHAP: Used to analyse feature contributions to model predictions.

LIME: Used to provide explanations for individual predictions.

These techniques help make the prediction results easier to interpret.

Evaluation Metrics

The models are evaluated using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

Repository Structure

├── src/
├── data/
├── results/
├── reports/
├── docs/
├── README.md
└── requirements.txt

Installation

Clone the repository:

git clone <repository-url>

Move into the project directory:

cd <repository-folder>

Install the required dependencies:

pip install -r requirements.txt

Running the Application

Run the Streamlit application using:

streamlit run src/app.py

The application provides the interface for entering traffic-related information and viewing the resulting accident-risk prediction and analysis.

Project Workflow

The complete workflow consists of:

Data collection

Data preprocessing

Exploratory analysis

NLP processing where applicable

Feature engineering

Feature selection

Machine learning model training

Risk classification

Model evaluation

Explainability analysis

Dashboard implementation

Project Outputs

The project produces:

Accident-risk predictions

Low, Medium, and High risk classification

Model performance metrics

Confusion matrices

Risk analysis visualizations

Feature-importance information

SHAP/LIME explanations

Dashboard-based presentation

Future Scope

The framework can be extended with additional traffic, environmental, geographical, and real-time data sources. Further improvements can also include advanced prediction models, larger datasets, and real-time traffic-risk monitoring.
