# Titanic Survival Prediction

A machine learning project to predict which passengers survived the Titanic disaster using Python and scikit-learn.

## Project Overview

This is my first ML project, built as part of my journey towards becoming an AI/ML Engineer.
The goal is to predict passenger survival based on features like age, sex, passenger class, and family size.

## Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)
- Training set: 891 passengers
- Features used: PassengerClass, Sex, Age, SibSp, ParentsChildrenAboard, Fare, Embarked, FamilySize, IsAlone

## What I Did

1. **Data Cleaning** — handled missing values, removed duplicates, dropped useless columns
2. **Feature Engineering** — created FamilySize and IsAlone columns
3. **EDA** — visualized survival rates by age, sex, class and family size
4. **Model Training** — trained Logistic Regression and Random Forest models
5. **Evaluation** — compared models using accuracy, confusion matrix and classification report

## Results

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 76.8%    |
| Random Forest          | 76.1%    |
| Improved Random Forest | 78.1%    |

## Key Findings

- Female passengers had significantly higher survival rates than males
- 1st class passengers survived more than 2nd and 3rd class
- Children had higher survival rates than adults
- Solo travelers had lower survival rates than those with small families

## Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## How to Run

1. Clone this repo
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open `clean.ipynb` in VSCode or Jupyter
4. Run all cells in order

## What I Learned

- Full data cleaning pipeline (missing values, duplicates, outliers, encoding)
- How to build and evaluate ML classification models
- How to use EDA to find patterns in data
- Feature engineering to improve model performance
