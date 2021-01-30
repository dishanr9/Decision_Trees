# Decision_Trees
HW to implement decision trees - Python

•	Consider the two data files attached to this homework assignment. 
This data is taken from the UCI Machine Learning Repository and contains biomechanical features of some patients. 

The task is to predict whether the patient is normal or abnormal (call it Data2). 
The second dataset splits the abnormal group into two different diagnoses (call it Data3). 
Both datasets have same 310 feature vectors, six features, and a class column.
Perform the following tasks with these datasets and submit the answers asked for in each task listed below.  

•	All your answers must be contained in a single pdf file. Upload this pdf file.

•	Use only one of the following two utilities: Scikit library function for decision trees or fitctree function of Matlab. Work done by any other toolbox will not be accepted.


1.	(30) Take Data2 and split it into randomly selected 230 training instances and remaining 80 as test instances. 
          Create decision trees using the training set and the “minimum records per leaf node” values of 5, 15, 25, 40 and 50. 
              a.	Show the trees for all the five cases of “min record per node” values. Comment on what you see in a comparative analysis of the five trees. 
                  Just reporting the numbers is not enough; you must try to give an explanation of any differences in decision tree structures. 
                  Which of these five trees would you prefer to use and why?
              b.	For each of the five decision trees compute and report the accuracy, precision (for each class), and recall (for each class) values. 
                  Compare and comment on these values and show these values on a plot. 
                  Give your reasons for the observed trends/differences.
                  
2.	 (30) Repeat the same tasks as done in Question-1 above for Data3 (Now the decision tree has three classes to work with). 
          In addition to reporting results for parts (1a) and (1b) comment on the comparison of results obtained for (1a) and (2a) and also for (1b) and (2b). 
          
3.	(30) Take Data2 for this question. Use “1” to denote “Abnormal” and “0” to denote “Normal) class labels. 
          Compute and report the correlations between each attribute (column) and the class label column. 
          Drop the column that has the highest magnitude of the correlation value (It could be positive or negative).
          
          Now repeat  that you did for Question number1 above.
          
          a.	Repeat the task (1a) for the truncated dataset.
          b.	Repeat the task (1b) for the truncated dataset.
          c.	Compare and contrast the results of (1a) with those of (2a), and the results of (1b) with those of (2b).
          
4.	(10) These 10 points are for good organization and presentation of results in your submission.

