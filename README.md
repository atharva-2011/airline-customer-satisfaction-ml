# ✈️ Airline Customer Satisfaction Prediction

## 📌 Project Overview
This project aims to predict whether an airline customer is **Satisfied** or **Dissatisfied** using machine learning techniques.  
The analysis focuses on identifying the key service and operational factors that influence customer satisfaction.

---

## 🔍 Dataset
The dataset contains airline customer information including:
- Demographic attributes
- Flight details
- Service quality ratings
- Operational delay metrics

The target variable represents overall customer satisfaction.


## 🧠 Methodology
The project follows a structured machine learning workflow:

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation analysis
   - Data quality checks

2. **Feature Selection**
   - Applied **ANOVA (F-test)** since all input features are numeric and the target variable is categorical
   - Identified statistically significant features influencing customer satisfaction

3. **Data Preprocessing**
   - Feature scaling using **StandardScaler**
   - Train-test split

4. **Model Building**
   - Implemented **Logistic Regression**
   - Hyperparameter tuning using GridSearchCV

5. **Model Evaluation**
   - Confusion Matrix
   - ROC Curve & AUC Score
   - Threshold optimization for better class separation

6. **Model Interpretation**
   - Analyzed Logistic Regression coefficients to understand feature impact


## 📊 Results & Insights
- Service quality features such as **Inflight Entertainment**, **Online Support**, **Seat Comfort**, and **Ease of Online Booking** were the strongest predictors of customer satisfaction.
- Operational delay features showed comparatively lower influence.
- Logistic Regression demonstrated strong discrimination capability based on ROC-AUC evaluation.


## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook


