# 🧠 Diabetes Prediction Using Machine Learning (CI512 Project)

A machine learning project using the **Pima Indians Diabetes Dataset** to predict whether a patient has diabetes. Built in **2021** for the CI512 – Intelligent Systems module, this project applies and compares multiple classification algorithms to identify the most accurate model.

---

## 📊 Dataset

- **Source**: National Institute of Diabetes and Digestive and Kidney Diseases  
- **Population**: Female patients over 21 years old of Pima Indian heritage  
- **Features**:
  - Pregnancies  
  - Plasma glucose concentration  
  - Diastolic blood pressure  
  - Triceps skin fold thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
  - Outcome (0 or 1)  

---

## 🤖 Algorithms Used

1. **K-Nearest Neighbors (KNN)**  
   - Predicts based on the distance to nearest data points.  
   - Chosen for its high accuracy with classification tasks.

2. **Decision Tree Classifier**  
   - Easy-to-interpret model using rule-based branching.  
   - Good for explaining predictions.

3. **Random Forest Classifier**  
   - Ensemble method combining multiple decision trees.  
   - Initially included, but later excluded due to inconsistent results.

4. **Multilayer Perceptron (MLP)**  
   - Neural network model with hidden layers.  
   - Provided the best prediction accuracy on this dataset.

5. **Stacking Classifier**  
   - Combines multiple models to improve prediction using meta-learning.

---

## 🧪 Evaluation Method

- **Data Cleaning**: Replaced 0 values with feature-wise mean (to handle missing values).  
- **Validation**: 10-fold cross-validation  
- **Split**: 70% Training, 30% Testing  
- **Visualization**: Line graphs for model accuracy comparison

---

## 📈 Results

- **Random Forest** was excluded due to poor alignment with other models.  
- **MLP (Multilayer Perceptron)** outperformed all other classifiers.  
- **Stacking** showed promise by combining model strengths.

---

## 🛠 Technologies

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- NumPy

---

## 👨‍💻 Developed By

**Vickshan Vicknakumaran**  
University of Brighton  
CI512 – Intelligent Systems (2021)

---
