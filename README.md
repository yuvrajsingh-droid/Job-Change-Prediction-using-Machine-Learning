# 💼 Job Change Prediction using Machine Learning

## 📌 Overview
This repository contains a machine learning project that predicts whether a candidate is likely to switch jobs based on their personal, educational, and professional details.  
The dataset (`aug_train.csv`) is used to train and test different classification models, and the notebook (`trainn.ipynb`) walks through the full analysis pipeline.

---

## 📊 Dataset
- **Rows:** 19,158  
- **Columns:** 14  
- **Target Variable:** `target`  
  - `0` → Candidate not looking for a job change  
  - `1` → Candidate is looking for a job change  

### Features:
- `gender`, `education_level`, `major_discipline`  
- `relevent_experience`, `experience`, `last_new_job`  
- `company_size`, `company_type`  
- `city`, `city_development_index`  
- `training_hours`  

---

## ⚙️ Project Workflow
1. **Data Exploration & Cleaning**  
   - Handle missing values  
   - Encode categorical variables  
   - Feature scaling  

2. **EDA (Exploratory Data Analysis)**  
   - Visualizing distributions and correlations  
   - Insights into job change patterns  

3. **Modeling**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost / LightGBM  
   - Model evaluation using Accuracy, Precision, Recall, F1, and ROC-AUC  

4. **Results**  
   - Performance comparison between models  
   - Key factors influencing job change  

---


 
