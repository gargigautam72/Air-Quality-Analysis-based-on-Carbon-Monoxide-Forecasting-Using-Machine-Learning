# Air Quality Analysis based on Carbon Monoxide Forecasting Using Machine Learning
End-to-end ML pipeline for forecasting CO concentrations as an indicator of air quality using the UCI Air Quality dataset. Includes EDA, data preprocessing, feature engineering, Prophet time-series forecasting. Further, it includes model refinement using C6H6 as an external regressor selected via correlation and Random Forest feature importance analysis, and finally model evaluation using MAE, RMSE, and R² metrics.

## Project Summary:

*   In this project, a machine learning-based framework was developed for forecasting carbon monoxide (CO) concentrations, using CO levels as an indicator of air quality. 
*   Successfully performed EDA, data preprocessing, and feature engineering including feature scaling using StandardScaler and MinMaxScaler on CO concentration values. 
*   Through Prophet-based time-series forecasting, the initial model successfully captured temporal patterns in CO levels.
*   Further enhancement using C6H6(GT) as an external regressor significantly improved forecasting accuracy and explained variation, demonstrating a strong predictive relationship of C6H6 with CO levels.
*   The models developed were evaluated using the MAE, RMSE, and R² metrics, demonstrating excellent performance of the models.
*   Overall, the project highlights how integrating statistical analysis with machine learning can improve the analysis of historical air quality data. This further contributes to reliable forecasts, thereby supporting more effective air quality monitoring and data-driven decision-making.

  ### Technologies & Libraries: 
  Python, Pandas, NumPy, Scikit-learn, Prophet, Matplotlib, Seaborn, Google Colab.

  ### Key Techniques & Methods used:
  * Exploratory Data Analysis (EDA)
  * Data preprocessing and missing/invalid value imputation
  * Feature engineering
      * Feature scaling using StandardScaler and MinMaxScaler
  * Time-series forecasting using Prophet
  * Correlation analysis
      * Pearson correlation analysis
      * Correlation heatmap
      * Random Forest-based feature importance analysis
  * Model evaluation using MAE, RMSE, and R² metrics.


