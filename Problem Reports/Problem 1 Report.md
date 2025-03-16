
###  Discussion and justification of any pre-processing performed, such as standardisation
* Important or LASSO & Ridge regression
* Using Scaler
* Performed this on the X_train, X_val and X_test sub-sets

### Details of the three trained models, including key parameters such as values for λ for the LASSO and Ridge models, and a brief discussion of how these were selected

#### - OLS regression model
*model summary:*
OLS Regression Results
|Dep. Variable:|ViolentCrimesPerPop|R-squared:|0.759|
|Model:|OLS|Adj. R-squared:|0.637|
|Method:|Least Squares|F-statistic:|6.207|
|Date:|Sun, 16 Mar 2025|Prob (F-statistic):|7.72e-28|
|Time:|19:53:46|Log-Likelihood:|251.07|
|No. Observations:|298|AIC:|-300.1|
|Df Residuals:|197|BIC:|73.27|
|Df Model:|100|||
|Covariance Type:|nonrobust||

*variance inflation factor*
|Feature|VIF|
|---|---|
|0|population|301.036172|
|1|householdsize|43.223331|
|2|racepctblack|29.407713|
|3|racePctWhite|27.699090|
|4|racePctAsian|7.606502|
|...|...|...|
|95|PctSameState85|12.730610|
|96|LandArea|7.016748|
|97|PopDens|6.065991|
|98|PctUsePubTrans|4.135846|
|99|LemasPctOfficDrugUn|2.252615|

*Residual Distribution*
[[ResidualDistribution.png]]

*Q-Q Plot*
[[Q-QPlot.png]]

*Residuals Vs Fitted Values*
[[Residuals_vs_FittedValues.png]]

*R^2 values etc..*
R²: 0.759085121509442
Adjusted R²: 0.6367933050167729
AIC: -300.133317607413
BIC: 73.27312452963281
#### - Ridge regression model
* Performed Data pre-processing (Scalar transforms)
* 
* 
