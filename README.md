# Machine Learning-Based Heart Disease Prediction Using Logistic Regression

## Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning, specifically the Logistic Regression algorithm, based on the UCI Heart Disease Dataset.

The objective is to classify whether a patient has heart disease (AHD) based on clinical and medical attributes such as age, cholesterol level, chest pain type, blood pressure, maximum heart rate, and more.

This project includes data preprocessing, feature scaling, model training, prediction, evaluation, and visualization of results using confusion matrix and scatter plots.

---

## Dataset Used

### UCI Heart Disease Dataset

- Total Instances: 303
- Total Attributes: 14
- Target Variable: AHD (Presence of Heart Disease)

### Features Used

- Age
- Sex
- ChestPain
- RestBP
- Chol
- Fbs
- RestECG
- MaxHR
- ExAng
- Oldpeak
- Slope
- Ca
- Thal
- AHD (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Loading

- Imported the Heart.csv dataset using Pandas

### 2. Data Cleaning

- Removed unnecessary column (`Unnamed: 0`)
- Checked missing values
- Removed null values using `dropna()`

### 3. Data Preprocessing

- Converted categorical variables:
  - ChestPain
  - Thal
  - AHD

into numerical format using category encoding.

### 4. Feature Selection

- Independent Variables → All features except AHD
- Dependent Variable → AHD

### 5. Train-Test Split

- Training Data → 70%
- Testing Data → 30%

### 6. Feature Scaling

Used `StandardScaler()` for standardization.

### 7. Model Training

Applied:

## Logistic Regression

for classification.

### 8. Model Evaluation

Evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Scatter Plot Visualization

---

## Results

The Logistic Regression model successfully predicted heart disease presence with good classification performance.

### Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Output Visualization

### Confusion Matrix Heatmap

Used Seaborn heatmap for model performance visualization.

### Scatter Plot

Visualized Logistic Regression prediction output.

---

## Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart.csv
├── heart_disease_prediction.ipynb
├── requirements.txt
├── README.md
└── output_screenshots/
```

---

## Future Improvements

- Add ROC Curve and AUC Score
- Compare with other ML models:
  - Random Forest
  - SVM
  - XGBoost
- Apply Deep Learning models
- Deploy as a web application using Streamlit

---

## Author

### Mohamed Jasee

MSc Computational Biology  
BSc Microbiology

Interested in:

- Bioinformatics
- NGS Data Analysis
- Metagenomics
- Machine Learning in Biology
- Computational Biology
- Statistics
- Multio Omics

---

## GitHub Project Purpose

This project is part of my Machine Learning and Computational Biology portfolio to demonstrate practical applications of ML in healthcare and disease prediction.
