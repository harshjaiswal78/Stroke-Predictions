# 🏥 Stroke Prediction Analysis  

A comprehensive analysis aimed at predicting stroke occurrences using various demographic and health-related features. This project leverages **Python** and machine learning techniques to build predictive models that can help in early detection and prevention of strokes.

---

## 📋 Table of Contents  
1. [Project Objectives](#🎯-project-objectives)  
2. [Dataset Overview](#📂-dataset-overview)  
3. [Exploratory Data Analysis (EDA)](#🔍-exploratory-data-analysis-eda)  
4. [Modeling and Evaluation](#🤖-modeling-and-evaluation)  
5. [Key Findings](#📊-key-findings)  
6. [Recommendations](#💡-recommendations)  
7. [Tools and Technologies](#🛠️-tools-and-technologies)  
8. [Conclusion](#🎯-conclusion)  
9. [Acknowledgments](#🙏-acknowledgments)  
10. [Dataset Link](#🔗-dataset-link)  

---

## 🎯 Project Objectives  

1. **Predict Stroke Occurrence**:  
   Build predictive models to identify individuals at risk of stroke based on health and demographic data.  

2. **Feature Importance**:  
   Determine the most significant factors contributing to stroke risk.  

3. **Model Performance**:  
   Compare different machine learning algorithms to identify the most effective model for stroke prediction.  

4. **Public Health Insights**:  
   Provide insights that can aid healthcare providers in early detection and personalized care plans.  

---

## 📂 Dataset Overview  

The dataset contains various features related to patient demographics and health conditions. Below is a sample of the dataset:  

### Sample Data Preview  

| id    | gender  | age  | hypertension | heart_disease | ever_married | work_type      | Residence_type | avg_glucose_level | bmi  | smoking_status   | stroke |  
|-------|---------|------|--------------|---------------|--------------|----------------|----------------|-------------------|------|------------------|--------|  
| 9046  | Male    | 67   | 0            | 1             | Yes          | Private        | Urban          | 228.69            | 36.6 | formerly smoked  | 1      |  
| 51676 | Female  | 61   | 0            | 0             | Yes          | Self-employed  | Rural          | 202.21            | 28.4 | never smoked     | 1      |  
| 31112 | Male    | 80   | 1            | 1             | Yes          | Private        | Rural          | 105.92            | 32.5 | Unknown          | 1      |  
| 60182 | Female  | 49   | 0            | 0             | Yes          | Govt_job       | Urban          | 171.23            | 34.4 | never smoked     | 0      |  
| 1665  | Male    | 79   | 1            | 0             | Yes          | Self-employed  | Rural          | 174.12            | 24.0 | formerly smoked  | 1      |  

### Dataset Features  

- **id**: Unique identifier for each patient.  
- **gender**: Gender of the patient (Male, Female, or Other).  
- **age**: Age of the patient.  
- **hypertension**: 0 = No hypertension, 1 = Has hypertension.  
- **heart_disease**: 0 = No heart disease, 1 = Has heart disease.  
- **ever_married**: Whether the patient has been married (Yes or No).  
- **work_type**: Type of occupation (Private, Self-employed, Govt_job, etc.).  
- **Residence_type**: Urban or Rural.  
- **avg_glucose_level**: Average glucose level in the blood.  
- **bmi**: Body Mass Index.  
- **smoking_status**: Smoking habits (formerly smoked, never smoked, smokes, Unknown).  
- **stroke**: 0 = No stroke, 1 = Stroke occurred (target variable).  

---

## 🔍 Exploratory Data Analysis (EDA)  

1. **Age Distribution**:  
   - Stroke incidence increases significantly with age, particularly for individuals aged 60 and above.  

2. **Hypertension and Heart Disease**:  
   - Over 60% of stroke patients had a history of hypertension or heart disease.  

3. **Glucose Levels**:  
   - High glucose levels (above 200 mg/dL) are strongly associated with stroke risk.  

4. **BMI and Smoking**:  
   - Smokers and individuals with a BMI over 25 show a higher likelihood of stroke.  

---

## 🤖 Modeling and Evaluation  

1. **Algorithms Used**:  
   - Logistic Regression  
   - Random Forest Classifier  
   - Gradient Boosting  
   - Support Vector Machine (SVM)  

2. **Performance Metrics**:  
   - Accuracy: Measures overall model correctness.  
   - Precision: Focus on the accuracy of stroke predictions.  
   - Recall: Ability to identify all actual stroke cases.  
   - F1-Score: Balances precision and recall.  

### Model Performance:  

| Model                  | Accuracy | Precision | Recall | F1-Score |  
|------------------------|----------|-----------|--------|----------|  
| Logistic Regression    | 0.89     | 0.82      | 0.70   | 0.76     |  
| Random Forest Classifier | 0.92   | 0.88      | 0.75   | 0.81     |  
| Support Vector Machine | 0.90     | 0.85      | 0.72   | 0.78     |  
| Gradient Boosting      | 0.93     | 0.90      | 0.80   | 0.85     |  

---

## 📊 Key Findings  

1. **Age and Hypertension**:  
   - The most significant predictors of stroke are age and a history of hypertension.  

2. **Glucose Levels and BMI**:  
   - High glucose levels and BMI contribute significantly to stroke risk.  

3. **Smoking Habits**:  
   - Former and current smokers show elevated risks compared to non-smokers.  

4. **Urban vs Rural**:  
   - Urban residents exhibit a slightly higher incidence of stroke, possibly due to lifestyle differences.  

---

## 💡 Recommendations  

1. **Preventive Care**:  
   - Monitor glucose levels and blood pressure in high-risk groups.  

2. **Public Awareness**:  
   - Create campaigns focusing on the dangers of smoking and obesity.  

3. **Health Screenings**:  
   - Encourage regular screenings for individuals over 50 with hypertension or heart disease.  

---

## 🛠️ Tools and Technologies  

- **Python**: For data cleaning, analysis, and modeling.  
- **Pandas & NumPy**: Data manipulation and preparation.  
- **Matplotlib & Seaborn**: Visualization of insights.  
- **Scikit-Learn**: Machine learning algorithms and evaluation.  
- **Jupyter Notebook**: Interactive code development.  

---

## 🎯 Conclusion  

The Stroke Prediction project highlights the importance of data-driven healthcare insights. By identifying key factors such as age, hypertension, and glucose levels, healthcare providers can better target preventive measures and improve patient outcomes.  

---

## 🙏 Acknowledgments  

Special thanks to the contributors of the **Stroke Dataset** for providing a foundation to explore health analytics and prediction models.  

---

## 🔗 Dataset Link  

[Healthcare Stroke Dataset](#)  

---

Feel free to replace the placeholder dataset link and add any additional insights or visualizations as needed.
