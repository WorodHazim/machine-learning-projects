# Diabetes Prediction using Machine Learning

## Project Overview

This project uses Machine Learning to predict whether a patient has diabetes based on medical diagnostic features such as glucose level, BMI, age, and blood pressure.

The dataset used is the **Pima Indians Diabetes Dataset**, a well-known dataset for binary classification problems in healthcare.

---

## Dataset

Source:
https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

Features used in the dataset:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigree
* Age

Target variable:

```
Outcome
0 = No Diabetes
1 = Diabetes
```

---

## Project Steps

### 1. Data Loading

The dataset is loaded using **Pandas**.

### 2. Exploratory Data Analysis (EDA)

* Data statistics
* Correlation heatmap
* Distribution analysis

### 3. Data Cleaning

Some features contained invalid values (`0`) such as:

* Glucose
* BloodPressure
* BMI
* Insulin

These values were treated as missing data and replaced with the **mean value of each column**.

### 4. Feature Scaling

The dataset features were scaled using:

```
StandardScaler
```

This is important for algorithms that rely on distance calculations such as **KNN**.

### 5. Train/Test Split

The dataset was split into:

```
80% Training Data
20% Testing Data
```

### 6. Model Training

Three machine learning models were trained:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest

### 7. Model Evaluation

Accuracy was used to evaluate the models.

Results:

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~0.75    |
| KNN                 | ~0.74    |
| Random Forest       | ~0.75    |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## Visualization

Model comparison was visualized using a **bar chart** to compare accuracy across models.

---

## Key Learning Points

* Handling missing data
* Feature scaling with StandardScaler
* Using KNN for classification
* Comparing multiple machine learning models
* Visualizing model performance

---

## Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Using additional ML models
* Feature engineering

---

## Author

Machine Learning practice project built as part of a learning roadmap.
