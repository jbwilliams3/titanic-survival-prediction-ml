# Titanic Survival Prediction (Machine Learning)

This project builds a machine learning model to predict which passengers survived the Titanic disaster, based on features like age, sex, class, and more. It follows a typical data science workflow from data cleaning and EDA to modeling and evaluation.

## 🚀 Project Structure
titanic-survival-prediction-ml/ │ ├── data/ │ ├── raw/ # Original unprocessed data │ └── processed/ # Cleaned and transformed data │ ├── notebooks/ │ ├── 01-data-cleaning.ipynb │ ├── 02-eda.ipynb │ ├── 03-modeling.ipynb │ └── 04-evaluation.ipynb │ ├── outputs/ │ ├── figures/ # Charts and visualizations │ └── models/ # Saved model files │ ├── src/ │ ├── utils.py │ └── train_model.py │ ├── .gitignore ├── LICENSE ├── README.md └── requirements.txt

## 📊 Data

The dataset used is the [Titanic dataset](https://www.kaggle.com/c/titanic/data) from Kaggle.

- **Target Variable**: `Survived`
- **Features**: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.

## 🧠 Techniques

- Data Cleaning and Imputation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training (Logistic Regression, Random Forest, etc.)
- Evaluation Metrics (Accuracy, Precision, Recall, ROC AUC)

## 🔧 Installation

To set up the project locally:

```bash
git clone https://github.com/jbwilliams3/titanic-survival-prediction-ml.git
cd titanic-survival-prediction-ml
pip install -r requirements.txt
