# MSCS 634 - Lab 4: Regression Techniques

**Purpose of the Lab**
The objective of this lab was to explore and compare different regression techniques using the Diabetes dataset from the sklearn.datasets library. The lab involved implementing Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, Ridge Regression, and Lasso Regression to predict disease progression. Model performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the coefficient of determination (R²). Visualizations were also created to compare model predictions and understand data patterns.

**Key Insights**
•	Simple Linear Regression using BMI alone provided limited predictive performance because a single feature could not fully explain disease progression.
•	Multiple Linear Regression significantly improved prediction accuracy by utilizing all available predictor variables.
•	Polynomial Regression did not improve performance, indicating that the relationship between the predictors and the target variable is largely linear.
•	Ridge Regression reduced coefficient magnitudes through L2 regularization, improving model stability while retaining all features.
•	Lasso Regression achieved the best overall performance by applying L1 regularization, performing feature selection, and improving model generalization.
•	The comparison of all models demonstrated that regularization techniques can improve predictive performance while reducing the risk of overfitting.

**Challenges and Decisions**
•	Selecting the appropriate polynomial degree required experimentation to observe the effects of underfitting and overfitting.
•	Different alpha values were tested for Ridge and Lasso Regression to understand how regularization strength affects model performance.
•	Model evaluation required comparing multiple performance metrics rather than relying on a single measure.
•	Organizing results, visualizations, and model comparisons in a clear and consistent format was important for effectively interpreting and presenting the findings.

