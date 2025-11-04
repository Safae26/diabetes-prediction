# Diabetes Prediction using SVM 🩺

A machine learning project that implements a Support Vector Machine classifier to predict diabetes based on patient health metrics. This system analyzes medical data to classify individuals as diabetic or non-diabetic (1 or 0), serving as a practical example of healthcare AI applications.

## 📋 Project Overview

This project uses the PIMA Diabetes Dataset to build a predictive model that can help in early diabetes detection. The model processes various health parameters to make binary classification predictions:

- **0** → Non-Diabetic
- **1** → Diabetic

## 🛠️ Technical Implementation

### Features
- **Data Processing**: Handles the PIMA Diabetes Dataset with 768 instances and 8 medical features
- **Data Standardization**: Uses StandardScaler to normalize features for better model performance
- **Model Training**: Implements Linear Support Vector Machine (SVM) for binary classification
- **Model Evaluation**: Achieves 77% accuracy on test data with proper train-test splitting
- **Predictive System**: Ready-to-use prediction pipeline for new patient data

### Dataset Features
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years

### Tech Stack
- **Python** with scikit-learn, pandas, numpy
- **Support Vector Machine (SVM)** with linear kernel
- **StandardScaler** for data normalization
- **Stratified Sampling** to maintain class balance
- **Accuracy Score** for model evaluation

## 📊 Dataset Details
- **768 patient records** with 8 medical features each
- **Class distribution**: 500 Non-Diabetic vs 268 Diabetic
- **Features**: Various health metrics and demographic information
- **Target**: Binary classification (0/1)

## Usage

The project includes a complete predictive system that can:

1. Process raw patient health data
2. Standardize features using pre-trained scaler
3. Make real-time predictions using the trained SVM model
4. Output clear diabetic/non-diabetic classification

## 📈 Model Performance
- **Training Accuracy**: 78.66%
- **Testing Accuracy**: 77.27%
- **Model**: Linear SVM Classifier
