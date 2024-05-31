# Understanding Employee Attrition: Patterns, Causes, and Predictive Insights

## Objective:
The primary objective of this project was to construct a predictive model for analyzing employee turnover within a company. The goal was to identify key factors influencing employee churn and forecast which employees are at risk of leaving, enabling proactive retention strategies.

## Data Overview:
The dataset encompassed several features, including satisfaction levels, project involvement, average monthly hours, tenure, work accidents, employment status, and recent promotions. These attributes provided a comprehensive view of employee dynamics.

## Methods and Models:
To tackle this business challenge, a range of models were deployed, including Logistic Regression, Random Forest, and XGBoost. Each model underwent rigorous evaluation based on performance metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC Score. This ensured the selection of the most effective model for predicting employee turnover.

## Business Problem:
The HR department at Salifort Motors is seeking to enhance employee satisfaction levels within the company. With data collected from employees, they are confronted with the challenge of leveraging this information effectively. As a data analytics professional, they turn to you for data-driven insights to address their pressing question: what factors are likely to lead an employee to leave the company?

### Project Goals:
Analyze the HR department's dataset to discern patterns and trends related to employee turnover.
Develop a predictive model capable of identifying employees at risk of leaving the company.
Provide actionable recommendations based on insights derived from the data, aiming to mitigate employee turnover and bolster retention efforts.

### Expected Outcome:
By accurately predicting employees who may quit, Salifort Motors can proactively identify underlying factors contributing to attrition. This proactive approach not only saves time and resources associated with recruitment but also fosters a positive work environment conducive to employee satisfaction and retention, ultimately benefiting the company's overall productivity and success.
## Dataset Overview
The dataset provided for this project  comprises 15,000 rows and 10 columns, encompassing various variables. 

You can refer to the data  source on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)

## Key Insights:
  ### Model Selection:

Random Forest and XGBoost exhibited superior performance in comparison to Logistic Regression, establishing them as more dependable options for this particular scenario.
The ROC-AUC scores and feature importance plots from both models aided in comprehending the significance of each feature in predicting employee turnover.
  ### Feature Importance:

Satisfaction Level emerged as the most pivotal factor influencing employee departure across both models, displaying a robust negative correlation with the target variable.
Last evaluation, number of projects, and average monthly hours were also noteworthy determinants impacting the probability of an employee leaving the company.
![image](https://github.com/ZareClem/Employee-Attrition-Prediction-Model/assets/138980152/c63a12eb-abcb-43ec-9883-5ed1fc4b7921) ![image](https://github.com/ZareClem/Employee-Attrition-Prediction-Model/assets/138980152/4d8348e0-a684-4c1c-bffa-c6e4948af441)

## Correlation Insights:
Employee satisfaction showed a strong negative correlation with leaving, implying lower satisfaction leads to higher chances of leaving.
Features like last evaluation, number of projects, and average monthly hours showed significant positive correlations with each other, affecting employee satisfaction inversely.
Promotions in the last 5 years and work accidents had notable impacts on employee departure, though comparatively minor.
![image](https://github.com/ZareClem/Employee-Attrition-Prediction-Model/assets/138980152/ae3680e3-a1b8-499d-a082-4e816711f279)

## Recommendations:

### Employee Satisfaction:
Focus on strategies to enhance employee satisfaction, addressing specific concerns and improving the overall work environment.
Regularly assess employee satisfaction levels to identify and mitigate potential issues proactively.

### Workload Management:
Establish a balanced workload by managing the number of projects and average monthly hours to prevent employee burnout and dissatisfaction.

### Employee Development:
Foster career development opportunities, ensuring that promotions and recognitions are distributed fairly and transparently.

### Model Utilization:
Employ the predictive models, particularly Random Forest or XGBoost, to forecast potential employee churn, allowing for timely interventions.
Continuously update and refine the models to adapt to evolving organizational dynamics and employee behaviors.
