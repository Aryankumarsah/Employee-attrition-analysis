📊 Employee Attrition Analysis
📌 Project Overview

This project analyzes employee attrition using HR data to uncover key factors such as age, salary, overtime, and department. The goal is to provide insights that help organizations improve employee retention and workforce planning.

🎯 Objectives

Identify factors that influence employee attrition.

Visualize attrition trends by age, salary, overtime, and department.

Build a predictive model to classify employees likely to leave.

Provide actionable HR recommendations to reduce attrition.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook for data analysis

GitHub for project sharing

(Optional) Power BI for interactive dashboard

📂 Dataset

HR Employee Attrition Dataset

Contains demographic, work-related, and attrition information

🔑 Project Steps

Problem Definition & Objectives – Define attrition analysis goals

Data Collection & Sources – Import HR dataset (CSV)

Data Cleaning & Preparation – Handle missing values, encode categorical data

Exploration & Visualization – Charts & heatmaps to identify patterns

Predictive Modeling – Random Forest Classifier for attrition prediction

Insights & Recommendations – Summarize results and HR strategies

Report & Dashboard – Notebook, PDF, and optional Power BI dashboard

📊 Key Visualizations

Attrition by Department

Age distribution of employees who left

Attrition vs Overtime

Correlation Heatmap of numeric features

🤖 Machine Learning Model

Algorithm: Random Forest Classifier

Task: Predict whether an employee will leave (Attrition = 1) or stay (Attrition = 0)

Evaluation: Accuracy, confusion matrix, and feature importance

📈 Insights & Recommendations

Younger employees are more likely to leave

Overtime significantly increases attrition risk

Sales & R&D departments have higher turnover

Higher salary reduces attrition probability

Recommendations: Balance overtime, review compensation, focus on retention programs in high-risk groups

📜 Project Structure
📂 Employee-Attrition-Analysis
│── 📄 Employee_Attrition_Analysis.ipynb   # Jupyter Notebook
│── 📄 dataset.csv                         # HR dataset
│── 📄 README.md                           # Project documentation
│── 📄 powerbi_dashboard.pbix              # Power BI dashboard 

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/employee-attrition-analysis.git


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook and run the analysis:

jupyter notebook Employee_Attrition_Analysis.ipynb
