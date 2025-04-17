# Heart Failure Prediction

This project aims to build a machine learning model that can predict the likelihood of heart failure based on clinical and demographic data. It is designed to assist medical professionals in identifying high-risk patients and taking early action.

## 1- Dataset

ِAbout The Dataset:


- Age	-> Age of the patient (in years).
- Sex	-> Gender of the patient: 1 = Male, 0 = Female.
- ChestPainType ->	Type of chest pain (e.g., Typical Angina, Atypical Angina, Non-anginal, Asymptomatic).
- RestingBP	-> Resting blood pressure (in mm Hg).
- Cholesterol	-> Serum cholesterol level (in mg/dl).
- FastingBS	-> Fasting blood sugar > 120 mg/dl: 1 = True, 0 = False.
- RestingECG	-> Resting electrocardiographic results (Normal, ST-T abnormality, LV hypertrophy).
- MaxHR	Maximum -> heart rate achieved during exercise.
- ExerciseAngina -> Exercise-induced angina: 1 = Yes, 0 = No.
- Oldpeak	-> ST depression induced by exercise relative to rest.
- ST_Slope	-> Slope of the peak exercise ST segment (Upsloping, Flat, Downsloping).
- HeartDisease	-> Target variable: 1 = Presence of heart disease, 0 = Absence.     

## 2- Objective

To predict the `HeartDisease` (whether the patient died during the follow-up period) using clinical features.

## 3- Tools & Technologies

- Python 
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

## 4- Models Used

- Logistic Regression
- Random Forest
- Support Vector Machine
- XGBoost
- Extra Trees
- Bagging
- LightGBM
- CatBoost

The models were evaluated using:
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC curve

## 5- Exploratory Data Analysis (EDA)

- Distribution of age and other clinical features
- Correlation heatmap
- Outlier detection
- Class imbalance handling

## 🧠 Model Training

- Data preprocessing: encoding, scaling
- Splitting: 80% training, 20% testing
- Hyperparameter tuning using GridSearchCV
- Cross-validation for robustness

## 6- Results

| Model              | Accuracy |
|-------------------|----------|
| XGBClassifier      | 89.33%   |
| LGBMClassifier     | 88.67%   |
| ExtraTrees         | 88.00%   |
| Catboost           | 87.33%   |
| Logistic Regression| 85.33%   |
| Random Forest      | 84.67%   |
| Bagging            | 68.00%   |
| SVM                | 68.00%   |

> XGBClassifier achieved the best performance overall.


## 7- Contact

- **Kaggle :** [Notebook](https://www.kaggle.com/code/alaaharb7/heart-failure-prediction)
- **LinkedIn:** [Alaa Harb](https://www.linkedin.com/in/alaa-harb7)
