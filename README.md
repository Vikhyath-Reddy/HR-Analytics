# HR-Analytics
# README

## Project Overview
This project explores HR analytics, focusing on employee performance, job satisfaction, and promotion factors. The study leverages machine learning models and visualization techniques to identify key drivers behind career progression and workplace equity.

## Dataset
- **Source**: Kaggle HR Analytics Dataset
- **Dataset Overview**:
  - 23 columns, including Education, EducationField, and JobRole.
  - 6709 reviews for 1470 employees, indicating multiple evaluations per employee.
  - "Years in Most Recent Role" differs from "Years Since Last Promotion," suggesting promotions refer to salary increases rather than positional advancements.

## Features
- **SelfRating**: Dominates importance across all years, indicating that employees' self-assessment strongly influences performance ratings.
- **Salary**: Consistently ranks second, showing a strong link between compensation and performance evaluation.
- **Age & Distance from Home**: Frequently appear as key factors, indicating life stage and commute distance impact performance ratings.
- **YearsAtCompany, YearsWithCurrManager, YearsSinceLastPromotion**: Moderate but steady influence on performance ratings.
- **Shifts in Other Features**: Some years show increased importance for factors like YearsInMostRecentRole or RelationshipSatisfaction.
- **Stable Trends Over Time**: Feature importance remains consistent over the years, indicating stable evaluation criteria.

## Data Preprocessing
- Handling missing values by appropriate imputation techniques.
- Standardizing data formats for consistency.
- Encoding categorical variables for machine learning models.
- Removing redundant or highly correlated features.

## Methodology
1. **Data Preprocessing**
   - Cleaning and formatting data for consistency.
   - Handling missing values using appropriate imputation techniques.
   - Feature engineering and transformation.

2. **Data Visualization**
   - Exploring correlations between demographics, job satisfaction, and promotions.
   - Graphical representations using Matplotlib/Seaborn.
   - Visualization of trends in performance metrics.

3. **Analysis and Model Implementation**
   - Applying Machine Learning models for classification/prediction.
   - Evaluating model performance using accuracy, precision, recall.
   - Analyzing feature importance.

## Key Findings
1. **Correlation Over Time**:
   - Male and female employees show fluctuations in self vs. manager rating correlations over the years.
   - Male employees start with a stronger correlation (0.87 in 2014), dip in 2016, and gradually recover post-2020.
   - Female employees initially have lower correlations (0.82 in 2014), improve sharply in 2015, fluctuate, and converge with male ratings by 2022.

2. **Gender Differences in Ratings**:
   - 2014: Male employees have stronger alignment with manager ratings.
   - 2015: Female self-ratings surpass male alignment briefly.
   - 2018: Both genders experience a dip, with female ratings dropping more.
   - 2022: Convergence in correlations suggests reduced gender disparities.

3. **Possible Causes for Fluctuations**:
   - 2014–2015: Female rating improvements may indicate diversity/inclusion initiatives.
   - 2018 Dip: Could be due to performance evaluation changes or discrepancies in self-perception vs. managerial assessments.
   - Post-2020 Trends: Gradual alignment suggests better appraisal systems and awareness of gender fairness.

4. **Education Level & Promotions**:
   - Masters/Doctorate holders have slightly higher manager ratings but slower promotion cycles.
   - Lower education levels tend to have quicker promotions, possibly due to role complexity and seniority factors.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Execution
To run the notebook, execute the following:
```bash
jupyter notebook Cap-Stone_Project.ipynb
```
Ensure all dependencies are installed using:
```bash
pip install -r requirements.txt
```
## Future Work
- Incorporate additional datasets for broader insights.
- Apply advanced ML techniques for better accuracy.
- Explore deep learning models for predictive analytics.

## Contributors
- **Author**: Vikhyath Reddy Bheemreddy

