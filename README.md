# Rossmann Stores

# Sales Prediction for Rossmann Stores

<p align='center'>
    <img src='img/rossmann.png'<
</p>

# 1. Business Problem.
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

# 2. Solution Strategy

My strategy to solve this challenge was:

**Step 01. Data Description: Use statistics metrics to identify data distribuctions.**

**Step 02. Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.**

**Step 03. Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.**

**Step 04. Feature Selection: Selection of the most significant attributes for training the model.**

**Step 05. Machine Learning Modelling: Machine Learning model training**

**Step 06. Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.**

**Step 07. Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.**

**Step 08. Deploy Modelo to Production:  Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.**

# 3. Top 3 Data Insights

Stores with more assortments sell less.

Stores with closer competitors sell more than stores with more distant competitors.

Stores sell less on weekends.

# 5. Machine Learning Model Applied

At this stage, 5 models were used for analysis:
*Average - Baseline
*Linear Regression
*Lasso Regression
*Random Forest Regressor
*XGBoost Regressor

# 6. Machine Learning Modelo Performance

XGBoost had a MAPE of 11.59%.

	Model Name		MAE		MAPE		RMSE
	XGBoost Regressor	772.459114	0.115992	1109.989069

# 7. Business Results

Below is the six-week forecast.

	Scenario	Values
	predictions	R$277,437,632.00
	worst_scenario	R$276,572,719.87
	best_scenario	R$278,302,519.21

# 8. Conclusions

The sales forecast and the generated insights provide the CEO with valuable tools to decide the amount of budget that is going to be dedicated to the restoration of each store.

