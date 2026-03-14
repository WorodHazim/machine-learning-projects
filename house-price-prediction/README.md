# House Price Prediction

This project uses **Machine Learning (Linear Regression)** to predict house prices based on several features such as house size, number of bedrooms, and age of the property.

The goal is to demonstrate a simple **regression pipeline** using Python and Scikit-Learn.

---

## Dataset

The dataset contains basic housing features:

| Feature  | Description                       |
| -------- | --------------------------------- |
| Size     | Size of the house (square meters) |
| Bedrooms | Number of bedrooms                |
| Age      | Age of the house (years)          |
| Price    | Target variable – house price     |

---

## Project Workflow

The project follows a standard Machine Learning pipeline:

1. Load dataset
2. Exploratory Data Analysis (EDA)
3. Select features and target variable
4. Train/Test split
5. Train Linear Regression model
6. Make predictions
7. Evaluate model performance using Mean Squared Error (MSE)

---

## Model Used

Linear Regression from `sklearn.linear_model`.

This model learns a linear relationship between house features and the predicted price.

---

## Evaluation Metric

The model performance is evaluated using:

**Mean Squared Error (MSE)**

Example result:

```
MSE ≈ 14,602,659
```

Lower values indicate better predictions.

---

## Example Prediction

Example input:

```
Size = 150
Bedrooms = 3
Age = 10
```

Predicted price:

```
≈ 498,260
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```
house-price-prediction
│
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## Future Improvements

Possible improvements:

* Add more features (location, area type, amenities)
* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Model deployment with Streamlit

---

## Author

Machine Learning practice project built as part of an **AI / Computer Vision learning roadmap**.
