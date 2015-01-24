#Introduction

The script run_analysis.R performs the 5 steps described in the course project's definition.

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#Variables

Xtest, ytest, Xtrain, ytrain, subjecttest, and subjecttrain contain the data from the downloaded files.
activitylabels contains activity labels  
features contain data from features file
featuresextract contains mean and standard deviation for each measurement.
testdata containd data after binding subjecttest,ytest,Xtest
traindata contains data after binding subjecttrain,ytrain,Xtrain
data contains merged test and train data
id contains column names "subject","Activity_ID","Activity_Label"
datalabels contains data labels
meltdata contains melt data
tidydata contains the tidy data


