# 🩺 Heart Stroke Prediction

This data science project aims to **predict the likelihood of a patient experiencing a stroke** based on various input parameters such as gender, age, health conditions, and lifestyle habits.  
The project uses **machine learning techniques** to analyze patient data and build a predictive model.

---

## 📊 Dataset Information
The dataset contains patient information required to predict the occurrence of a stroke.  
Each row represents a patient and includes the following attributes:

- **id**: Unique identifier  
- **gender**: "Male", "Female", or "Other"  
- **age**: Age of the patient  
- **hypertension**: 0 → No hypertension, 1 → Has hypertension  
- **heart_disease**: 0 → No heart disease, 1 → Has heart disease  
- **ever_married**: "No" or "Yes"  
- **work_type**: "Children", "Govt_job", "Never_worked", "Private", "Self-employed"  
- **Residence_type**: "Rural" or "Urban"  
- **avg_glucose_level**: Average glucose level in blood  
- **bmi**: Body Mass Index  
- **smoking_status**: "Formerly smoked", "Never smoked", "Smokes", "Unknown"  
- **stroke**: 1 → Patient had a stroke, 0 → Did not have a stroke  

---

## 🌍 Context
According to the **World Health Organization (WHO)**, stroke is the **second leading cause of death worldwide**, responsible for about **11% of total deaths**.  

By predicting the risk of stroke early, healthcare providers can take **preventive measures** to reduce the incidence and impact of stroke.

---

## ⚙️ Project Workflow
1. **Data Collection** – Import dataset  
2. **Data Preprocessing** – Handle missing values, encode categorical variables, feature scaling  
3. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and patterns  
4. **Model Building** – Train ML models (e.g., Logistic Regression, Random Forest, XGBoost)  
5. **Model Evaluation** – Compare accuracy, precision, recall, F1-score, ROC-AUC  
6. **Prediction** – Use the best model to predict stroke risk  

---

## 🚀 Technologies Used
- Python 🐍  
- Pandas & NumPy – Data manipulation  
- Matplotlib & Seaborn – Data visualization  
- Scikit-learn – Machine learning models  
- Jupyter Notebook – Development & analysis  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
