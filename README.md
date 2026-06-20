# Titanic Survival Prediction using Machine Learning

## Project Overview

This project develops a machine learning model to predict whether a passenger survived the Titanic disaster based on passenger attributes such as age, gender, ticket class, fare, and family information.

The project demonstrates the complete machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and performance visualization.

---

## Objectives

* Clean and preprocess raw data
* Handle missing values
* Perform exploratory data analysis
* Train multiple machine learning models
* Compare model performance
* Generate predictions
* Evaluate models using confusion matrix and ROC curve

---

## Dataset

Titanic Dataset from Kaggle.

Features include:

* Passenger Class
* Sex
* Age
* Number of Siblings/Spouses
* Number of Parents/Children
* Fare
* Embarkation Port

Target Variable:

* Survived (0 = No, 1 = Yes)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model.

### Decision Tree Classifier

Used to learn non-linear relationships.

### Random Forest Classifier

Used to improve prediction accuracy through ensemble learning.

---

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* ROC Curve
* AUC Score

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Feature Engineering
5. Exploratory Data Analysis
6. Model Training
7. Model Testing
8. Performance Evaluation
9. Model Saving

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~80%     |
| Decision Tree       | ~78%     |
| Random Forest       | ~85%     |

Random Forest achieved the best performance among the tested models.

---

## Visualizations

### Survival Distribution

![Survival Distribution](visualizations/survival_distribution.png)

### Confusion Matrix

![Confusion Matrix](visualizations/confusion_matrix.png)

### ROC Curve

![ROC Curve](visualizations/roc_curve.png)

---

## Conclusion

The project successfully demonstrates predictive modeling using machine learning techniques. Data preprocessing, model comparison, and evaluation techniques were applied to achieve reliable prediction performance. Random Forest provided the highest accuracy and best overall results.

---

## Author

Aman

Completed as part of the Thiranex Machine Learning Internship Program.
