# Main-Project
HR Analytics- Predict Employee Attrition
# HR Analytics - Predict Employee Attrition

## 📌 Objective
Use analytics to understand the key factors behind employee resignation and build a classification model to predict future attrition.

---

## 🧰 Tools & Technologies
- Python (Pandas, Seaborn, Scikit-learn)
- Power BI
- SHAP (for model explainability)

---

## 📊 Dataset
- **File:** `hr_analytics_attrition_dataset.xlsx`
- Contains features like:
  - Satisfaction Level
  - Last Evaluation
  - Number of Projects
  - Average Monthly Hours
  - Time Spent at Company
  - Work Accident
  - Promotion in Last 5 Years
  - Department
  - Salary
  - Attrition Label (Left)

---

## 🔍 EDA (Exploratory Data Analysis)
- Identified key factors affecting attrition
- Analyzed department-wise trends and salary-level impact
- Visualizations done using Seaborn and Power BI

---

## 🤖 Model Building
- **Model Used:** Logistic Regression (with `max_iter=1000`)
- Feature engineering: Label encoding for categorical columns
- Train-test split applied

---

## 🧪 Evaluation
- **Classification Report:** `classification_report.csv`
- **Confusion Matrix:** `confusion_matrix.png`
- Accuracy, Precision, Recall, and F1-score computed

---

## 📊 Power BI Dashboard
- File: `hr_attrition_analysis.pbix`
- Interactive visuals:
  - Attrition by department
  - Salary vs. attrition
  - Time spent at company vs. attrition
  - Slicer to filter employee left/stayed

---

## 📈 SHAP Analysis
- Used SHAP to explain model predictions
- Identified key influencers like satisfaction level, monthly hours, and promotion status

---

## 🎯 Deliverables
| File | Description |
|------|-------------|
| `hr_analytics_attrition_dataset.xlsx` | Original dataset |
| `hr_analytics_attrition_model.ipynb` | Python notebook with EDA, model training, and evaluation |
| `classification_report.csv` | Model performance metrics |
| `confusion_matrix.png` | Visual confusion matrix |
| `hr_attrition_model.pkl` | Trained Logistic Regression model |
| `hr_attrition_analysis.pbix` | Power BI dashboard |
| `hr_analytics.pptx` | Presentation slides |
| `model metrics summary slide.pptx` | Slide with classification metrics |
| `readme.md` | Project documentation |

---

## ✅ How to Run (Locally)
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas seaborn scikit-learn streamlit joblib shap

---

## Insights & Recommendations
1. Employees with low satisfaction and no promotions in the last 5 years are at higher risk of leaving.

2. Departments with higher workloads should be monitored.

3. Increasing employee engagement and internal mobility may reduce attrition.

