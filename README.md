# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques.
The goal is to reduce financial losses for institutions while maintaining a smooth and secure customer experience.

The model focuses on optimizing the **F1-score**, ensuring a balance between:

* Detecting fraud cases (high recall)
* Minimizing false positives (good precision)

---

## 📊 Dataset

The dataset contains credit card transactions with labeled classes:

* 0 → Legitimate transaction
* 1 → Fraudulent transaction

The data is highly imbalanced, which makes fraud detection a challenging task.

---

## 🔹 Workflow

The project follows a clear data science workflow:

##  Data Cleaning

Checked dataset structure
Handled missing values
Removed duplicate records

## 🔍  Exploratory Data Analysis (EDA)

To better understand the dataset, the following analyses were performed:

* Descriptive statistics to explore data distribution
* Histograms for continuous features
* Bar plots to visualize class imbalance
* Box plots to compare feature distributions between fraud and non-fraud cases

---

##  Feature Engineering

* Created new features from raw data to help the model better understand patterns

---

##  🤖 Models Used

Several machine learning models were trained and compared:

* Random Forest
* XGBoost
* CatBoost

---

## ⚖️ Handling Imbalanced Data

* Applied **class weighting techniques** to improve fraud detection performance

---

## ⚙️ Model Optimization

* Hyperparameter tuning using **RandomizedSearchCV**
* Threshold tuning to improve classification performance

---

## 📈 Results

* Best model: **CatBoost**
* Achieved **F1-score: 0.88**

This demonstrates a strong balance between precision and recall in detecting fraudulent transactions.

---


## 🛠️ Technologies & Libraries

### 📊 Data Manipulation & Analysis

* Pandas
* NumPy

### 📈 Data Visualization

* Matplotlib
* Seaborn

### ⚙️ Preprocessing & Feature Engineering

* Scikit-learn (RobustScaler, StandardScaler)
* Custom Transformers (BaseEstimator, TransformerMixin)
* SciPy (statistical functions)

### ⚖️ Handling Imbalanced Data

* Imbalanced-learn (SMOTE, Pipeline)

### 🤖 Machine Learning Models

* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* XGBoost
* LightGBM
* CatBoost

### 🔍 Model Evaluation

* F1-score, Precision, Recall
* Confusion Matrix
* Cross-validation (StratifiedKFold)

### ⚙️ Model Optimization

* GridSearchCV
* RandomizedSearchCV

---


## ▶️ How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/islam_projects.git

# Navigate to the project folder
cd islam_projects

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
```

---

## 👤 Author

**Islam Soussi**
Aspiring Data Scientist & AI engineer | Big Data & Analytics

---

