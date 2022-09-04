# NetworkDataAnalysis Project
##FAILURE DETECTION WITH DIFFERENT FAILURES LOCATION
In this repository is present a project related to the course Network and data analysis lab, Politecnico di Milano.
The scope of the project is to understand wheater a failure in a scenario composed by three paths occurrs
with the use of three different classifiers.
Starting from raw data containing information of the paths such as CROSS TALK, POWER(dB) ...it has been necessary to create
a new dataset in which it was added the groundtruth information.
The groundtruth is a binary variable (true/false). Thanks to it, it was possible to identify with an accuracy almost perfect the
presence of a failure in the scenario considered.

#TOPICS COVERED
-Normalization of the dataset
-Characterization of each classifier
-Examine what is the impact of window duration and windows
spacing on the performance of each classifier
-Manually Identify the importance of each feature on the performance
and exploit tecniques that can improve the accuracy of the classifier
-XAI: use explainability to realize each feature's role in the Random
Forest classifier model
