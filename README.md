# Regression Case Study
## Data
we isolated our initial analysis to just a few columns:

['Grouser_Type', 'ProductSize', 'Drive_System', 'Thumb', 'Track_Type', 'Pattern_Changer', 'Differential_Type', 'Steering_Controls']


And used One-Hot Encoding to deal with NaNs in the categorical data
## Evaluation
### GDBR Without Log Transform
![GDBR](images/GDBR.png)
### GDBR With Log Transform
![LogGDBR](images/LogGDBR.png)
### Grid Search results for Optimal Hyperparameters GDBR
![GridSearch](images/gdbr_gridsearch.png)
### Grid Search results for Optimal Hyperparameters Random Forest
![GridSearch](images/rf_gridsearch(1).png)
### GDBR With Log Transform and Optimal Hyperparameters
![Optimized](images/gdbr_optimized.png)
### GDBR vs Random Forest
![VS](images/gdbr_rf_model.png)
### Feature Importance
![Features](images/Permuatation_importance.png)

