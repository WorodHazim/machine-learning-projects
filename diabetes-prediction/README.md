# Titanic Survival Prediction 🚢

Machine Learning project that predicts whether a passenger survived the Titanic disaster using passenger data.

---

## 📊 Dataset

The dataset contains information about Titanic passengers such as:

- Passenger Class (Pclass)
- Age
- Sex
- Fare
- Family Size

Target variable:

Survived  
0 = Did not survive  
1 = Survived

Dataset source: Kaggle Titanic Dataset

---

## 🧠 Models Used

The following Machine Learning models were tested:

| Model | Accuracy |
|------|------|
| Logistic Regression | ~79% |
| K-Nearest Neighbors | ~82% |
| Random Forest | ~86-88% |

---

## ⚙️ Features Used

The model was trained using the following features:

- Pclass
- Age
- Fare
- Sex
- FamilySize (engineered feature)

Feature engineering:
FamilySize = SibSp + Parch + 1

---

## 🧹 Data Preprocessing

Steps performed before training:

- Missing values in Age filled using mean
- Sex converted to numerical values
- New feature created: FamilySize
- Train/Test split (80/20)

---

## 📈 Model Evaluation

Evaluation metric used:
Accuracy Score

Example result:
Accuracy: 0.87

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Matplotlib
- Seaborn

---

## 🚀 How to Run

Clone the repository:

git clone https://github.com/WorodHazim/titanic-ml-prediction.git


Install dependencies:
pip install pandas scikit-learn matplotlib seaborn

Run the notebook:
jupyter notebook


Open:
TitanicSurvivalPrediction.ipynb

---

## 📌 Project Goal

Practice a full Machine Learning workflow:

- Data cleaning
- Feature engineering
- Model training
- Model comparison
- Model evaluation

---

## 👩‍💻 Author

Worod Hazim  
AI & Machine Learning Student
