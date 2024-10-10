# AutoPricePred

Project Overview:
The goal of the project is to predict automobile prices using a variety of machine learning models. The dataset includes several features, such as the car's make, fuel type, number of cylinders, and price, among others.

Key Steps:
1. Data Preprocessing:

Initial exploration shows different types of data (object, float, int, bool).
The dataset has 16 discrete and 10 continuous columns.
Missing values and non-standard values like "?" are handled through preprocessing.

2. Exploratory Data Analysis (EDA):

Car Brand Analysis: Toyota has the highest number of listings, while Mercury has the least.
Price Analysis: Mercedes-Benz is associated with the highest vehicle prices, while Chevrolet offers vehicles with the highest city miles per gallon (MPG) but at a lower price point.
Cylinders and MPG: Vehicles with eight cylinders and cars with the best city MPG were analyzed to derive patterns.

3. Univariate Analysis:

Numerical and categorical columns were explored separately to understand the distribution and variability within the data.

4. Model Training:

Several machine learning models were trained to predict automobile prices:
Linear Regression: Performed well with reasonable accuracy.
Support Vector Regression (SVR): Did not perform as expected, with a low R² score.
Decision Tree: Showed good performance with minimal overfitting.
Bagging and Boosting (Gradient Boosting): Provided strong results, with Gradient Boosting performing particularly well due to its ability to handle non-linear relationships.

5. Challenges:

A limited dataset with only 200 rows contributed to overfitting and reduced accuracy.
Handling missing values and "?" entries was time-consuming and affected the quality of insights.
Lack of features like car model year and sale price year further limited the analysis.
Hyperparameter tuning was challenging but essential for improving model performance.

6. Conclusion:

Gradient Boosting emerged as the best-performing model, making it well-suited for this task.
The project encountered various challenges, especially related to data quality and size.
