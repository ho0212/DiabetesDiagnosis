# Diabetes Prediction using R

This project builds a binary classification model to predict whether a person is likely to have diabetes using the publicly available dataset from Kaggle.

The goal is to explore the data, apply preprocessing, train predictive models (e.g., logistic regression, decision tree), and evaluate model performance using appropriate metrics.

---

## Dataset

- Source: [Kaggle – Diabetes Dataset by aravindpcoder](https://www.kaggle.com/datasets/aravindpcoder/diabetes-dataset)
- Features include: Sugar Level Blood, Age, Gender, Creatinine ratio(Cr), Body Mass Index (BMI), Urea, Cholesterol (Chol), Fasting lipid profile, including total, LDL, VLDL, Triglycerides(TG) and HDL Cholesterol , HBA1C, Class (the patient's diabetes disease class may be Diabetic, Non-Diabetic, or Predict-Diabetic).
- Target variable: `Class` (N = Non-Diabetic, Y = Diabetic, P = Predict-Diabetic)

See `data/README.md` for dataset details.

---

## Model Workflow

1. **Data Exploration**
   - Summary stats, visualizations
2. **Preprocessing**
   - Handling missing values
   - Normalization / scaling
3. **Modeling**
   - Logistic Regression
   - Decision Tree
   - (optional: Random Forest or SVM)
4. **Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1 Score

---

## Model Evaluation

Two models were trained and evaluated on the diabetes dataset using a confusion matrix and performance metrics:

| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | **97.47%** |
| Logistic Regression | **92.93%** |

Additional metrics such as precision, recall, and F1-score are visualized in Figures 7–10 in the project report.


---

##  Repository Structure

| Folder        | Description                              |
|---------------|------------------------------------------|
| `data/`       | Contains raw Kaggle dataset and README   |
| `scripts/`    | Contains R script(s) for modeling        |
| `reports/`    | Final report or write-up (PDF/Markdown)  |
