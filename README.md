# 📊 Employee Attrition Prediction using Machine Learning

Predict employee attrition using Machine Learning by analyzing HR-related factors such as job satisfaction, salary, work-life balance, overtime, years at the company, and more. This project helps organizations identify employees who are at risk of leaving, enabling proactive retention strategies.

---

## 📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations. High attrition leads to increased recruitment costs, productivity loss, and knowledge drain.

This project builds a Machine Learning classification model that predicts whether an employee is likely to leave the organization based on historical HR data.

---

## 🎯 Objectives

- Analyze employee data to understand factors influencing attrition.
- Perform data cleaning and preprocessing.
- Explore data using visualization techniques.
- Train multiple Machine Learning classification models.
- Evaluate model performance using various metrics.
- Select the best-performing model for prediction.

---

## 📂 Repository Structure

```
EmployeeAttrition/
│
├── HR_Attrition.csv  # Dataset
│   
│
├── analysis.ipynb   # Notebook
│   
│
├── charts/
|   └── Attrition_Rate_by_Department.png
|   └── Attrition_Rate_by_Job_Role.png
|   └── chart5_roc_curve.png
|   └── confusion_matrix.png
|   └── feature_importance.png
|   └── Monthly_Income_by_Employee_Attrition.png
│
├── requirements.txt
├── README.md         # Documentation
```

---

## 📊 Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance Dataset

The dataset contains employee-related information including:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Job Satisfaction
- Environment Satisfaction
- Overtime
- Work-Life Balance
- Years at Company
- Training Times Last Year
- Attrition (Target Variable)

**Target Variable**

- Yes → Employee Left
- No → Employee Stayed

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Encoding & Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Prediction
```

---

## 📈 Exploratory Data Analysis

The project includes several visualizations to understand the dataset:

- Department-wise Attrition
- Job Role Analysis
- ROC CURVE of the trained models
- Confusion matrix
- Feature Importance
- Monthly Income Analysis

These insights help identify patterns associated with employee turnover.

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting

The best-performing model was selected based on evaluation metrics.

---

## 📏 Evaluation Metrics

Model performance was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Deepthikarani/EmployeeAttrition.git
```

Move into the project directory

```bash
cd EmployeeAttrition
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install required libraries.
3. Open the notebook.
4. Run all cells sequentially.
5. View predictions and evaluation results.

---


## 💡 Key Insights

- Overtime has a strong relationship with employee attrition.
- Employees with lower job satisfaction tend to leave more frequently.
- Monthly income and work-life balance significantly influence retention.
- Employees with fewer years at the company show higher attrition rates.

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Ensemble Learning
- Model Explainability using SHAP/LIME
- Deployment using Streamlit or Flask
- Real-time prediction API

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- HR Analytics
- Data Visualization

---

## 🛠 Requirements

```
Python 3.x

numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 👩‍💻 Author

**Pokali Deepthikarani**

B.Tech Computer Science Engineering

Machine Learning & Data Science Enthusiast

GitHub:
https://github.com/Deepthikarani

LinkedIn:
https://linkedin.com/in/deepthikarani-pokali-5304182b8

---

## ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub.

It motivates me to build more Machine Learning and Data Science projects.

---

## 📄 License

This project is intended for educational and learning purposes.
