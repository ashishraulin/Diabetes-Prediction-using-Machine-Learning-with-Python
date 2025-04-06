# Diabetes Prediction using Machine Learning (SVM)

This project uses machine learning to predict whether a person is diabetic or not using medical features. We implemented a Support Vector Machine (SVM) model in Python to train on the dataset and evaluate its performance.

## 📌 Project Objective

To build a classification system using machine learning that predicts diabetes in individuals based on diagnostic health features.

## 🧠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Google Colab

## 📊 Dataset

We use the **Pima Indians Diabetes Dataset**, which includes 768 records of female patients aged 21 years and older of Pima Indian heritage. Each record contains several medical predictor variables and one target variable (`Outcome`) indicating if the patient has diabetes (`1`) or not (`0`).

### 📄 Features:

- **Pregnancies**
- **Glucose**
- **BloodPressure**
- **SkinThickness**
- **Insulin**
- **BMI** (Body Mass Index)
- **DiabetesPedigreeFunction**
- **Age**
- **Outcome** (Target variable)

## 🚀 How to Run

1. Clone this repository or download the Jupyter/Colab notebook.
2. Upload `diabetes.csv` in the same directory or to your Google Colab environment.
3. Run the notebook to train the model and evaluate its performance.

## 📈 Model Used

- **Model:** Support Vector Machine (SVM)
- **Accuracy:** ~80% on test data
- **Evaluation Metrics:**
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## 📷 Sample Output

![Confusion Matrix](images/confusion_matrix.png)


