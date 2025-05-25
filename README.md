# HealBharat_2
# 🏥 Patient Outcome Prediction - Task 2 (Heal Bharat Internship)

This project is part of my internship at **Heal Bharat**. The goal of Task 2 is to predict patient recovery outcomes using clinical vitals, and demonstrate how machine learning can support healthcare decision-making.

---

## 📌 Objective

To analyze patient health data and build a classification model that predicts whether a patient is likely to recover (1) or not recover (0), based on vital signs like heart rate, respiratory rate, blood pressure, oxygen saturation, and temperature.

---

## 📁 Folder Structure
Patient_Outcome_Analysis/
├── Task_2_Dataset.xlsx                   # Dataset used for training
├── Patient_Outcome_Prediction.ipynb      # Jupyter Notebook with code and analysis
├── Summary_Report.pdf                    # Final report with methodology & insights
├── Data_Dictionary.pdf                   # Column definitions and descriptions
├── ML_Workflow_Diagram.pdf               # End-to-end workflow visualization
├── roc_curve.png                         # ROC Curve comparison (LR vs RF)
├── feature_importance.png                # Feature importance plot from Random Forest
└── README.md                             # Project overview and guide


---

## 🔍 Dataset Overview

- Format: Excel (`.xlsx`)
- Records: ~1,000 patient entries
- Fields used:
  - `patient_id`
  - `age`
  - `heart_rate`
  - `respiratory_rate`
  - `blood_pressure`
  - `oxygen_saturation`
  - `temperature`
  - `outcome` (1 = Recovered, 0 = Not Recovered)

---

## 📊 Methods & Tools Used

- **Languages**: Python (Jupyter Notebook)
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- **Models Used**:
  - Logistic Regression (Baseline)
  - Random Forest Classifier (Best performance)
- **Evaluation Metrics**:
  - ROC-AUC Score
  - F1-Score
  - Confusion Matrix

---

## 📈 Key Insights

- Respiratory rate and oxygen saturation were the top predictors of recovery.
- Random Forest achieved a high ROC-AUC (~0.85), outperforming Logistic Regression.
- The model can help hospitals flag high-risk patients early for intervention.

---

## ✅ Recommendations

- Monitor high-risk vitals closely (especially respiratory rate and oxygen saturation).
- Expand dataset with diagnosis, gender, and treatment fields for even better accuracy.
- Deploy model into dashboards for clinical testing and alert systems.

---

## 👨‍💻 Author

**[Your Name]**  
Data Analyst Intern, Heal Bharat  
