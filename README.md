# Getting-and-cleaning-data
Data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone was retrieved, worked on, and cleaned, to prepare tidy data that can be analyzed later


## This repository contains the following files:

1. README.md, this file, which provides an overview of the data set and how it was created.
2. tidy_data.txt, which contains the data set.
3. CodeBook.md, the code book, which describes the contents of the dataset (data, variables and transformations used to generate the data).
4. run_analysis.R, the R script that was used to create the dataset (see the Creating the data set section below)


The R script run_analysis.R is used to create the dataset.
the run_analysis.py does the following :
1. Download and unzip source data if it doesn't exist.
2. Read data.
3. Merge the training and the test sets to create one data set.
4. Extract only the measurements on the mean and standard deviation for each measurement.
5. Use descriptive activity names to name the activities in the data set.
6. Appropriately label the data set with descriptive variable names.
7. Create a second, independent tidy set with the average of each variable for each activity and each subject.
8. Write the data set to the tidy_data.txt file.

# Requirements
dplyr package
