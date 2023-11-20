
# Heart Disease in the USA: Exploring Trends and Health Determinants.

## Overview
The proposed research project is to conduct thorough research into the current trends of cardiovascular disease (CVD) in the United States. This study will explore the prevalence of CVD, its impact on various demographic groups(age, gender), and the health indicators and tests that can identify heart risk. This research is driven by the dedication to providing valuable insights into heart health.

## Acknowledgements

 - [API CDC] https://data.cdc.gov/resource/9dzk-mvmi.json
 - [kaggle]https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

## Task Breakdown

**1. Introduction**
Explain the motivation and purpose behind the analysis. Why the analysis is conducted?

**2. Data Preparation**
Install and import necessary Python packages for data analysis and visualization.
Connect to any external data sources or APIs required for data retrieval.
Load the dataset into the project environment.
Initial exploration to understand the dataset's structure and content.

**3. Data Preprocessing**
Identify and handle missing data points.
Check for and remove duplicate entries.
Detect and address outliers in the data.
Calculate descriptive statistics to understand data distribution.
Create visualizations to identify outliers.

**4. Exploratory Data Analysis**
Analyze trends in heart-related mortality from 2020 to 2023.
Calculate and visualize year-to-year growth rates.

**5. Univariate Analysis of Continuous Variables**
Analyze the distribution of heart risk by gender.
Explore age-related insights:
Visualize age distribution (Histogram).
Visualize age density (Density plot).
Compare age distribution by gender.
Analyze cholesterol level distribution.
Explore the distribution of resting blood pressure.
Examine the distribution of resting heart rate.
Create density graphs for continuous variables.

**6. Univariate Analysis for Categorical Columns**
Analyze categorical variables (provide more details on what categorical variables are analyzed).

**7. Bivariate Analysis**
Investigate the relationship between age and blood pressure.

**8. Statistical Analysis**
Perform point-biserial correlation analysis for heart attack risk and continuous variables.
Conduct chi-squared analysis for heart attack risk and categorical variables.

**9. Conclusion**
* Gender and Heart Risk:There is a positive correlation between gender and heart risk, with females having a significantly higher (75%) proportion of high-risk cases.

* Age and Heart Risk:The highest risk for heart disease is observed among individuals aged 55-60.
However, there doesn't appear to be a strong link between age and heart disease risk.
* Cholesterol Levels:High-risk cases increase significantly between cholesterol levels of 200-300 mg/dL.
However, there isn't a strong correlation between cholesterol levels and heart disease risk.

* Resting Heart Rate:Resting heart rate shows a positive correlation with high risk for heart disease.
High-risk heart rate is observed in the range of 170-180 bpm.

* Blood Pressure:A significant number of high-risk cases have blood pressure between 125-140 mmHg.
Nonetheless, there isn't a strong connection between blood pressure and heart disease risk.

* Exercise-Induced Angina:Exercise-induced angina is correlated with a lower risk of heart-related issues.
Non-anginal pain is very frequent among high-risk heart patients.

* Chest pain: Individuals with Typical Angina chest pain (typically considered low severity) are more often classified as low-risk, suggesting that less severe chest pain may be associated with a lower cardiovascular risk.

* Resting ECG: Having a normal resting electrocardiogram (Left Ventricular Hypertrophy) is associated with a lower risk classification for the condition in question, highlighting the importance of this diagnostic indicator in assessing cardiovascular risk.

* Ca: Having no major blood vessels affected (category 0) is correlated with a low-risk classification, indicating that the number of affected vessels is a significant factor in risk assessment, with fewer affected vessels being more favorable.

* Slope: A certain type of ST segment slope during peak exercise (unsloping) is more frequently associated with high-risk classifications, suggesting that this particular ST segment slope may be a critical predictor of cardiovascular events.

* Exercise-induced angina: The absence of an exercise-induced angina condition corresponds to a higher count of individuals being classified as high-risk, suggesting that exercise may have an impact on cardiovascular health and can influence risk assessment.

* Blood sugar:A lower fasting blood sugar level (<120 mg/dl) is predominant among those classified as high risk group suggest the negative correlation with heart risk.


## Authors

- [Ashlin Shinu George](https://github.com/)

