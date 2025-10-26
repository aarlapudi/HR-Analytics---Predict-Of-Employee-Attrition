# HR-Analytics---Predict-Of-Employee-Attrition
This HR Attrition project aims to analyze employee data to understand the key factors influencing attrition. Using Python for data cleaning, visualization, and modeling, the project helps identify patterns in employee behavior. The insights are further explained using SHAP values and visualized through an interactive Power BI dashboard.

## Source 
Data set : https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Tools used 

Python 3.x

SHAP

Power BI

Juypter Notebook

## 🛠️ How to Run the Project

### 1. Clone the Repository

   git clone https://github.com/your-aarlapudi/HR-Analytics---Predict-Of-Employee-Attrition.git
   
   cd HR-Analytics---Predict-Of-Employee-Attrition

### 2. Set Up the Environment
   
   It’s recommended to create a new environment to avoid dependency issues.

   conda create -n hr_env python=3.9
   conda activate hr_env

### 3. Install Required Libraries

   import pandas as pd
   
   import matplotlib.pyplot as plt

   import seaborn as sns

   import plotly.express as px

   from sklearn.model_selection import train_test_split

   from sklearn.linear_model import LogisticRegression

   import shap

   import numpy as np

### 4.Run the Python Script / Notebook

   jupyter notebook

### 5.View Outputs and Visualizations

EDA plots (e.g., correlation heatmap, attrition distribution) will appear inline in Jupyter or be saved in the outputs/ folder.

SHAP value plots will help explain model predictions.

## Conclusion:
The HR Attrition Prediction project effectively combines data analytics, machine learning, 
visualisation, and interpretability to address a real-world HR challenge. Using Python for data 
preprocessing, visualisation, and logistic regression modelling allowed for the accurate prediction 
of employee attrition. SHAP value analysis provided transparency and interpretability, making it 
easier to understand which features contribute most to attrition. The Power BI dashboard 
translated analytical results into a visual format that can be easily understood by HR stakeholders 
to drive retention strategies.





