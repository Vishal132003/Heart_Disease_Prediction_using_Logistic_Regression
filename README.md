# 🫀 Heart Disease Prediction using Logistic Regression

## 📘 Overview
This project aims to predict whether a person is likely to have heart disease based on medical attributes using the **Logistic Regression** algorithm. It performs binary classification to determine if a person is at risk (1) or not (0).

---

## 📊 Dataset
Dataset used: [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)

**Features include:**
- `age` — Age of the person  
- `sex` — Gender (1 = male, 0 = female)  
- `cp` — Chest pain type  
- `trestbps` — Resting blood pressure  
- `chol` — Cholesterol level  
- `fbs` — Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- `restecg` — Resting electrocardiographic results  
- `thalach` — Maximum heart rate achieved  
- `exang` — Exercise-induced angina (1 = yes, 0 = no)  
- `oldpeak` — ST depression induced by exercise  
- `slope` — Slope of the peak exercise ST segment  
- `ca` — Major vessels colored by fluoroscopy  
- `thal` — Thalassemia  
- `target` — 1 = Heart disease, 0 = No heart disease  

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧠 Model Used
- **Logistic Regression**  
Used for binary classification (Heart Disease: Yes/No).

---

## 🔍 Steps Performed
1. Importing required libraries  
2. Loading and exploring the dataset  
3. Data preprocessing  
   - Handling missing values  
   - Checking and removing duplicates  
   - Feature scaling  
4. Splitting the dataset into **training** and **testing** sets  
5. Training the **Logistic Regression** model  
6. Evaluating performance using Accuracy, Confusion Matrix, and Classification Report  
7. Predicting results for new data  

---

## 💡 Example Prediction
```python
prediction = model.predict(new_data)
if prediction[0] == 1:
    print("🫀 The person is likely to have heart disease.")
else:
    print("✅ The person is unlikely to have heart disease.")
