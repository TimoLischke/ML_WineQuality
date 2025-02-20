# ML_WineQuality
Prediction of Wine Quality using ML

Dataset used:
https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

Jupyter notebook: ML_WineQuality.ipynb 

Import libraries to Jupyter notebook
Import data table to Jupyter notebook

Check data structure
Check for null values and duplicates

Exporatory Data Analyses using plot histograms of numerical data
Create Countplot of Wine Quality

Normalization: Without or with MinMax Standardization
Correlation analyis of feature to target 
Dropping 5 of the 11 feature columns due to high inter-feature correlation or low target correlation

Data split: 80% training values and 20% test values

Supervised Machine Learning Models to predict Wine Quality:
KNN Classification Model using 11 non-normalized, 11 normalized and 6 selected normalized input features
Logistic Regression Classification Model using the six selected normalized input features
Decision Tree Classification Model using the six selected normalized input features
Add 4 Ensemble Models (LogReg+Bagging, RandomForest, GradientBoosting, LogReg+Adapt.Boosting) using the six selected normalized input features
Calculate accuracy for all the models and the respective input features + graphical representation
Compute Confusion Matrices for all models
Visualize the Coefficient of Variation for the features of the best model (LogReg)

Repository:
https://github.com/TimoLischke/ML_WineQuality

Project Presentation:
https://www.canva.com/design/DAGfXpuzW8U/10SBgAVWcqVBgyKkaUgNfA/edit?ui=eyJEIjp7IlEiOnsiQSI6dHJ1ZX19fQ
