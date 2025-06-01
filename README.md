# Heart Disease Prediction using ML

Heart disease is a major cause of mortality worldwide. This project aims to utilise various machine learning algorithms to predict the presence of heart disease based on clinical parameters. Early detection can lead to timely treatment and improved patient outcomes.

## 📌 Project Overview

This project develops a classification model to predict whether a person has heart disease or not, utilising a dataset of medical features. The goal is to analyse different machine learning algorithms and compare their performance.

## 📂 Dataset

The dataset contains several clinical features, including:
- Age, Sex
- Chest Pain Type (`cp`)
- Fasting Blood Sugar (`fbs`)
- Resting ECG (`restecg`)
- Exercise Induced Angina (`exang`)
- Slope of the peak exercise ST segment (`slope`)
- Number of major vessels colored by fluoroscopy (`ca`)
- Thalassemia (`thal`)
- And more...

The target variable indicates the presence (`1`) or absence (`0`) of heart disease.

## 🧠 Machine Learning Algorithms Used

Implemented using **Python** and popular libraries like `scikit-learn`, `Keras`, and `XGBoost`:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (Linear)
- K-Nearest Neighbours (KNN)
- Decision Tree
- Random Forest
- XGBoost
- Artificial Neural Network (ANN with 1 hidden layer)

## 🔍 Exploratory Data Analysis (EDA)

- Correlation heatmaps
- Feature-wise analysis (e.g., `sex`, `cp`, `fbs`, `thal`)
- Visualisation of target value distribution

## ⚙️ Implementation Steps

1. Import libraries and the dataset
2. Perform EDA and visualise features
3. Preprocess and split the data into train/test sets
4. Train models and evaluate using performance metrics (accuracy, precision, recall, etc.)
5. Compare model outputs

## ✅ Results

The models achieved high accuracy and were effective in identifying key predictors of heart disease. Ensemble models, such as **Random Forest** and **XGBoost**, performed particularly well.

## 📌 Conclusion

Machine learning algorithms can significantly aid in the early detection of heart disease. With continued improvement and larger datasets, these models can enhance personalised healthcare and preventive interventions. 

## 📚 Institution

**Department of Computer Science & Engineering**  
**GITAM (Deemed to be University), Visakhapatnam**
