summary of the analysis:

Data was loaded, cleaned, and split into training and testing sets.
Linear Regression, Decision Tree, and Random Forest models were trained and evaluated. The Linear Regression model showed the best performance with very low RMSE and MAE, and an R2 close to 1.
The Random Forest model was tuned using GridSearchCV, and the best parameters were found.
Visualizations were generated to show actual vs. predicted values, residual distribution, and feature importances for the tuned Random Forest model. The feature importance plot shows that 'Supply Chain Emission Factors without Margins' is the most important feature in predicting 'Supply Chain Emission Factors with Margins'.
The tuned Random Forest model was saved as 'best_random_forest_model.pkl'.
