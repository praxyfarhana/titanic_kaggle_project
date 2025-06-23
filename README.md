🛳️ Titanic Survival Prediction - Kaggle Competition
Welcome to my machine learning project for the Kaggle Titanic - Machine Learning from Disaster competition. This project involves predicting survival outcomes for passengers on the Titanic using classification models and data analysis techniques.

📁 Project Structure

Data Sets
train.csv
test.csv

🎯 Objective
To build a machine learning model that predicts whether a given passenger survived the Titanic disaster, based on features like age, gender, class, fare, and family relations.

📊 Dataset
Train: 891 records with labels (Survived)

Test: 418 records without labels

Kaggle Titanic Dataset

🧼 Key Steps
1. Data Cleaning
Imputed missing Age, Embarked

Dropped Cabin due to many missing values

Converted categorical variables

2. Exploratory Data Analysis (EDA)
Survival analysis by gender, class, age group

Visualizations using seaborn and matplotlib

3. Feature Engineering
FamilySize = SibSp + Parch + 1

Extracted Title from passenger names

4. Model Building
Algorithm Tested:

Random Forest Classifier

5. Evaluation
Cross-validation accuracy

Confusion matrix & feature importance

Best model: Random Forest (~82% accuracy)

📌 Results & Insights
Female passengers had higher survival rates

1st-class passengers were more likely to survive

Feature engineering boosted model performance

Github link: https://github.com/praxyfarhana/titanic_kaggle_project/blob/main/survival-prediction.ipynb

📧 Contact
Farhana Agufa
📬 Email: praxyfarhana@example.com
🌍 Nairobi, Kenya
