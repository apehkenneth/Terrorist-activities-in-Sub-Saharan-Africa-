# Terrorist activities in Sub Saharan Africa (SSA) between 1970 and 2019
The dataset is for terrorist activities in Sub Saharan Africa (SSA) between 1970 and 2019. The columns show various attributes in the dataset.
The main idea is to subject the dataset to machine learning models to train the data and use the same for predicting future terrorist occurrences.

Overall objective is to intelligently use ML algorithms to predict future terrorist activities in Sub Saharan Africa (types, groups involved, places of incidents, etc) using data from the Global Terrorism Database.

The main machine learning models of interest here are: Support Vector Machines (SVM), Naive Bayes (NB), Logistic Regression (LR) and Neural Networks (NNETs).

Some of the metrics to be considered for comparing performances include: Root Mean Square Error (RMSE); Minkowski/Euclidean distance (for K-Nearest Neighbours); Jaccard Similarity coefficient (Regression); or F1 Score.

# Data dictionary

A few explanations of the column data are as follows:
1.	weaptype1_txt - the weapon type used by the terrorists
2.	nkill - no of people killed
3.	nwounded - no of people wounded
4.	gname - name of the group that carried out the attack
5.	targettype1_txt - the main target of the terrorist group
6.	success - whether the attack was successful or not
7.	attacktype1_txt - method of accrying out the attack (assassination, bombing, shooting, explosion, etc)
8.	iyear - the year the terrorist attack occured
9.	imonth - the month in which the attack took place
10.	iday - the day in which the attack took place
11.	country_txt - the country in which the attack took place
12.	
13.	eventid - the unique identification for each terrorist activity
14.	latitude  - the geographic latitude position of the event
15.	longitude - the geographic longitude position of the event
16.	crit1/crit2/crit3 - shows whether the attack was critical in nature

