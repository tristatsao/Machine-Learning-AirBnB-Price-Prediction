# Machine-Learning-AirBnB-Review-score-rating-Prediction
Objective 
In this project, we investigate the Airbnb ratings dataset found on Kaggle. Our goal is to know what factors will influence the review scores rating value of the Airbnb listings in LA and how we can better predict the review scores ratings. The dataset contains 22,267 entries and 39 total columns. Based on 6 machine learning models and these models' performance, our team generate some insights for Airbnb to maintain high review scores ratings.
We used R as our main data analysis tool.

Step 1: Exploratory Data Analysis
We explored the data through summary statistics and boxplots to deal with NA values, outliers , standardized all the column names and created the new variables that we think will affect the price prediction. After cleaning the data, we further checked the correlations between each variable to see if there are any multicollinearity issues because this could lead to misleading or skewed results. 

Step 2: Machine Learning
After selecting the variables, we have separated 80% of the data into training data and the remaining 20% is testing data. Then we applied various machine learning techniques for predicting the review scores rating of Airbnb, including KNN, Linear regression, Support Vector Regression, Regression Tree, Random Forest, and Gradient Boost.  we evaluated the models' performance based on R squared and RMSE on both training samples and testing samples.

Step 3: Results
By comeparing the R squared and RMSE,  our best prediction model comes from Gradient Boost model, which got highest R squared :0.64 and lowest RMSE 4.16 in testing sample.

Tool: R
