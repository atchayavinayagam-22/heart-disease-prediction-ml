# Heart Disease Prediction Using Machine Learning

## Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals make timely decisions and improve patient outcomes. This project uses Machine Learning techniques to predict the likelihood of heart disease based on clinical parameters such as age, cholesterol level, blood pressure, and heart rate.

The project compares the performance of two supervised learning algorithms:

* Logistic Regression
* Support Vector Machine (SVM)

---

## Objectives

* Analyze heart disease data using machine learning.
* Build predictive models for heart disease classification.
* Compare the performance of Logistic Regression and SVM.
* Evaluate model accuracy and generalization capability.

---

## Dataset Features

The dataset contains medical attributes commonly associated with cardiovascular health, including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Slope
* Number of Major Vessels
* Thalassemia

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Machine Learning Models

### Logistic Regression

A statistical classification algorithm used for binary classification problems.

**Results**

* Training Accuracy: 85.12%
* Good generalization with minimal overfitting

### Support Vector Machine (SVM)

A supervised learning algorithm that identifies the optimal decision boundary between classes.

**Results**

* Training Accuracy: 85.55%
* Slightly better training performance than Logistic Regression

---

## Performance Comparison

| Model                        | Training Accuracy |
| ---------------------------- | ----------------- |
| Logistic Regression          | 85.12%            |
| Support Vector Machine (SVM) | 85.55%            |

Both models achieved comparable performance on unseen data and demonstrated reliable prediction capability.

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Heart Disease Prediction

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Heart_Disease.ipynb
```

---

## Results

* Accurate prediction of heart disease risk using clinical data.
* Logistic Regression and SVM produced similar prediction performance.
* SVM achieved slightly higher training accuracy.
* Both models generalized well without significant overfitting.

---

## Future Enhancements

* Use larger healthcare datasets.
* Apply advanced ensemble learning techniques.
* Hyperparameter optimization.
* Deploy as a web application.
* Integrate real-time healthcare monitoring systems.

---

 
## Conclusion

This project demonstrates the effectiveness of Machine Learning in predicting heart disease using clinical data. Both Logistic Regression and Support Vector Machine models achieved reliable performance, highlighting the potential of data-driven approaches in supporting medical diagnosis and improving healthcare outcomes.

