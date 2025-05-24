# Breast-Cancer-Detection-using-Machine-Learning

This project implements a machine learning pipeline to predict breast cancer diagnosis (benign or malignant) based on features extracted from breast mass images. It aims to support early diagnosis and improve decision-making in medical analysis.

## 🧪 Dataset

The project uses the Breast Cancer Wisconsin (Diagnostic) dataset, which includes:

- **Features**: Radius, texture, perimeter, area, smoothness, etc.
- **Target**: Diagnosis (`M` = Malignant, `B` = Benign)

These features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📊 Workflow

1. **Data Preprocessing**:
   - Handled missing values
   - Label encoded target variable
   - Scaled features

2. **Exploratory Data Analysis (EDA)**:
   - Feature distributions and correlations
   - Class balance

3. **Model Training**:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Random Forest

4. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix
   - ROC-AUC Curve

## 📈 Results

- Compared performance of multiple classifiers
- Selected the best model based on accuracy and AUC score
- Achieved high accuracy in detecting malignant vs. benign cases

