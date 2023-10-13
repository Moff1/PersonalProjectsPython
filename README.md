### This project is showcasing the NLP model, and how it interacts with a dataset in additional data exploration

### Import Packages

### Import Data

### EDA

### Including for Inflation
I took it upon myself to add the inflation (based on 2022) to make the data and model more accurate

### Models and Data Pre-Processing 
I stated that if a movie is successful if the revenue exceeds the budget of the movie

### Pipeline
This pipeline has several components:
 - Categorical Transformer: 
	- Simple Imputer: set to fill in the missing values in the datasets
	- One Hot Encoder:  represent categorical variables as numerical values in a machine learning model
 - Numerical Transformer:
	- Simple Imputer: set to fill in the missing values in the datasets
	- Robust Scaler: scales the data, but ignores the outlier data points
- Preprocessor:
	- contains the Categorical and Numerical Transformer

### Logistic Classification Model
 - I created a second 'pipelinetwo' which is a copy of the previous pipeline

### HyperParameter Tuning and Cross Validation 
Even though these pipelines are performing well, we can always see if there is way to better these models. I used Randomized Search Cross Validation, which takes in parameters and plays mix and match until the best results are yielded.

### Logistic Model Tuning (Same method as Logistic Model)
I then recreated the above process using an Logstic Model instead of XGBoost model

### Conclusion
Both of these model perform pretty similiarly which I figured would happen when the orginal model performed so well with the test dataset. I just wanted to show the process if the original model had been terrible
