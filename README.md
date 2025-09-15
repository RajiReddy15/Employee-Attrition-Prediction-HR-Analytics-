# 📌 HR Attrition Prediction  

## 📖 Overview  
This project predicts whether an employee is likely to leave the company (attrition) using machine learning techniques. Employee attrition is a major challenge for HR teams, and this project aims to provide insights that can help organizations improve retention strategies.  

---

## 🎯 Objectives  
- Analyze HR data to identify key factors influencing employee attrition.  
- Build and compare multiple machine learning models.  
- Evaluate performance using accuracy, precision, recall, F1-score, and ROC-AUC.  
- Provide actionable insights for HR decision-making.  

---

## 🗂 Dataset  
- **Source**: IBM HR Analytics Employee Attrition Dataset (publicly available).  
- **Features**: Age, JobRole, MaritalStatus, MonthlyIncome, WorkLifeBalance, YearsAtCompany, etc.  
- **Target**: Attrition (Yes/No).  

---

## ⚙️ Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - Pandas, NumPy (data handling)  
  - Matplotlib, Seaborn (visualization)  
  - Scikit-learn (ML models & evaluation)  
  - Jupyter Notebook (development)  

---

## 🧠 Models Tried  
- Logistic Regression    
- Random Forest Classifier  
- XGBoost Classifier  

---

## 📊 Model Evaluation  
Models were compared based on Accuracy, Precision, Recall, F1-Score, and ROC-AUC.  

| Model                | Accuracy | Precision | Recall | F1-Score | ROC-AUC |  
|-----------------------|----------|-----------|--------|----------|---------|  
| Logistic Regression   | 0.82     | 0.75      | 0.68   | 0.71     | 0.80    |  
| Random Forest         | 0.87     | 0.81      | 0.77   | 0.79     | 0.88    |  
| XGBoost               | 0.89     | 0.83      | 0.80   | 0.81     | 0.90    |  

✅ **Best Model: XGBoost** with ROC-AUC of **0.90**  

---

## 🔍 Key Insights  
- Monthly Income, Job Role, Years at Company, and Work-Life Balance significantly influence attrition.  
- Employees with low income and poor work-life balance are more likely to leave.  
- Random Forest and XGBoost provided the most balanced performance.  

---


## 📂 Project Structure  

HR-Attrition-Prediction/
│

├── data/ # Data files (raw & modified)

│     ├── employee_attrition.csv

│     ├── cleaned_data.csv

│
├── scripts/ # Scripts for project workflow

│   ├── datacollection.py

│   ├── datacleaning.py

│   ├── eda.py

│   ├── model.py
│
├── relation/ # Feature relationship analysis

│ ├── relation_with_attrition.py

│ 

├── README.md # Project documentation


└── requirements.txt # Python dependencies

---

## 🚀 How to Run the Project  

1. Clone the repository:  
   git clone https://github.com/your-username/hr-attrition-prediction.git
   cd hr-attrition-prediction
   
3. Install dependencies:
   pip install -r requirements.txt
   
3.Run Jupyter Notebook or Python scripts:
   jupyter notebook

📌 Future Work
Deploy the model as a web app using Flask/Streamlit.

Perform hyperparameter tuning for better accuracy.

Try deep learning models for more complex patterns.

🏆 Results
Best Model: XGBoost

ROC-AUC: 0.90

Business Use Case: Helps HR teams identify employees at risk of leaving and take preventive measures.

✍️ Author

Your Name : S.RajiReddy

GitHub: https://github.com/RajiReddy15

LinkedIn: https://www.linkedin.com/in/raji-reddy-bb54682aa/
