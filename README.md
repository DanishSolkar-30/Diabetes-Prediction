# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Project Overview
This project predicts whether a patient is likely to have diabetes based on various medical attributes using the **Logistic Regression** algorithm from Scikit-learn. The model is trained on a diabetes dataset and classifies patients as either **Diabetic** or **Non-Diabetic**. It also allows users to enter their own medical details to receive a prediction.

---

## 🚀 Features
- Loaded and preprocessed the diabetes dataset.
- Split the dataset into training and testing sets.
- Trained a Logistic Regression model using Scikit-learn.
- Evaluated the model using Accuracy Score.
- Displayed the Classification Report and Confusion Matrix.
- Accepted user input for medical parameters.
- Predicted whether the patient is diabetic or non-diabetic.

---

## ⚙️ How the Program Works
The program starts by loading the diabetes dataset using Pandas and separating the input features from the target variable. The dataset is then divided into training and testing sets using Scikit-learn's `train_test_split` function. A Logistic Regression model is trained on the training data to learn patterns associated with diabetes. After training, the model is evaluated using metrics such as Accuracy Score, Classification Report, and Confusion Matrix. Finally, the program accepts medical information from the user and predicts whether the patient is likely to have diabetes.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Logistic Regression

---

## 📂 Dataset
The project uses the **Pima Indians Diabetes Dataset**, which contains medical information about patients.

### Input Features
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target
- **0** → Non-Diabetic
- **1** → Diabetic

---

## 📊 Model Evaluation
The model is evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## ▶️ How to Run
1. Clone this repository.
2. Install the required libraries.
3. Place the dataset (`diabetes.csv`) in the project folder.
4. Run the Python file.

```bash
python diabetes_prediction.py
```

5. Enter the required medical details when prompted.
6. View the prediction result.

---

## 📚 What I Learned
- Data preprocessing using Pandas.
- Binary Classification using Logistic Regression.
- Splitting datasets into training and testing sets.
- Evaluating classification models.
- Making predictions using trained Machine Learning models.
- Building an end-to-end Machine Learning project with Python.

---

## 📜 License
This project is created for educational purposes.
