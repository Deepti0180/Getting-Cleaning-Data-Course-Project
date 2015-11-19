# Getting-Cleaning-Data-Course-Project

This is the course project for the Getting and Cleaning Data Coursera course. 

The R script, run_analysis.R, assumes the compressed data files are kept in current working directory and does the following:

1. Unzips the data files folder in current working directory.
2. Changes current working directory to unzipped data files folder.
3. Load the activity and feature info.
4. Reads both the training and test datasets and merges these data sets to create combined data set.
5. Extracts only the measurements on the mean and standard deviation for each measurement in features data set.
6. Use descriptive activity names to name the activities in the activities data set
7. Merges the features, activities and subject datasets in one dataset.
8. Create a second, independent tidy data set from combined dataset with the average of each variable for each activity and each subject pair.
9. The end result is saved in the file tidy.txt.

