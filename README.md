# UK-Regional-Inequality-Analysis
An econometric analysis of school expenditure per pupil (EXPP) across the UK. Using the dataset in R, this project examines regional funding disparities through descriptive statistics, 80/20 ratios, and multivariate regression to identify key drivers of resource allocation in the primary and secondary education sectors.

## Regional Expenditure Disparities in UK Schools: An Econometric Analysis

### Project Overview: 
This project investigates the distribution of financial resources across the UK education system using the Department for Education (DfE) AppQE dataset. The analysis focuses on identifying whether school expenditure is influenced by geographical location, school type, or socioeconomic factors.  This research was originally developed as part of an Applied Quantitative Economics project during my study abroad term at Goldsmiths, University of London.  

### Key Research Questions:
- How significant is the funding gap between the highest and lowest-funded schools in the UK?
- To what extent do socioeconomic variables, such as the percentage of pupils eligible for Free School Meals (PFSM), drive expenditure per pupil?
- Are there statistically significant regional variations in resource allocation?

### Methodology & Technical Skills:
The analysis is conducted in R within a Jupyter Notebook, utilizing a "literate programming" approach where the code and narrative are intertwined to tell a comprehensive story.  
- Data Cleaning: Managing missing values and structural inconsistencies within the 758-school sample.  
- Descriptive Statistics: Utilizing the 80/20 ratio and coefficient of variation to quantify financial inequality.
- Econometric Modeling: Developing a multivariate regression model with Expenditure per Pupil (EXPP) as the dependent variable.
- Hypothesis Testing: Interpreting $p$-values, $R^2$, and standard errors to determine the statistical significance of regional and socioeconomic drivers.

### Repository StructureProject_Analysis.ipynb: 
The primary file containing the integrated R code, data visualizations, and research write-up.

### Key Findings
- Expenditure per pupil and expenditure overall were the largest determinants of regional inequalities across the UK
- Socioeconomic Impact: Initial findings suggest that schools with a higher percentage of students on Free School Meals (PFSM) often correlate with higher expenditure per pupil, reflecting targeted funding policies.
- Regional Variance: The analysis highlights distinct concentration tendencies in expenditure across different local authorities. 
