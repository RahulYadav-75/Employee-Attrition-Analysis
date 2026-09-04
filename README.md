# 📊 Employee Attrition Analysis

## 📌 Project Overview

This project analyzes employee data to understand the main factors that influence **employee attrition (employees leaving the company)**.

The analysis uses Python and data visualization techniques to identify patterns related to **age, salary, overtime, job role, department, job satisfaction, work-life balance, and experience**.

---

## 🎯 Objectives

* Analyze employee attrition patterns
* Identify factors associated with employee turnover
* Clean and prepare the HR dataset
* Perform Exploratory Data Analysis (EDA)
* Create meaningful visualizations
* Generate business insights for employee retention

---

## 📂 Dataset

The dataset contains employee information such as:

* Age
* Gender
* Department
* Job Role
* Monthly Income
* Salary Slab
* Business Travel
* Overtime
* Job Satisfaction
* Work-Life Balance
* Years at Company
* Total Working Years
* Attrition

**Dataset Size:** 1,480 employees and 38 columns

---
## 🔄 Data Analysis Workflow

The project follows a structured data analysis process:

```text
1. Data Understanding
        ↓
2. Data Cleaning
        ↓
3. Univariate Analysis
        ↓
4. Attrition Analysis
        ↓
5. Categorical vs Attrition
        ↓
6. Numerical vs Attrition
        ↓
7. Correlation Analysis
        ↓
8. 20+ Business Insights
        ↓
9. Recommendations
        ↓
10. Dashboard
```

### 📌 Workflow Details

**1. Data Understanding**
Understand the dataset, columns, data types, and employee information.

**2. Data Cleaning**
Handle missing values, remove duplicates, check incorrect values, and prepare the data.

**3. Univariate Analysis**
Analyze individual variables such as Age, Gender, Department, Salary, and Job Role.

**4. Attrition Analysis**
Analyze the overall employee attrition rate and understand the distribution of employees who left and stayed.

**5. Categorical vs Attrition**
Compare categorical variables such as Job Role, Department, OverTime, Gender, and Salary Slab with Attrition.

**6. Numerical vs Attrition**
Compare numerical variables such as Age, Monthly Income, Distance From Home, and Years at Company with Attrition.

**7. Correlation Analysis**
Study relationships between numerical variables and identify important patterns.

**8. 20+ Business Insights**
Convert the analysis into meaningful business insights related to employee turnover.

**9. Recommendations**
Suggest strategies that can help HR teams reduce employee attrition.

**10. Dashboard**
Create an interactive dashboard to present important KPIs, charts, and business insights.


## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Checked missing values
* Handled missing values using median imputation
* Removed duplicate records
* Checked data types
* Checked invalid values
* Identified constant columns
* Prepared categorical and numerical variables for analysis

---

## 📊 Exploratory Data Analysis

The project analyzes:

### Employee Demographics

* Age Group
* Gender
* Marital Status
* Education Field

### Job Information

* Department
* Job Role
* Job Level
* Business Travel

### Compensation

* Monthly Income
* Salary Slab
* Percent Salary Hike
* Stock Option Level

### Employee Experience

* Total Working Years
* Years at Company
* Years in Current Role
* Years Since Last Promotion
* Years With Current Manager

### Employee Satisfaction

* Job Satisfaction
* Environment Satisfaction
* Relationship Satisfaction
* Work-Life Balance
* Job Involvement

---

## 🔍 Key Business Insights

Some important findings from the analysis:

* Overall employee attrition rate is approximately **16%**.
* Employees working **overtime** have significantly higher attrition.
* Younger employees show higher employee turnover.
* **Sales Representatives** have one of the highest attrition rates.
* Employees in lower salary groups show higher attrition.
* Employees with lower job involvement have higher attrition.
* Poor work-life balance is associated with higher attrition.
* Employees who left the company have lower average tenure.
* Employees who left have lower average monthly income than employees who stayed.
* Employees who travel frequently show higher attrition.

---

## 📈 Visualizations

The project includes visualizations such as:

* Attrition Distribution
* Attrition by Age Group
* Attrition by Department
* Attrition by Job Role
* Attrition by Overtime
* Attrition by Salary Slab
* Attrition by Business Travel
* Attrition by Job Satisfaction
* Attrition by Work-Life Balance
* Attrition by Years at Company

---

## 💡 Business Recommendations

Based on the analysis, companies can:

1. Monitor employees working frequent overtime.
2. Improve work-life balance.
3. Focus on retention of younger employees.
4. Review compensation for lower salary groups.
5. Improve employee engagement and job involvement.
6. Provide better career growth and promotion opportunities.
7. Monitor high-risk job roles and departments.

---

## 📁 Project Structure

```text
employee-attrition-analysis/
│
├── data/
│   └── HR_Analytics.csv
│
├── notebooks/
│   └── Employee_Attrition_Analysis.ipynb
│
├── images/
│   └── charts/
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/employee-attrition-analysis.git
```

### 2. Go to the project folder

```bash
cd employee-attrition-analysis
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder.

---

## 👨‍💻 Author

**Rahul Yadav**

B.Tech – Computer Science & Engineering (Data Science)

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Data Cleaning` `EDA` `Matplotlib` `Seaborn` `Business Analytics`
