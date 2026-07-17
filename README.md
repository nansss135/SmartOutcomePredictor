# Smart Outcome Predictor using Ensemble Learning

## 📌 Project Overview

This project implements multiple Ensemble Learning algorithms to predict student learning outcomes using machine learning.

The project performs both:

- Classification: Predict whether a student will complete the course (`completion_status`)
- Regression: Predict the student's final performance (`final_score`)

Several ensemble techniques are implemented and compared to identify the best-performing model.

---

## 🎯 Objectives

- Understand Ensemble Learning concepts.
- Predict course completion using classification models.
- Predict final score using regression models.
- Compare Bagging, Boosting, Voting, and Stacking techniques.
- Evaluate model performance using multiple metrics.
- Select the best ensemble model.

---

## 📂 Dataset Information

- Dataset Name: Smart Outcome Predictor Dataset
- Total Records: 5200
- Total Features: 19

### Classification Target
- `completion_status`

### Regression Target
- `final_score`

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- XGBoost
- Google Colab / Jupyter Notebook

---

## ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Imported required libraries
- Loaded Excel dataset
- Explored dataset using `info()` and `describe()`
- Checked missing values
- Encoded categorical features using LabelEncoder
- Applied StandardScaler
- Performed 80:20 Train-Test Split

---

## 🤖 Machine Learning Models

### Bagging

- Decision Tree Classifier
- Decision Tree Regressor
- Bagging Classifier
- Bagging Regressor

---

### Boosting

- AdaBoost Classifier
- AdaBoost Regressor
- Gradient Boosting Classifier
- Gradient Boosting Regressor
- LightGBM Classifier
- LightGBM Regressor
- XGBoost Classifier
- XGBoost Regressor

---

### Voting Ensemble

- Hard Voting Classifier
- Soft Voting Classifier
- Voting Regressor

---

### Stacking Ensemble

- Stacking Classifier
- Stacking Regressor

---

## 📊 Evaluation Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- AUC Score

### Regression

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Visualizations

- Completion Status Distribution
- Final Score Distribution
- Correlation Heatmap
- Confusion Matrix
- Accuracy Comparison
- R² Comparison
- ROC Curve
- Feature Importance Graph

---

## 📁 Project Structure

```
Smart_Outcome_Predictor/
│
├── Smart_Outcome_Predictor_Dataset_5200.xlsx
├── Ensemble_Learning.ipynb
├── README.md
├── Documentation.docx
└── requirements.txt
```

---

## 🚀 Workflow

```
Dataset
   │
   ▼
Data Understanding
   │
   ▼
Preprocessing
   │
   ▼
Feature Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Bagging
   │
   ▼
Boosting
   │
   ▼
Voting
   │
   ▼
Stacking
   │
   ▼
Model Evaluation
   │
   ▼
Performance Comparison
   │
   ▼
Best Model Selection
```

---

## 📌 Results

The performance of multiple ensemble learning algorithms was compared using classification and regression metrics.

The comparison demonstrated that advanced ensemble techniques such as Gradient Boosting, LightGBM, XGBoost, and Stacking generally achieved better prediction accuracy and model stability than a single Decision Tree model.

---

## 🎓 Learning Outcomes

Through this project, the following concepts were implemented and understood:

- Ensemble Learning
- Bagging
- Boosting
- Voting Ensemble
- Stacking Ensemble
- Classification
- Regression
- Model Evaluation
- Feature Scaling
- Data Preprocessing

---

## 📚 Future Improvements

- Hyperparameter Optimization
- Cross Validation
- Model Deployment using Streamlit or Flask
- Real-Time Student Performance Prediction
- Automated Model Selection

---

## 👨‍💻 Author

**Nandani Rajput**

B.Tech Computer Science Engineering

Machine Learning Project

GLS University

---

## ⭐ If you found this project useful, consider giving it a star!
