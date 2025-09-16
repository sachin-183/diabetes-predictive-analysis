# 🩺 Predictive Analysis in Diabetes

This project performs **predictive analysis on a diabetes dataset** using various machine learning techniques. The goal is to build a model that can predict whether a patient has diabetes based on diagnostic measurements.

---

## 📂 Dataset
- **File:** `diabetes.csv`  
- Contains patient medical records used to predict diabetes.  
- Common features:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Target: 1 = Diabetes, 0 = No Diabetes)

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data manipulation  
- [numpy](https://numpy.org/) – Numerical computations  
- [matplotlib](https://matplotlib.org/) – Visualizations  
- [seaborn](https://seaborn.pydata.org/) – Statistical plots  
- [scikit-learn](https://scikit-learn.org/stable/) – ML algorithms & evaluation  

---

## 📊 Project Workflow
1. **Import Libraries** – Load essential Python libraries.  
2. **Data Loading** – Read `diabetes.csv` into a DataFrame.  
3. **Data Cleaning** – Handle missing/null values.  
4. **Exploratory Data Analysis (EDA)**  
   - Statistical summary  
   - Correlation heatmap  
   - Distribution & relationship plots  
5. **Data Preprocessing**  
   - Feature scaling  
   - Train/test split  
6. **Model Training & Evaluation**  
   - Apply ML algorithms (e.g., Logistic Regression, Decision Tree, Random Forest, etc.)  
   - Evaluate models using:
     - Accuracy
     - Confusion Matrix
     - Precision, Recall, F1-score
7. **Model Saving**
   -Using pickle save the model

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sachin-183/diabetes-predictive-analysis.git
   cd diabetes-predictive-analysis
