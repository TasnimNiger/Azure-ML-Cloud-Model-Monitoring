# Azure-ML-Cloud-Model-Monitoring
Explore the importance of model monitoring and its role in ensuring the ongoing performance and reliability of machine learning models.  Conduct long-term model monitoring checks like data drift, target checks, Kolmogorov-Smirnov test, and model drift for sustained model performance assessment. 


## Business Context: 

Fashion Haven has successfully implemented a predictive model for sales revenue estimation based on their advertising campaigns across different media sources (TV, Newspaper, Radio). The model has been deployed in production, and it plays a crucial role in guiding the company's advertising budget allocation and overall marketing strategy. However, after the initial deployment, the company faces the challenge of monitoring the model's performance and ensuring its ongoing reliability and accuracy. Over time, the business environment may change, advertising trends could evolve, or external factors may impact customer behavior, all of which can influence the model's predictive capabilities. Fashion Haven needs to develop a robust model monitoring system to identify and address potential issues with the deployed sales revenue prediction model.
The goal of this model monitoring assignment is to implement a proactive approach to ensure the model's continued effectiveness and identify any degradation in its performance. By regularly monitoring the model, Fashion Haven can maintain the quality of predictions, make timely updates, and take corrective actions as needed.
The model monitoring system should provide the following key functionalities:

**1. Data Drift Detection:** The business environment is dynamic, and changes in customer behavior, market trends, or competitor strategies may cause data distribution to drift over time. The monitoring system should identify and measure data drift in the input features used by the model, helping the team understand how well the model adapts to new data.

**2. Model Drift Checks:** Regular calibration checks will ensure that the model's predicted probabilities align with the observed outcomes. If the model becomes miscalibrated, corrective actions should be taken to recalibrate it for accurate probability estimates.


## Data Description:

The data contains the different attributes of the advertising business. The detailed data dictionary is given below.

-  **TV:** Expenditure on media resource- TV 
-  **Radio:** Expenditure on media resource- Radio 
-  **NewsPaper**: Expenditure on media resource- Newspaper 
-  **Sales:** Target Column - Amount of Sales
