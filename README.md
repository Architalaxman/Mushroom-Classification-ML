# 🍄 Mushroom Classification ML Project

## 📌 Project Overview
This project focuses on building a Machine Learning model to classify mushrooms as edible or poisonous based on their physical characteristics. The dataset includes various features such as cap shape, color, gill structure, stem properties, and habitat.

---

## 🎯 Objective
To develop a classification model that accurately predicts the class of mushrooms using supervised learning techniques.

---

## 📊 Dataset Features
- Cap: diameter, shape, surface, color
- Gill: attachment, spacing, color
- Stem: height, width, root, surface, color
- Veil and Ring features
- Spore print color
- Habitat and season

**Target Variable:** `class`

---

## 🧹 Data Preprocessing
- Handled missing values using median (numerical) and mode (categorical)
- Removed duplicate records
- Converted data types appropriately
- Encoded categorical variables using OneHotEncoder
- Scaled numerical features using StandardScaler

---

## ⚙️ Machine Learning Pipeline
- Used `ColumnTransformer` for preprocessing
- Applied `RandomOverSampler` to handle class imbalance
- Built pipelines using `sklearn` and `imblearn`

---

## 🤖 Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest (Best Performing)

---

## 🔍 Model Optimization
- Hyperparameter tuning using `GridSearchCV`
- Cross-validation (5-fold) for performance evaluation

---

## 📈 Results
- Random Forest achieved the highest accuracy
- Model performance validated using cross-validation
- Balanced dataset improved classification performance

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn

---

## 📂 Project Structure
Mushroom-Classification/
│── data.csv
│── cleaned_data.csv
│── notebook.ipynb
│── mushroom_model.pkl
│── README.md
