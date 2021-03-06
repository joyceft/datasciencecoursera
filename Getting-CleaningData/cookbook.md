Code Book
===========================================================
This code book is to indicate all the variables used in the project, and summeries calculated, along with 
units, and any other relevant information.

Steps
-----------------------------------------------------------
1.  Reading all the data files we need
2.  Giving names for specific columns such as `subjectid`, `activityid`, `activity names`
3.  Merging training data and test data into one dataset(separately)
4.  Extracting variables which contain only `mean` and `standard deviation`
5.  From step 4, creating a new tidy data set with the average of each activity and each subject

Variables
------------------------------------------------------------
*  `test_x`,`test_y`,`train_x`,`train_y`contains the measured data for testing samples and training samples.  
*  `test_subject`,`train_subject` contains ID of the test/train subjects.  
*  `mrg_test`, `mrg_train` are the merged data of `test_y`+`test_subject`+`test_x` and 
`train_y`+`train_subject`+`train_x`.  
*  `features` are the names of variables of merged data.  
*  `activity_labels` are the types of activities.  
*  `mrg_test_msd`, `mrg_train_msd` are the selected data which only contains measurements
on the means and standard deviations.  
*  `all_data` is the combination of all testing and training data.  
*  `average_data` is the tidy data set with the average of each variable for each activity and each subject.  
*  finally, wrote the above data to `averages.txt`.  
#  I just put activity as 1st column and subject as 2nd column
