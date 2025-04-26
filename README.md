# Employee_Attrition_Prediction

### By Zoya Naseer
[
![Attrition-01](https://www.teamly.com/blog/wp-content/uploads/2022/06/What-Is-Employee-Attrition.png)
](url)


## *Overview*

This project analyzes employee attrition trends and predicts potential high-risk employees using data visualization and machine learning. The goal is to help HR teams take early action to retain employees and reduce hiring costs.



## *Problem Statement*

High employee attrition impacts productivity, increases hiring costs, and affects company culture. However, organizations often lack tools to understand:
- *Why employees leave*
- *Who is most likely to leave next*



## *Objectives*

- Analyze employee data to uncover attrition patterns  
- Predict which employees are at risk of leaving  
- Identify the most influential features leading to attrition  
- Present insights using an interactive Power BI dashboard


## *Tools & Technologies*

- *Python*: For data cleaning, feature engineering, and ML modeling  
- *Scikit-learn*: To train classification models  
- *Power BI*: For dashboard creation and visualization  
- *SHAP / Feature Importance*: For model explainability



## *Datasets Used*

1. *cleaned_dataset.csv*  
   - Contains processed employee information  
   - Features include: Department, Job Role, Monthly Income, Overtime, etc.

2. *feature_importance.csv*  
   - Output from ML model showing which features contribute most to attrition


## *Dashboard Pages*

### *1. Attrition Analysis Dashboard*
- *KPIs*: Total Employees, Attrited Employees, Avg Monthly Income, Satisfaction Score  
- *Visuals*:  
  - Attrition by Job Role  
  - Monthly Income vs Attrition  
  - Work-Life Balance & Overtime Impact  
  - Gender-wise and Department-wise Attrition  
- *Slicers*: Filter by Job Role, Gender, Overtime, Department, etc.

### *2. ML Insights Dashboard*
- *Top Drivers of Attrition* (Bar Chart from feature_importance.csv)  
- *Predicted High-Risk Employees Table*  
- *Feature Impact (Tree Map)*



## *Results / Insights*

- Employees with *low income, **high overtime, and **longer commutes* are more likely to leave  
- Departments like *Research & Development* have higher attrition  
- Machine learning model helps flag at-risk employees for HR focus



## *Business Impact*

- Helps organizations take *data-driven decisions* to improve employee retention  
- Reduces hiring/training costs  
- Improves employee satisfaction and overall productivity





