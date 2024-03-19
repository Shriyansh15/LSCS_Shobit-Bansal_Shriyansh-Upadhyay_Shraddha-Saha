# X Education Lead Conversion Prediction

## Problem Statement
X Education, an online training company, aims to improve its lead conversion rate by identifying the most promising leads. The company has provided a dataset containing information about leads, including their interactions with the website and whether they converted or not. The goal is to build a logistic regression model to assign a lead score between 0 and 100 to each lead, indicating the likelihood of conversion.

## Data Description
The dataset contains around 9000 data points with attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable is 'Converted', where 1 indicates conversion and 0 indicates no conversion. Some categorical variables have a level called 'Select', which needs to be handled as it is similar to a null value.

## Goals
1. Build a logistic regression model to assign a lead score to each lead.
2. The lead score should help the sales team target potential leads more effectively.
3. Achieve a target lead conversion rate of around 80%.

## Approach
1. **Data Cleaning**: Handle missing values, outliers, and 'Select' levels in categorical variables.
2. **EDA**: Univariate & Bivariate Analysis
3. **Dummy Variable Creation** 
4. **Test-Train Split**
5. **Feature Scaling** : Checking Correlation Matrix
6. **Model Building**: Build a logistic regression model using all features and another using RFE feature selection.
7. **Model Evaluation**: Compare the performance of both models on unseen test data.
8. **Model Interpretation**: Analyze the coefficients of the final model to understand the relative importance of each feature.

## Results
- Factors influencing conversion include website engagement, specialization, occupation, and city.
- The RFE-based feature selection model performed slightly better, suggesting that excluding irrelevant features can improve model accuracy.

## Conclusion
By focusing on website engagement, targeting relevant user segments, and optimizing marketing efforts in specific cities, X Education can potentially increase its lead conversion rate and drive business growth.

For detailed analysis, refer to the Jupyter notebook, Word document, and presentation provided.
