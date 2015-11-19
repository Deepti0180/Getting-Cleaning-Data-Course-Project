This code book summarizes the variables along with necessary information in tidy_data.txt.

###########  Variables #################
•	x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
•	x_data, y_data and subject_data merge the previous datasets to further analysis.
•	features contains the correct names for the x_data dataset, which are applied to the column names stored in mean_and_std_features, a   numeric vector used to 	extract the desired data.
•	A similar approach is taken with activity names through the activities variable.
•	all_data merges x_data, y_data and subject_data in a big dataset.
•	Finally, tidy_data contains the relevant averages which will be later stored in tidy_data.txt file. ddply() from the plyr package is used to apply colMeans().

####### Measurements ##################
tBodyAccMeanX
tBodyAccMeanY
tBodyAccMeanZ
tBodyAccStdX
tBodyAccStdY
tBodyAccStdZ
tGravityAccMeanX
tGravityAccMeanY
tGravityAccMeanZ
tGravityAccStdX
tGravityAccStdY
tGravityAccStdZ
tBodyAccJerkMeanX
tBodyAccJerkMeanY
tBodyAccJerkMeanZ
tBodyAccJerkStdX
tBodyAccJerkStdY
tBodyAccJerkStdZ
tBodyGyroMeanX
tBodyGyroMeanY
tBodyGyroMeanZ
tBodyGyroStdX
tBodyGyroStdY
tBodyGyroStdZ
tBodyGyroJerkMeanX
tBodyGyroJerkMeanY
tBodyGyroJerkMeanZ
tBodyGyroJerkStdX
tBodyGyroJerkStdY
tBodyGyroJerkStdZ
tBodyAccMagMean
tBodyAccMagStd
tGravityAccMagMean
tGravityAccMagStd
tBodyAccJerkMagMean
tBodyAccJerkMagStd
tBodyGyroMagMean
tBodyGyroMagStd
tBodyGyroJerkMagMean
tBodyGyroJerkMagStd
fBodyAccMeanX
fBodyAccMeanY
fBodyAccMeanZ
fBodyAccStdX
fBodyAccStdY
fBodyAccStdZ
fBodyAccMeanFreqX
fBodyAccMeanFreqY
fBodyAccMeanFreqZ
fBodyAccJerkMeanX
fBodyAccJerkMeanY
fBodyAccJerkMeanZ
fBodyAccJerkStdX
fBodyAccJerkStdY
fBodyAccJerkStdZ
fBodyAccJerkMeanFreqX
fBodyAccJerkMeanFreqY
fBodyAccJerkMeanFreqZ
fBodyGyroMeanX
fBodyGyroMeanY
fBodyGyroMeanZ
fBodyGyroStdX
fBodyGyroStdY
fBodyGyroStdZ
fBodyGyroMeanFreqX
fBodyGyroMeanFreqY

#############  Activity Labels  ############
LAYING
SITTING
STANDING
WALKING
WALKING_DOWNSTAIRS
WALKING_UPSTAIRS

