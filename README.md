# Student Performance Analysis – Capstone Project

## Project Overview

This project analyzes student performance data to explore how various social, demographic, and academic factors influence students' final grades. The goal is to provide insights that can help schools and educators improve academic outcomes.

The project includes two main parts:

- **Python (Data Analysis & Modeling)** using Jupyter Notebook
- **Power BI (Interactive Visualization Dashboard)**

## Sector

**Education**

## Problem Statement

Can we identify key patterns or factors that influence student performance (final grade) based on data about their background, lifestyle, and school support?

## Folder Structure

student-performance-project/
│
├── data/
│ └── student-mat.csv
│
├── codes/
│ └── student_analysis.ipynb
│
├── powerbi/
│ └── powerbi.pbix
│
└── README.md

## Tools Used

- **Python & Jupyter Notebook** for data preprocessing, visualization, and model training
- **Pandas, Seaborn, Scikit-learn** for analytics and machine learning
- **Power BI** for visual dashboard and insights
- **GitHub** for code management and version control

## Methodology

### Python Analysis

1. **Data Cleaning**: Handled missing values and encoded categorical variables.
2. **Exploratory Data Analysis (EDA)**:
   - Scatter plot: `G3` vs. weekend alcohol consumption
   - Boxplots: Study time vs. grade, Failures vs. grade
   - Correlation matrix and heatmap
3. **Modeling**:
   - Used Linear Regression to predict final grade (`G3`)
   - Evaluated with MSE and R² score
4. **Saved Model**: Trained model saved using `joblib` in the `models/` folder.

### Power BI Dashboard

- Visualized key variables such as:
  - Final grade vs. study time
  - Final grade vs. alcohol consumption
  - Final grade distribution
- Included slicers for interactivity (e.g., filter by sex, school)

## Results

- **R² Score**: ~0.75
- Study time and number of failures showed strong correlations with student grades.
- Alcohol consumption negatively impacted performance.

## Recommendations

- Encourage consistent study habits among students.
- Provide additional support for students with past failures.
- Reduce risk factors like excessive alcohol use through awareness programs.

## Future Work

- Try classification models (e.g., Pass vs. Fail).
- Add more external data such as test scores or attendance logs.
- Deploy the model as a prediction tool in a web interface.

## Submission Details

- GitHub Repository: (https://github.com/gisele-gisubizo/Capstone-Project)
- Power BI File: `Powerbi/powerbi.pbix`
- Jupyter Notebook: `codes/student_analysis.ipynb`
- Author: Gisubizo Gisele 26188

> “Whatever you do, work at it with all your heart, as working for the Lord, not for human masters.” – Colossians 3:23
