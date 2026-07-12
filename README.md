# Adult Census Income Prediction Using Machine Learning

A comparative machine learning project that predicts whether an individual's annual income is **greater than \$50,000** or **less than or equal to \$50,000** using the Adult Census Income Dataset.

The project demonstrates a complete end-to-end machine learning workflow including data preprocessing, exploratory data analysis (EDA), model training, evaluation, comparison, feature importance analysis, unsupervised learning, and best model selection.

---

## 📌 Project Objectives

- Explore and understand the Adult Census Income dataset.
- Perform data cleaning and preprocessing.
- Compare multiple supervised machine learning algorithms.
- Evaluate model performance using standard classification metrics.
- Apply K-Means clustering as an unsupervised learning technique.
- Identify the most important features influencing income prediction.
- Select and save the best-performing model.

---

## 📂 Dataset

**Dataset:** Adult Census Income Dataset

**Objective**

Predict whether a person's annual income is:

- <=50K
- >50K

based on demographic and employment-related attributes.

**Dataset Source**

- https://archive.ics.uci.edu/dataset/2/adult
- https://www.kaggle.com/datasets/uciml/adult-census-income

---

## 📊 Dataset Features

Some of the key attributes include:

- Age
- Workclass
- Education
- Education-num
- Marital-status
- Occupation
- Relationship
- Race
- Sex
- Capital-gain
- Capital-loss
- Hours-per-week
- Native-country

**Target Variable**

Income

- " <=50K "
- " >50K "

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

# 📈 Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Exploration
      │
      ▼
Missing Value Handling
      │
      ▼
Duplicate Removal
      │
      ▼
One-Hot Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
      │
      ▼
Model Comparison
      │
      ▼
Best Model Selection
      │
      ▼
Model Saving
```

---

# 🤖 Supervised Learning Algorithms

The following supervised learning algorithms were implemented and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest
- Linear Regression (Baseline)

---

# 🔍 Unsupervised Learning

The project also demonstrates:

- K-Means Clustering

Evaluation metrics:

- Adjusted Rand Index (ARI)
- Normalized Mutual Information (NMI)

---

# 📊 Exploratory Data Analysis

The notebook includes:

- Dataset Overview
- Missing Value Analysis
- Duplicate Detection
- Income Distribution
- Histograms
- Boxplots
- Correlation Heatmap

---

# ⚙ Data Preprocessing

The preprocessing pipeline includes:

- Missing value imputation
- Duplicate removal
- One-Hot Encoding
- Standard Scaling
- ColumnTransformer
- Train-Test Split

---

# 📉 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Classification Report
- Precision-Recall Curve

---

# 📌 Feature Importance

Feature importance was generated using the Random Forest model to identify the most influential variables affecting income prediction.

Examples include:

- Education
- Capital Gain
- Hours per Week
- Age
- Occupation

---

# 📊 Model Comparison

All supervised learning models were compared using identical training and testing datasets to ensure a fair evaluation.

The best-performing model was selected based on overall classification performance.

---

# 💾 Saved Model

The project saves the best-performing trained model together with the preprocessing pipeline using Joblib.

Example:

```
Models/
│
├── best_model.pkl
├── preprocessor.pkl
```

or

```
adult_income_classifier.pkl
```

---

# 📁 Project Structure

```
Adult-Income-Prediction/
│
├── Adult_Income_Prediction.ipynb
├── README.md
├── Figures/
├── Tables/
├── Models/
│
├── requirements.txt
└── LICENSE
```

---

# 📷 Outputs

The notebook generates:

- Data exploration visualizations
- Confusion matrices
- ROC Curves
- Precision-Recall Curves
- Feature Importance
- PCA Visualization for K-Means
- Model comparison charts

---

# 🚀 Future Improvements

Possible enhancements include:

- Hyperparameter tuning
- Cross-validation
- XGBoost
- LightGBM
- CatBoost
- Model deployment using Flask or FastAPI
- Interactive web application

---

# 📚 References

- UCI Machine Learning Repository
- Scikit-learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation

---

Machine Learning | Data Science | Artificial Intelligence