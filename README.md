# Crime-prediction
We have data for per-capita crime rates around the country. The task is to build models to predict the crime rate based on demographic and economic information about the particular locality. The data is given in the files “communities-crime-clean.csv” and “communities-crime-full.csv”; a description of the data and data fields is given in “communities-crime.names”. The “full” dataset includes data fields with missing values (indicated by “?”), while in the “clean” set these fields have been removed.

Decision Trees
In this problem, we use the clean dataset to predict whether the crime rate in a locality is greater than 0.1 per capita or not.

Linear Classification
Use GaussianNB and Linear SVC to learn classifier to predict highCrime, and compare the results for both.
	
Regression
Use Linear and ridge regression to predict highCrime, and compare the results for both.

Dirty Data
Here we repeat the decision tree learning for the full (non-clean) data set and present the results. We compare different missing value treatment methods as well.
