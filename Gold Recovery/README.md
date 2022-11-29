### Gold Recovery

The goal of this project is to prepare a prototype of a ML model that should predict the recovery rate of gold from gold ore. We have data around extraction and cleaning parameters. The model should help optimize production in order not to launch an enterprise with unprofitable characteristics.

Summary: 
We have prepared a prototype ML model that should predict the gold recovery rate from gold ore.
1. We have studied the data and did some pre-processing steps.
2. We compared the size distributions of raw material granules on the training and test sets. We looked at how the concentration of metals (Au, Ag, Pb) changes at various stages of purification. After that, the total concentration of substances was checked
3. After that, we checked the following models: Linear Regression, DecisionTreeRegressor, RandomForestRegressor. With the help of GridSearchCV, we selected the best model and the best parameters
4. The final SMAPE turned out: 12.7

**KEYWORDS**: Python, Data Cleaning, Linear Regression, DecisionTreeRegressor, RandomForestRegressor
