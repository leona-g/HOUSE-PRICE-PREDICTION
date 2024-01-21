# HOUSE-PRICE-PREDICTION

Introduction:

In the realm of real estate, predicting house prices accurately is a complex task that involves understanding various factors influencing property values. This project aimed to create an advanced house price prediction model using regression techniques. The dataset initially consisted of 1460 rows and 81 columns, with thorough exploratory data analysis (EDA), feature engineering, and feature selection employed to enhance the modeling process.

Approach:

The initial dataset underwent a comprehensive EDA to uncover patterns and insights, followed by strategic feature engineering to extract relevant information. Feature selection techniques were then applied to streamline the dataset, resulting in a final set of 21 features deemed crucial for modeling.

Regression Techniques:

Four regression algorithms—Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Support Vector Regressor—were employed to predict house prices based on the selected features.

Results:

The model performance was evaluated using mean squared error (MSE) and R-squared metrics:

1. **Linear Regression:**
   - Mean Squared Error: 0.019201
   - R-squared: 0.897111

2. **Decision Tree Regressor:**
   - Mean Squared Error: 0.041586
   - R-squared: 0.777153

3. **Random Forest Regressor:**
   - Mean Squared Error: 0.020494
   - R-squared: 0.890177

4. **Support Vector Regressor (SVR):**
   - Mean Squared Error: 0.021062
   - R-squared: 0.887134

Conclusion:

The results demonstrate the effectiveness of the regression models in predicting house prices. Linear Regression emerged as the top performer with a low MSE and a high R-squared value, indicating its strong predictive capabilities. Random Forest Regressor closely followed, showcasing the power of ensemble methods. While Decision Tree Regressor and SVR performed well, they exhibited slightly higher errors compared to the top two models.

This project's success underscores the importance of thorough data exploration, thoughtful feature engineering, and strategic model selection in creating accurate and reliable predictive models for house prices. The insights gained can potentially assist stakeholders in making informed decisions in the dynamic real estate market.
