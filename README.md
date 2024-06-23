#### Project Overview: Secondhand Car Price Prediction
In this project, I built a robust model for predicting the prices of secondhand cars. 
The dataset included various features such as the car's age, kilometers driven, condition, and technical specifications. My goal was to refine the prediction accuracy by addressing key aspects of the model development process.

#### Key Improvements and Methodologies
Understanding Data Distribution:
- I employed the Shapiro-Wilk test to assess the normality of the data distribution. This helped identify any deviations from normality, allowing for better preprocessing and transformation of the features.
Feature Selection:
- To enhance the model's performance, I utilized Univariate Selection with the SelectKBest method to extract the most significant features. This approach helped in reducing dimensionality and retaining only the features that had the highest impact on the target variable.
Model Evaluation and Performance:

By refining the feature selection and understanding the data distribution, I managed to lower the Root Mean Squared Error (RMSE), which served as the evaluation metric for the model. 
The reduced RMSE value indicated an improvement in the model's predictive accuracy and overall performance.

#### Results and Impact
Through these enhancements, the updated model demonstrated a marked improvement in predicting secondhand car prices. 
The use of the Shapiro-Wilk test ensured better data preprocessing, while the SelectKBest method for feature selection significantly improved the model's focus on impactful variables. 
As a result, the model achieved a lower RMSE, reflecting higher accuracy and reliability in price predictions.

This project underscores the importance of thorough data analysis and strategic feature selection in building effective predictive models.
