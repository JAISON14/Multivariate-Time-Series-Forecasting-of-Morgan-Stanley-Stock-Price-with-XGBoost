# Multivariate-Time-Series-Forecasting-of-Morgan-Stanley-Stock-Price-with-XGBoost

#### Project Overview
The primary objective of this project was to develop a predictive model for Morgan Stanley's stock price. I aimed to employ advanced machine learning techniques, specifically focusing on time series forecasting using the XGBoost algorithm.

#### Data and Features
Historical stock prices of Morgan Stanley and other relevant indices like S&P 500 and Financials Select Sector Index were used. Several features such as rolling averages, lags, and others were engineered to improve the model's performance.

#### Model Building and Evaluation
Initially, I trained the model using a comprehensive set of features and evaluated it using various metrics like MAE, MSE, RMSE, and MAPE. The initial model yielded promising results with an RMSE value of approximately 1.10.

To improve upon this, I evaluated feature importance, revealing that only a subset of features significantly impacted the model's predictive capability. A simplified model was then trained using these important features alone.

#### Results
The simplified model showed a marked improvement in all evaluation metrics:

* Mean Absolute Error (MAE): Reduced to 0.2814
* Mean Squared Error (MSE): Reduced to 0.634
* Root Mean Squared Error (RMSE): Reduced to 0.796
* Mean Absolute Percentage Error (MAPE): Reduced to 1.626%

#### Implications
The results demonstrate the power of feature selection and engineering in enhancing model performance. By focusing on the most impactful features, I was able to build a more efficient and accurate model.

#### Future Work
While the results are promising, further improvements can be explored by:

* Experimenting with other machine learning algorithms and ensemble methods.
* Incorporating more external features, like macroeconomic indicators.
* Fine-tuning the model parameters using techniques like Grid Search or Randomized Search.
