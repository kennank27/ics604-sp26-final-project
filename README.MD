# Student Performance Analysis

This project explores the relationship between academic, behavioral, lifestyle, and family/social factors and student academic performance using the UCI Student Performance Dataset.

The analysis was completed using exploratory data analysis (EDA), correlation analysis, and linear regression techniques in Python through a Jupyter Notebook workflow.

---

# Project Objective

The goal of this project is to determine which factors are most strongly associated with student academic performance and to explore whether student outcomes can be predicted using academic, behavioral, and social variables.

The project specifically investigates:
- The relationship between prior grades and final academic performance
- The effect of study time on student outcomes
- The impact of alcohol consumption and social activity
- The role of family background and educational support
- Which variables demonstrate the strongest relationships with final grades

---

# Dataset

Dataset Source:  
UCI Machine Learning Repository - Student Performance Dataset  
https://archive.ics.uci.edu/dataset/320/student+performance

This project uses the mathematics student dataset (`student-mat.csv`).

The dataset includes:
- Student grades
- Demographic information
- Behavioral and lifestyle variables
- Family and social support variables
- School-related features

Target Variable:
- `G3` — Final grade

---

# Technologies Used

- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels

---

# Project Structure

```text
.
├── README.md
├── requirements.txt
├── student-mat.csv
├── ics604_final_project.ipynb
└── ics604_final_report.pdf
```

---


# Analysis Overview

The notebook includes:
- Data inspection and preprocessing
- Target variable analysis
- Academic factor analysis
- Behavioral and lifestyle analysis
- Family and social factor analysis
- Correlation and multivariate analysis
- Simple and multiple linear regression
- Final conclusions and insights

---

# Key Findings

- Prior academic grades (`G1` and `G2`) were the strongest predictors of final performance (`G3`)
- Past academic failures showed a strong negative relationship with student outcomes
- Study time demonstrated a moderate positive relationship with performance
- Behavioral variables such as alcohol consumption and social activity showed weaker negative relationships
- Family education and higher education aspirations demonstrated moderate positive relationships with academic success

---

# AI Usage Disclosure

ChatGPT was used during this project for:
- Writing assistance
- Notebook organization recommendations
- Visualization recommendations
- Report formatting assistance
