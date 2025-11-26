🛳 Titanic Survival Prediction — Machine Learning Project

A complete ML pipeline that predicts passenger survival on the Titanic using classical machine learning techniques.

📁 Project Structure
titanic-survival-ml
│
├── titanic_survival_prediction.ipynb   # Main ML notebook
├── best_titanic_model.joblib           # Saved Random Forest model
│
├── data/
│     ├── train.xlsx                    # Training dataset
│     ├── test.xlsx                     # Test dataset
│
└── README.md

📘 Dataset

This project uses the Kaggle Titanic dataset:

Columns include:

PassengerId

Survived

Pclass

Name

Sex

Age

SibSp

Parch

Ticket

Fare

Cabin

Embarked

Excel format (.xlsx) works the same as CSV.


🚀 ML Workflow


✔ Data Cleaning

Outlier handling

Null value imputation

Encoding categorical values

Dropping unnecessary features

✔ Exploratory Data Analysis (EDA)

Count plots

Correlation heatmap

Feature distributions

✔ Model Training

Algorithms used:

Logistic Regression

Random Forest Classifier (Best)

Support Vector Machine (SVM)

✔ Model Evaluation

Accuracy score

Confusion matrix

Classification report

Cross-validation (cv=5)

🏆 Results
Model	Accuracy
Random Forest (Best)	~80–85%
SVM	~78–82%
Logistic Regression	~76–80%
🤖 Saved Model

The best model is saved as:

best_titanic_model.joblib


Load and predict:

import joblib
model = joblib.load("best_titanic_model.joblib")
model.predict([[3, 1, 22.0, 1, 0, 7.25, 0]])

▶️ Run Instructions

Clone the repo:

git clone https://github.com/abusegithub/titanic-survival-ml


Open the notebook:

jupyter notebook titanic_survival_prediction.ipynb


Run all cells.

🧑‍💻 Author

Akanksha (abusegithub)
Machine Learning / Python Developer

⭐ Support The Project

Give the repo a star ⭐ if you like it!
