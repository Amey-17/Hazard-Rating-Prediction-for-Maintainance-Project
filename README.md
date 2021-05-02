# Hazard-Rating-Prediction-for-Maintainance-Project
A Machine Learning Predictive model building project. 

All the money in the world can not make up for a loss of life. Better safe than sorry is the motto of
all engineering and construction practices which routinely deal with dangerous situations.
However many times, extent of caution is just not enough and leads to very hard learnt lessons
in employee safety.

Instead of relying on something going wrong and then taking preventive measure; organisations
are coming up with ways of assessing the extent of danger to life for a new project before even
the first hammer strikes.

We have a masked dataset which contains various properties of tasks taken up in heavy
equipments maintenance by a manual crew. Each of these tasks have been given a hazard score
which is eventually used in deciding levels of safety checks and caution while planning for the
maintenance process.

### Data Files
Train Dataset = Hazard_train.csv
Test Dataset = Hazard_test_share.csv

### Formal Problem Statement
Variable names are masked and there is no formal data dictionary provided by the client .
The task here is to build a predictive model for predicting hazard score given other information
related to maintenance tasks. We need to build your model on the train dataset. Test dataset
does not have a response column; We need to predict those values.

target column = Hazard

### Exploratory Data Analysis
The code for exploratory data analysis is present in 'Hazard Prediction - Exploratory Data Analysis.ipynb'.

### Feature Selection
We have applied various statistical tests for feature selection. The code is present in 'Hazard Prediction - Feature Selection.ipynb'.

### Feature Transformation and Encoding
The code for feature transformation and encoding is present in 'Hazard Prediction - Feature Transformation & Encoding.ipynb'.

### Model Building and Hyperparameter Tuning
The code for model building and hyperparameter tuning is presnt in 'Hazard Prediction - Model Building & Hyperparameter Tuning.ipynb'.

### Pickle File
The cleaned and transfomed data is present in 'transformed_all_data_hazard' pickle file.
