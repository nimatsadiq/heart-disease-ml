# 🩺 Heart Disease Risk Prediction using Machine Learning

### Overview
This project applies **Machine Learning (ML)** to predict whether a patient is at risk of heart disease using key health indicators such as age, cholesterol, heart rate, and chest pain type.  
It demonstrates how data science and AI can support **early diagnosis** and **health decision-making**, aligning with health informatics research goals.


### Project Objectives
- Explore and understand the **Heart Disease dataset**
- Identify which features (risk factors) are most related to heart disease
- Build a **predictive ML model** using Logistic Regression
- Evaluate its accuracy and visualize important insights


### Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**


### Dataset
Dataset source: [Kaggle – Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
The dataset contains **1,025 patient records** and **14 features**, including:
- `age` – age of the patient  
- `sex` – gender (1 = male, 0 = female)  
- `cp` – chest pain type  
- `chol` – cholesterol level  
- `thalach` – maximum heart rate achieved  
- `exang` – exercise-induced angina  
- `target` – diagnosis (1 = disease, 0 = no disease)


### Exploratory Data Analysis (EDA)
Key insights:
- No missing or null values were found in the dataset.
- Around **50% of patients** showed signs of heart disease.
- Strong correlations found between:
  - Chest pain type (`cp`)
  - Exercise-induced angina (`exang`)
  - Maximum heart rate (`thalach`)
  - ST depression (`oldpeak`)
- Cholesterol and fasting blood sugar had weak correlation with heart disease.

Visualizations included:
- Distribution plots  
- Correlation heatmap  
- Feature importance chart  


### Model Training
A **Logistic Regression model** was trained and evaluated.

**Results:**
| Metric | Score |
|---------|-------|
| Accuracy | 79.5% |
| Precision | ~80% |
| Recall | ~79% |
| F1-score | ~79% |

**Top Predictive Features:**
1. Chest Pain Type (`cp`)  
2. Exercise-Induced Angina (`exang`)  
3. Maximum Heart Rate (`thalach`)  
4. ST Depression (`oldpeak`)  
5. Slope of Peak Exercise Segment (`slope`)


### Interpretation
The model can correctly predict **about 8 out of 10 patients** based on their health features.  
This aligns with real-world understanding — chest pain and heart rate responses are key indicators of cardiac health.


### Conclusion
This mini project demonstrates how simple ML methods can assist in **predicting heart disease risk**, showcasing the value of **AI in healthcare**.  
It highlights the potential for:
- Data-driven early diagnosis  
- Improved decision-making for clinicians  
- Foundational insights for future research in health informatics  


### 📁 Repository Structure
