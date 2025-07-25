# 🫀 Cardiovascular Disease Risk Prediction
This project uses patient health data to predict the risk of cardiovascular disease. The goal is to demonstrate how machine learning can assist in early detection and clinical decision-making by analyzing features like blood pressure, cholesterol, and lifestyle factors.

## 📁 Dataset
**Source**: Public dataset (Kaggle) - Manually uploaded  
**Files Used**:
- `cardiovascular_disease_dataset.csv` (raw data)
- `cleaned_cardiovascular_disease_dataset.csv` (preprocessed for ML)

### Key Features:
- Demographics: Age, Gender
- Vital Signs: Height, Weight, Blood Pressure (ap_hi, ap_lo)
- Lab Results: Cholesterol, Glucose
- Lifestyle: Smoking, Alcohol Intake, Physical Activity
- Labels: Cardiovascular disease presence (0 or 1)
- Engineered Features: BMI, Age in years

## 🔍 Project Workflow
- Load and clean raw dataset
- Feature engineering (e.g., BMI calculation, age transformation)
- Exploratory Data Analysis (EDA) with plots
- Model training and evaluation:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - K-Nearest Neighbors (KNN)
- Visualize model performance with confusion matrices and accuracy metrics

## 📊 Key Insights
- Correlation of features with cardiovascular risk
- Feature importance scores (especially from tree-based models)
- Model comparison across accuracy and precision
- Relationship of BMI, age, and lifestyle habits with heart disease

## 🛠 Tools & Libraries
- Python 3.x
- pandas & numpy for data preprocessing
- scikit-learn for ML models and evaluation
- xgboost for gradient boosting
- matplotlib & seaborn for EDA and visualization

## 🧠 How to Use
1. Clone this repository
2. Make sure both CSVs are in the same folder
3. Open `Predicting_cardiovascular_disease_risk.ipynb` using Jupyter or VS Code
4. Run the notebook to:
   - Explore the dataset
   - Train models
   - Visualize results

## ✅ Output Preview
📈 Visualizations include:
- Correlation Heatmaps
- Feature Importance Bar Charts
- Confusion Matrices
- Accuracy Comparisons by Model

## 💡 Author
Santhakumar Ramesh  
MPS in Data Science and Applications  
University at Buffalo  
GitHub: [Santhakumarramesh](https://github.com/Santhakumarramesh)

---

*This project is part of an academic exercise demonstrating applied machine learning for healthcare data.*
