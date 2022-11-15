# Getting-and-cleaning-data-course-project
This is the course project of Getting and Cleaning Data Course by Johns Hopkins University on Coursera. I have used R 4.2.1 and RStudio.

# Dataset
Human Activity Recognition Using Smartphones

# Files
* CodeBook.md a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

* run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
      * Merges the training and the test sets to create one data set.
      * Extracts only the measurements on the mean and standard deviation for each measurement.
      * Uses descriptive activity names to name the activities in the data set
      * Appropriately labels the data set with descriptive variable names.
      * From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
* FinalData.txt is the exported final data after going through all the sequences described above.

# Steps for execution:
1.Download the data set and unzip the folder
2.load the dplyr package with library(dplyr)
3.changed the paths in run_analysis.R
4.run the R script
