# 🫀 Heart Disease Prediction

This project uses machine learning techniques to predict the presence of heart disease based on medical diagnostic data. It involves data preprocessing, visualization, and model building to evaluate prediction performance.

## 🧰 Tools & Libraries Used

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn

## 📝 Dataset Overview

The dataset is sourced from the UCI Machine Learning Repository and contains 303 records with 14 attributes. It includes demographic and medical features such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia
- **Target Variable**: Presence (1) or absence (0) of heart disease

## 📊 Exploratory Data Analysis

The notebook includes:
- Descriptive statistics of the dataset
- Correlation heatmaps
- Count plots and distribution plots
- Boxplots for outlier detection

## 🤖 Machine Learning Models

The following algorithms were explored:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

## 📈 Evaluation Metrics

Model performance was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC Curve

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook "Heart Disease Prediction.ipynb"
   ```

## 📌 Future Enhancements

* Deploy the model using Streamlit or Flask for a web-based prediction tool
* Add feature engineering and hyperparameter tuning
* Use cross-validation for robust model evaluation

## 🙋‍♂️ Author

**PIYUSH KUMAR ROY**
