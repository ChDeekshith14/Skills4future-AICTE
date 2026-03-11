## 🔮 EV Adoption Forecasting System

This project predicts future electric vehicle (EV) adoption trends using historical vehicle registration data from Washington State.
The system uses machine learning regression models to forecast EV growth and provides an interactive dashboard built with Streamlit to visualize predictions.

The goal is to help urban planners, policymakers, and infrastructure developers anticipate EV growth and plan charging infrastructure accordingly.

![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/eac01179b35a8addcca069daa48d6ba310a05134/ev-car-factory.jpg)

---

## 📌 Problem Statement

- As electric vehicle adoption increases rapidly, cities must prepare the required infrastructure such as EV charging stations.

- Poor forecasting can cause:

- Charging infrastructure shortages

- Increased waiting times for EV users

- Slower EV adoption due to poor accessibility

- The challenge is to predict future EV adoption trends based on historical data.

---

## 🎯 Project Goal

Build a machine learning forecasting model that predicts the future number of electric vehicles using historical EV registration data.

**The system should:**

- Analyze historical EV trends

- Forecast EV growth for future months

- Allow county-level comparison of EV adoption

- Provide interactive visualization through a web application

---

## 🛠 Technologies Used

- Programming Language - Python
- Libraries
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Streamlit
- TensorFlow
- Joblib
- Machine Learning
- RandomForestRegressor
- RandomizedSearchCV (hyperparameter tuning)
- Data Processing
- Label Encoding
- Feature Engineering
- Time-based transformations

----

## 📦 Required Dependencies

numpy==1.26.4
pandas==1.5.3
scikit-learn==1.6.1
scipy==1.15.2
statsmodels==0.14.4
streamlit==1.44.1
tensorflow==2.19.0

---

## ⚙ Model Training Workflow

Step 1 — Load dataset
Step 2 — Preprocess and clean data
Step 3 — Encode categorical features
Step 4 — Create lag and trend features
Step 5 — Train Random Forest model
Step 6 — Evaluate model performance
Step 7 — Save trained model using joblib

---

## 📊 Visualization

**The application generates:**

- Cumulative EV growth charts

- Historical vs forecasted trends

- Multi-county comparison graphs

- Charts are generated using Matplotlib and displayed inside Streamlit.

---

## 🚀 Forecast Horizon

The model predicts EV adoption for the next 36 months (3 years).

Predictions are generated iteratively by using previous predictions as lag inputs.

---

## 📌 Final Output

**The application displays:**

- Historical EV adoption

- Forecasted EV growth

- County comparison trends

- Percentage EV growth prediction

---

## 📸 Screenshots
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210037.png)
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210057.png)
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210126.png)
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210200.png)
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210216.png)
![image alt](https://github.com/ChDeekshith14/Skills4future-AICTE/blob/891ed8470ff60c592b32251c292887f757b4c4bd/Screenshot%202026-03-11%20210216.png)

