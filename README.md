# HR Employee Attrition Analytics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-4285F4?style=flat&logo=google-analytics&logoColor=white)](https://analytics.google.com/)

A comprehensive data analytics project focused on understanding employee attrition patterns and predicting workforce turnover using advanced Excel techniques including pivot tables, regression analysis, and interactive dashboards.

![Dashboard Preview](assets/images/dashboard_banner.png)

## 🎯 Project Overview

This project analyzes employee attrition data to identify key factors contributing to workforce turnover and provides actionable insights for HR decision-making. The analysis employs multiple statistical and visualization techniques to create a comprehensive view of employee retention patterns.

### 🔍 Key Objectives
- **Identify Attrition Drivers**: Analyze factors leading to employee turnover
- **Predict Turnover Risk**: Develop models to forecast attrition likelihood  
- **Create Actionable Insights**: Provide data-driven recommendations for HR strategy
- **Build Interactive Dashboard**: Design user-friendly visualization tools

## 📊 Dataset Information

**Source**: HR Employee Attrition Dataset  
**Records**: 1,470 employee records  
**Features**: 35+ variables including demographics, job characteristics, and satisfaction metrics

### Key Variables Analyzed:
- **Demographics**: Age, Gender, Marital Status, Distance from Home
- **Job Characteristics**: Department, Role, Salary, Years at Company
- **Satisfaction Metrics**: Job Satisfaction, Work-Life Balance, Environment Satisfaction
- **Performance Indicators**: Performance Rating, Training Hours, Promotions

## 🛠️ Methodology & Tools

### Technology Stack
- **Primary Tool**: Jupyter Notebook with Python
- **Libraries Used**:
  - **pandas**: Data manipulation and analysis
  - **matplotlib & seaborn**: Data visualization and statistical plotting
  - **numpy**: Numerical computations
  - **plotly**: Interactive visualizations
- **Techniques Applied**:
  - Data Cleaning & Preprocessing
  - Exploratory Data Analysis (EDA)
  - Statistical Analysis & Correlation
  - Multi-dimensional Pivot Analysis
  - Advanced Data Visualization

### Analysis Framework
1. **Data Import & Preprocessing**: Loading and cleaning the HR dataset using pandas
2. **Exploratory Data Analysis**: Comprehensive data exploration and statistical summaries
3. **Feature Analysis**: Multi-dimensional analysis of employee attributes and relationships
4. **Visualization Development**: Creating insightful charts and statistical plots
5. **Pattern Recognition**: Identifying trends in attrition, satisfaction, and compensation
6. **Insights Generation**: Deriving actionable recommendations from data patterns

## 📈 Key Findings

### Income & Compensation Analysis
- **Highest Earning Role**: Manager positions across all education fields
- **Income by Education**: Higher education levels (Level 5) correlate with significantly higher salaries
- **Education Impact**: Employees with advanced degrees earn 30-40% more than entry-level education
- **Attrition vs Income**: Clear inverse relationship - higher income levels show lower attrition rates

### Job Role & Satisfaction Patterns
- **Distance Impact**: Male employees generally commute further than female employees
- **Satisfaction Trends**: Relatively consistent job satisfaction (2.5-3.0 range) across most roles
- **Gender Differences**: Minimal satisfaction gaps between genders across departments
- **Department Analysis**: Research & Development shows highest male satisfaction levels

### Compensation Structure
- **Hourly Rate Distribution**: Technical roles and senior positions command premium rates ($60-75/hour)
- **Education ROI**: Life Sciences and Marketing education fields yield highest compensation
- **Role Hierarchy**: Clear compensation tiers from representatives to executives and directors

## 📁 Repository Structure

├── data/
│   └── hr_employee_dataset.csv              # Raw HR dataset (PROVIDED)
├── notebooks/
│   └── hr_analytics_analysis.ipynb          # Jupyter Notebook analysis (YOUR WORK)
├── docs/
│   ├── project_guidelines.docx              # Assignment specifications (PROVIDED)
│   ├── analysis_report.docx                 # Detailed findings report (YOUR WORK)
│   └── screenshots/                         # Visualization outputs
└── assets/
└── images/                              # Project visuals



## 🖥️ Dashboard Features

### Interactive Elements
- **Attrition Overview**: Department-wise turnover rates
- **Demographic Analysis**: Age, gender, and location breakdowns
- **Satisfaction Correlation**: Impact of job satisfaction on retention
- **Predictive Modeling**: Risk assessment for current employees
- **Scenario Analysis**: What-if modeling for retention strategies

![Dashboard Overview](docs/screenshots/dashboard_overview.png)

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or later
- Jupyter Notebook or JupyterLab
- Required libraries: pandas, matplotlib, seaborn, numpy, plotly

### Usage Instructions
1. **Clone the repository**
```bash
   git clone https://github.com/yourusername/hr-employee-attrition-analytics.git
   cd hr-employee-attrition-analytics
