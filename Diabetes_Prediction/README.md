# **Diabetes Prediction Using Machine Learning**

## **Overview**

This project demonstrates how to predict the likelihood of diabetes in individuals based on a dataset using machine learning. The prediction model is built using the Python programming language, with the Scikit-learn (sklearn) library for machine learning, and other essential libraries such as Pandas and Matplotlib for data manipulation and visualization.

## **Table of Contents**

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Modeling Approach](#modeling-approach)
- [How to Run the Project](#how-to-run-the-project)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## **Introduction**

Diabetes is a chronic medical condition that affects how your body turns food into energy. The goal of this project is to use machine learning to predict whether a person is at risk of diabetes based on factors such as age, BMI, blood pressure, insulin levels, and more. By predicting this early, individuals can take preventive measures to control the condition.

## **Dataset**

The dataset used in this project is the Pima Indians Diabetes Database, which contains information collected from female patients of Pima Indian heritage. The dataset includes the following features:

- **Pregnancies**: Number of pregnancies
- **Glucose**: Plasma glucose concentration after a 2-hour oral glucose tolerance test
- **Blood Pressure**: Diastolic blood pressure (mm Hg)
- **Skin Thickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-hour serum insulin (mu U/ml)
- **BMI**: Body mass index (kg/m^2)
- **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history
- **Age**: Age in years
- **Outcome**: Outcome (1: Diabetic, 0: Non-diabetic)

The dataset can be found here: [Pima Indians Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

## **Libraries Used**

- **Scikit-learn**: The primary library used for building machine learning models.
- **Pandas**: For data manipulation and loading datasets.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizing data and results.
- **Seaborn**: For advanced statistical visualizations.

## **Modeling Approach**

1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Handle missing values (if any).
   - Split the dataset into training and testing sets (80% training, 20% testing).
   
2. **Feature Selection**:
   - We use all the available features to train the model.
   - Features are scaled (using StandardScaler) to improve model accuracy.

3. **Model Selection**:
   - Various classification algorithms are tested, including:
     - Logistic Regression
     - Decision Trees
     - Support Vector Machine (SVM)
   - The best model is selected based on performance metrics such as accuracy, precision.

4. **Model Evaluation**:
   - After training, the model is evaluated using a confusion matrix and classification report.
  
5. **Prediction**:
   - After the model is trained, it is used to predict the likelihood of diabetes for new inputs.

## **How to Run the Project**

### **Requirements**


- Python 3.x
- Install the required libraries by running:

```bash
pip install -r requirements.txt
```

## **Running the file**

```bash 
python Diabetes_Prediction.py
```
