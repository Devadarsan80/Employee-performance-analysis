# 🏢 Employee Performance Analysis Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Type](https://img.shields.io/badge/Type-Client%20Project-orange.svg)

---

## 📌 Project Overview

This project analyzes employee data from **INX Future Inc.** to understand and predict employee performance using Machine Learning. The goal is to help organizations identify key factors that influence employee performance and build a predictive model to support data-driven HR decision-making.

---

## 🎯 Objective

- Identify patterns and key factors affecting employee performance
- Build a machine learning model to predict employee **Performance Ratings**
- Provide actionable insights to HR teams for better workforce management
- Analyze department-wise performance trends

---

## 📊 Dataset

| Property | Details |
|---|---|
| **Source** | INX Future Inc. Employee Performance Dataset |
| **File** | INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls |
| **Target Variable** | `PerformanceRating` |
| **Features** | Department, Education Level, Training Score, Salary Hike %, Years Since Promotion, Environment Satisfaction, and more |

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---|---|
| **Language** | Python 3.8+ |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Model Used** | Random Forest Classifier |
| **Preprocessing** | LabelEncoder, Train-Test Split |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 🔍 Methodology

### 1. Data Acquisition
- Loaded the employee performance dataset from an Excel file
- Explored the structure using `.head()`, `.info()`, `.describe()`

### 2. Data Preprocessing
- Checked and handled **missing values**
- Removed irrelevant columns (e.g., `EmpNumber`)
- Applied **Label Encoding** to all categorical variables
- Split dataset into **80% training** and **20% testing** sets

### 3. Exploratory Data Analysis (EDA)
- **Correlation Heatmap** — identified relationships between features
- **Count Plot** — visualized performance rating distribution
- **Bar Chart** — analyzed department-wise average performance
- **Distribution Plots** — explored feature distributions

### 4. Model Development
- Applied **Random Forest Classifier** with 200 estimators
- Trained model on training set
- Predicted performance ratings on test set

### 5. Model Evaluation
- Evaluated using **Accuracy Score**, **Classification Report**, **Confusion Matrix**
- Extracted **Feature Importances** to identify top influencing factors

---

## 📈 Results

### ✅ Model Performance
| Metric | Score |
|---|---|
| **Algorithm** | Random Forest Classifier |
| **Estimators** | 200 |
| **Test Split** | 20% |
| **Evaluation** | Accuracy, Precision, Recall, F1-Score |

### 🔑 Top 3 Factors Influencing Employee Performance

| Rank | Feature | Impact |
|---|---|---|
| 1 | `EmpEnvironmentSatisfaction` | High |
| 2 | `EmpLastSalaryHikePercent` | High |
| 3 | `YearsSinceLastPromotion` | High |

### 📊 Key Insights
- Departments with **lower environment satisfaction** showed consistently lower performance
- Employees with **higher salary hike percentages** tend to perform better
- Long gaps since **last promotion** negatively impact performance ratings
- The model can predict performance rating for any new employee based on their profile

---

## 📁 Project Structure

```
employee-performance-analysis/
│
├── Employee_performance_analysis_project.ipynb   # Main notebook
├── INX_Future_Inc_Employee_Performance_Data.xls  # Dataset
├── README.md                                      # Project documentation
```

---

## 🚀 How to Run

### Step 1 — Clone the Repository
```bash
git clone https://github.com/yourusername/employee-performance-analysis.git
cd employee-performance-analysis
```

### Step 2 — Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xlrd openpyxl
```

### Step 3 — Run the Notebook
```bash
jupyter notebook Employee_performance_analysis_project.ipynb
```
Or open directly in **Google Colab** by uploading the `.ipynb` file.

---

## 💡 Business Impact

- Helps HR departments **proactively identify** underperforming employees
- Enables organizations to focus on **environment satisfaction** and **salary policies**
- Reduces guesswork in **performance reviews** using data-driven predictions
- Supports strategic decisions around **promotions and training programs**

---

## 🙋 Author

**Devadarsan A**
- 📧 Email: devadarsan80@gmail.com
- 💼 LinkedIn: [linkedin.com/in/devadarsan-a-043756307]
- 🐙 GitHub: [https://github.com/Devadarsan80/Employee-performance-analysis]
---

## 📜 License

This project is for educational and portfolio purposes.

---

⭐ **If you found this project helpful, please give it a star!**
