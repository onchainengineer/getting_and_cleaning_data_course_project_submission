# Getting And Cleaning Data Course Peer Graded Project Submission.

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. This **README.md** explains how all of the scripts work and how they are connected.

## Dataset

[Human Activity Recognition Using Smartphones](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Files

**CodeBook.md**, a code book that describes the variables, the data, and any transformations or work that we performed to clean up the data.

We have created one R script called ***run_analysis.R*** that does the following:

1.  Merges the training and the test sets to create one data set.

2.  Extracts only the measurements on the mean and standard deviation for each measurement.

3.  Uses descriptive activity names to name the activities in the data set.

4.  Appropriately labels the data set with descriptive variable names.

5.  From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

**CleanedDataSet.txt** is the exported final data after going through all the steps mentioned above.
