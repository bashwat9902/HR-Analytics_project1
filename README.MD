 🧠 HR Analytics: Predicting Employee Attrition

📌 Overview
This project analyzes HR data to uncover patterns that lead to employee attrition and builds predictive models to identify employees at risk of leaving. It combines data science techniques, interactive dashboards, and business insights to help HR departments improve retention strategies.

---

 📊 Objectives
- Analyze key drivers of employee attrition
- Predict which employees are most likely to leave
- Visualize attrition trends across departments and roles
- Recommend data-driven retention strategies

---

 🧰 Tools & Technologies
- **Python** (Pandas, Seaborn, Scikit-learn, Plotly)
- **Power BI** for dashboard visualizations
- **Jupyter Notebook / Google Colab**
- **SHAP** (optional for model explainability)

---

 📁 Dataset
A synthetic HR dataset with 500 employee records was used. It includes:
- Demographic: Age, Gender
- Job Info: Department, JobRole, MonthlyIncome, YearsAtCompany
- Behavioral: JobSatisfaction, EnvironmentSatisfaction, OverTime
- Target: `Attrition` (Yes/No)

---

 🔄 Workflow

- Label encoding for categorical variables
- Removal of irrelevant columns (`EmployeeID`)
- Feature-target separation and train-test split
 2. Exploratory Data Analysis (EDA)
- Attrition by Department, Gender, and Role
- Monthly Income distribution
- Correlation heatmap

 3. Modeling
- **Logistic Regression** (Baseline Model)
- **Decision Tree Classifier** (Higher Accuracy ~87%)
- Metrics: Accuracy, Confusion Matrix, Precision, Recall

 4. Visualization
- Created interactive dashboard using Power BI
- Optional: Plotly interactive dashboard in Google Colab

---

 📈 Key Insights
- Overtime, low income, and poor satisfaction are key factors
- Highest attrition seen in Sales and HR departments
- Employees with <3 years at the company are more likely to leave

---

 💡 Recommendations
- Limit mandatory overtime
- Increase early-career support and promotion opportunities
- Tailor retention programs to high-risk roles

---

📦 Project Structure

```plaintext
├── HR_Attrition_Analysis.ipynb       # Jupyter notebook with full code
├── Synthetic_HR_Attrition_Dataset.csv # Raw synthetic dataset
├── Cleaned_HR_Attrition.csv          # Preprocessed dataset for Power BI
├── HR_Attrition_Dashboard.pbix       # Power BI dashboard file
├── HR_Attrition_Report.docx          # Final project report (2 pages)
└── README.md                         # This file
