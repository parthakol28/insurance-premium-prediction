# 🧠 Insurance Premium Prediction App

This project predicts annual insurance premium amounts based on customer demographic, financial, and medical attributes. Built with Python, the goal is to improve pricing accuracy and reduce under/over-charging for insurance customers.

---

## 🚀 Project Highlights
### Model Details

- **Model:** Used XGBoost algoritm to bulid the model
- **Data:** 50,000+ records with 12+ features including age, income, health status, and insurance plan.


---

## 📁 Dataset Features

1. **Input Features**

| Category      | Features |
|---------------|----------|
| Demographics  | `age`, `gender`, `region`, `marital_status` |
| Health        | `bmi_category`, `smoking_status`, `medical_history` |
| Financial     | `income_level`, `income_lakhs`, `employment_status` |
| Insurance     | `insurance_plan`,  |

2. **Target Variable**
<br>Annual Premium Amount
---

---
## 🚀 How to Use

1. Clone the repository

2. Install the dependencies using:
   ```
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```
