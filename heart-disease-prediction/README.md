# Heart Disease Prediction using Machine Learning

## Project Overview

This project uses Machine Learning algorithms to predict whether a patient has heart disease based on medical attributes such as age, cholesterol level, chest pain type, and maximum heart rate.

The goal is to build and compare multiple classification models to determine which performs best for predicting heart disease.

---

## Dataset

The dataset contains medical attributes related to heart disease diagnosis.

Features include:

* age
* sex
* cp (chest pain type)
* trestbps (resting blood pressure)
* chol (cholesterol)
* fbs (fasting blood sugar)
* restecg (resting electrocardiographic results)
* thalach (maximum heart rate achieved)
* exang (exercise induced angina)
* oldpeak (ST depression induced by exercise)
* slope
* ca
* thal

Target variable:

```
target
0 = No heart disease
1 = Heart disease
```

---

## Project Workflow

### 1. Data Loading

The dataset is loaded using **Pandas** and inspected to understand its structure.

---

### 2. Exploratory Data Analysis (EDA)

Several techniques were used to explore the dataset:

* Data statistics
* Feature distribution
* Correlation heatmap

A correlation heatmap was used to visualize relationships between features and the target variable.

---

### 3. Data Preparation

The dataset was prepared for machine learning by separating:

```
Features (X)
Target (y)
```

---

### 4. Train/Test Split

The dataset was split into training and testing sets:

```
80% Training
20% Testing
```

This allows the model to be evaluated on unseen data.

---

### 5. Model Training

Three machine learning models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

Each model was trained using the training dataset and tested using the testing dataset.

---

### 6. Model Evaluation

Model performance was evaluated using:

```
Accuracy Score
Confusion Matrix
```

Results showed that **Random Forest** and **Logistic Regression** performed well on this dataset.

---

## Model Comparison

The models were compared using a bar chart to visualize their accuracy scores.

Example models tested:

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~0.88    |
| Decision Tree       | ~0.73    |
| Random Forest       | ~0.88    |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Learning Points

This project demonstrates:

* Exploratory Data Analysis (EDA)
* Feature correlation analysis
* Training multiple machine learning models
* Evaluating model performance
* Comparing models using visualization

---

## Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Testing additional machine learning models

---

## Author

Machine Learning practice project built as part of a learning roadmap.
