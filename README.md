# Indian Liver Patient Prediction

## 📌 Project Overview

This project focuses on predicting liver disease in patients using machine learning algorithms. The dataset includes medical information about patients, and the goal is to develop a model that accurately identifies individuals with liver disease. The project involves data analysis, model training, evaluation, and deriving key insights to aid in early disease detection.

## 🔊 Dataset Information

- *Filename*: Indian Liver Patient Dataset (ILPD).csv
- *Features*:
  - Age: Age of the patient
  - Gender: Male/Female
  - Total_Bilirubin: Total bilirubin level in the blood
  - Direct_Bilirubin: Direct bilirubin level
  - Alkaline_Phosphotase: Alkaline phosphotase enzyme level
  - Alamine_Aminotransferase: Enzyme level (ALT)
  - Aspartate_Aminotransferase: Enzyme level (AST)
  - Total_Proteins: Total protein level in the blood
  - Albumin: Albumin level in the blood
  - Albumin_and_Globulin_Ratio: Ratio between albumin and globulin
  - Dataset: Target variable (1: Liver disease, 2: No liver disease)

## 🔍 Exploratory Data Analysis (EDA)

- *Data Cleaning*:
  - Handled missing values in Albumin_and_Globulin_Ratio.
  - Categorical encoding for Gender (Male: 1, Female: 0).
- *Feature Engineering*:
  - Created interaction terms between significant biochemical attributes.
  - Standardized numerical columns to improve model performance.
- *Visualizations*:
  - Histograms to observe feature distributions.
  - Box plots to identify outliers.
  - Correlation heatmaps to detect relationships between features.
  - Count plots to visualize the distribution of liver disease status across gender and age groups.

## 🤖 Machine Learning Models Used

Multiple machine learning models were trained and evaluated:

1. *Logistic Regression*
2. *Decision Tree Classifier*
3. *Random Forest Classifier*
4. *Gradient Boosting Classifier*
5. *XGBoost Classifier*
6. *K-Nearest Neighbors (KNN) Classifier*

## 📈 Model Evaluation Metrics

The models were assessed using:
- *Accuracy Score*
- *Precision*
- *Recall*
- *F1-Score*
- *Confusion Matrix*
- *ROC-AUC Score*

## 🛠 Hyperparameter Tuning
- Utilized *GridSearchCV* and *RandomizedSearchCV* for optimizing hyperparameters.
- Focused on reducing overfitting and improving model generalization.

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
bash
pip install -r requirements.txt


### 2️⃣ Run the Jupyter Notebook
bash
jupyter notebook PRCP-1007-LiverPatientPred.ipynb


## 📌 Key Insights

- *Age and Gender Impact*: Older individuals and males showed a higher likelihood of liver disease.
- *Bilirubin Levels*: Elevated levels of Total_Bilirubin and Direct_Bilirubin were strongly correlated with liver disease presence.
- *Enzyme Levels*: Higher levels of Alkaline_Phosphotase and Aspartate_Aminotransferase were significant indicators.
- *Model Performance: The **Random Forest* and *XGBoost* classifiers outperformed others in accuracy and ROC-AUC scores.
- *Early Detection*: Insights from this analysis can be leveraged for early detection and preventive healthcare strategies.


## 📄 Conclusion

This project successfully developed machine learning models for predicting liver disease based on clinical data. The findings can aid healthcare professionals in early diagnosis and intervention, potentially improving patient outcomes. Continuous model refinement and integration with real-time data can further enhance prediction accuracy.

---
