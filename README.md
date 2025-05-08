## 🚢 Titanic Survival Prediction Model
This is a machine learning project that predicts passenger survival on the Titanic using various classification models. The famous Kaggle Titanic competition inspires this project, which provides a full workflow from data preprocessing to model evaluation.

## 📊 Project Overview
The goal of this project is to build a predictive model that answers the question:
“What sorts of people were more likely to survive?”

We analyze the dataset to uncover insights and use machine learning algorithms to predict survival outcomes based on passenger data such as:

- Passenger Class (Pclass)

- Sex

- Age

- Fare

- Family size (SibSp, Parch)

- Embarked location

## 🚀 Features
- Data Exploration & Visualization  
Visual insights into survival patterns and relationships between features.

- Data Cleaning & Preprocessing
  - Handling missing values
  - Encoding categorical variables
  - Feature engineering (e.g., creating new variables)

- Model Development  
Trains and compares multiple models:

  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)

- Model Evaluation  
Assesses performance using:

  - Accuracy
  - Confusion Matrix
  - Cross-validation scores

- Prediction  
Generates predictions for the test set and explores feature importance.


## 🗂 Dataset
The dataset is sourced from the [Kaggle Titanic competition](https://www.kaggle.com/c/titanic), which provides:

- train.csv: Training data with labels

- test.csv: Test data without labels

## 🔧 How to Run
1️⃣ **Clone the repository:**

```bash
git clone https://github.com/yourusername/Titanic-Survival-Prediction-Model.git
cd Titanic-Survival-Prediction-Model
```

2️⃣ **Install dependencies:**

Create a virtual environment and install packages from requirements.txt (if provided), or install manually:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3️⃣ ***Run the notebook:***

Launch Jupyter Notebook and open:
```
Titanic Survival Prediction.ipynb
```
