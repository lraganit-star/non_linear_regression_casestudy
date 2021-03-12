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
### Grid Search results for Optimal Hyperparameters
![GridSearch](images/gdbr_gridsearch.png)
### GDBR With Log Transform and Optimal Hyperparameters
![Optimized](images/gdbr_optimized.png)
### GDBR vs Random Forest
![Optimized](images/gdbr_optimized.png)

