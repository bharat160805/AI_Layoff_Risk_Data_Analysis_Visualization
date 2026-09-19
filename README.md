# 📊 AI Layoff Risk — Data Analysis & Visualization

## 📌 Project Overview

This project is a **Data Analysis and Visualization project** that explores the relationship between **Artificial Intelligence adoption, task automation, employee characteristics, and layoff risk**.

The analysis uses Python and Jupyter Notebook to clean, explore, analyze, and visualize employee-related data.

The project focuses on understanding how factors such as **AI adoption, task automation, routine tasks, AI usage, training, experience, job role, industry, and education level** relate to different layoff-risk categories.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the dataset
* Clean and prepare the data for analysis
* Identify missing and duplicate values
* Handle invalid values
* Detect and remove outliers
* Analyze employee characteristics
* Study AI adoption and usage
* Analyze task automation
* Compare different layoff-risk categories
* Identify relationships between numerical variables
* Create meaningful data visualizations
* Generate business insights from the analysis

---

## 🛠️ Tools & Technologies

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## 📂 Dataset

The dataset contains employee and AI-related attributes, including:

| Feature                    | Description                          |
| -------------------------- | ------------------------------------ |
| Industry                   | Industry in which the employee works |
| Job_Role                   | Employee's job position              |
| Company_Size               | Size of the organization             |
| Job_Level                  | Employee's organizational level      |
| Education_Level            | Employee's education level           |
| Age                        | Employee age                         |
| Years_of_Experience        | Years of professional experience     |
| AI_Adoption_Level          | Level of AI adoption                 |
| AI_Training_Hours          | AI-related training hours            |
| AI_Usage_Hours_Per_Week    | Weekly AI usage                      |
| Routine_Task_Percentage    | Percentage of routine tasks          |
| Tasks_Automated_Percentage | Percentage of tasks automated        |
| Human_Interaction_Level    | Level of human interaction           |
| Creativity_Requirement     | Creativity requirement of the job    |
| Layoff_Risk                | Employee layoff-risk category        |

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Information & Statistics
   ↓
Missing Value Detection
   ↓
Duplicate Detection
   ↓
Data Cleaning
   ↓
Invalid Value Handling
   ↓
Outlier Detection
   ↓
Outlier Removal
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Correlation Analysis
   ↓
Business Insights
```

---

# 🧹 Data Cleaning

The project performs several data-cleaning operations.

### Missing Values

Missing values are identified using:

```python
df.isnull().sum()
```

String values such as:

```text
NULL
N/A
null
n/a
```

are converted into missing values.

### Duplicate Values

Duplicate records are identified and removed.

### Invalid Age Values

Negative age values are treated as invalid and replaced with missing values before filling them using the median.

### Invalid Experience Values

Negative years of experience are treated as invalid and replaced with missing values before median imputation.

### Missing Numerical Values

Missing numerical values such as:

* AI Usage Hours
* AI Training Hours
* Age
* Years of Experience

are handled using median values.

### Missing Categorical Values

Missing categorical values such as:

* Education Level
* Industry
* Job Role
* Job Level
* Company Size
* AI Adoption Level

are handled using the mode.

### Percentage Validation

Percentage-based variables are checked to ensure their values fall within the valid range of **0–100**.

---

# 📊 Exploratory Data Analysis

The project performs analysis to answer questions such as:

### 1. Layoff Risk Distribution

The number and percentage of employees in each layoff-risk category are calculated.

### 2. High-Risk Employees by Industry

The project analyzes the number of high-risk employees across different industries.

### 3. Employees by Company Size and Industry

The distribution of employees across company sizes and industries is analyzed.

### 4. Job Role and Job Level

A cross-tabulation is used to examine the relationship between job roles and job levels.

### 5. AI Training Hours

Average AI training hours are analyzed across job levels and education levels.

### 6. Education Level Distribution

The number of employees belonging to different education levels is visualized.

---

# 📈 Data Visualizations

The project includes several types of visualizations.

### 📊 Bar Chart

Used to analyze job roles with the highest proportion of high layoff risk.

### 📉 Histogram

Used to understand the distribution of task automation percentages.

### 🔵 Scatter Plot

Used to examine the relationship between:

```text
Routine Task Percentage
           vs
Task Automation Percentage
```

with employees categorized by layoff risk.

### 📈 Line Chart

Used to compare average task automation percentages across industries.

### 📌 Stem Plot

Used to visualize the number of employees belonging to different job roles.

### 🥧 Pie Chart

Used to show the percentage distribution of employees across layoff-risk categories.

### 📊 Grouped Bar Chart

Used to compare minimum, maximum, and average percentages of:

* Routine Tasks
* Automated Tasks

### 🎻 Violin Plot

Used to analyze the variation in task automation percentages across layoff-risk categories.

### 🍩 Donut Chart

Used to visualize the percentage distribution of employees across AI adoption levels.

### 🔥 Correlation Heatmap

Used to analyze the strength and direction of relationships between numerical variables.

### 🔗 Pair Plot

Used to examine relationships between:

* Age
* Years of Experience
* Routine Task Percentage
* Creativity Requirement
* Human Interaction Level
* AI Usage Hours
* Tasks Automated Percentage
* AI Training Hours

across different layoff-risk categories.

---

# 💡 Key Insights

The analysis provides several observations about the dataset:

* AI adoption is changing the nature of work across industries.
* Routine tasks can have greater exposure to automation.
* Task automation varies across industries and job roles.
* Different layoff-risk categories show different patterns in task automation.
* AI usage and training can be analyzed alongside employee characteristics.
* The project provides an overall view of employee exposure to AI-related automation and layoff risk.

> These insights are based on the patterns observed in the analyzed dataset and should not be interpreted as predictions about individual employees.

---

# 📊 Visualizations Included

The notebook contains:

* Employee distribution analysis
* Layoff-risk analysis
* Education-level analysis
* Job-role analysis
* Industry analysis
* Task automation analysis
* AI adoption analysis
* Correlation analysis
* Multivariable relationship analysis

---

# 📁 Repository Structure

```text
AI-Layoff-Risk-Data-Analysis/
│
├── README.md
│
├── AI_Layoff_Risk_Data_Analysis.ipynb
│
├── ai_impact_jobs_layoff_risk.csv
|
├── correlation_heatmap.png
├── distribution_of_layoff_risk.png
├── percentage_distribution_of_layoff_risk.png
├── percnetage_of_employees_in_each_ai_adoption_level_category.png
├── variation_of_task_automation_acorss_layoff_risk_categories.png
```

---

# 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Layoff-Risk-Data-Analysis.git
```

### 2. Navigate to the project

```bash
cd AI-Layoff-Risk-Data-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

bash
jupyter notebook


### 5. Open

AI_Layoff_Risk_Data_Analysis.ipynb

### 6. Run the notebook cells

Make sure the dataset path in the notebook matches the location of the dataset inside the repository.

---

# 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Exploratory Data Analysis (EDA)
* Data Cleaning
* Missing Value Handling
* Duplicate Removal
* Outlier Detection
* Statistical Analysis
* Data Visualization
* Correlation Analysis
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Business Insight Generation

---

## 👨‍💻 Author

**Bharat Prajapat**

B.Tech Computer Science & Engineering

**Skills:** Python | SQL | Excel | Power BI | Data Analysis | Machine Learning | NLP

---

⭐ If you find this project useful, feel free to explore the repository and other data analysis projects.
