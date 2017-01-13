# Getting and Cleaning Data
## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## run_analisys.R explanation
1. The run_analisys.R function will create a libray called "data" in your WD 
2. The run_analisys.R function download and extract the zip file from the url and create a sub directory "UCI HAR Dataset"
3. The run_analisys.R function will load the libraries: dplyr, data.table, tidyr and reshape2
4. The run_analisys.R function Extracts only the measurements on the mean and standard deviation for each measurement
5. The run_analisys.R function Uses descriptive activity names to name the activities in the data set
6. The run_analisys.R function Appropriately labels the data set with descriptive variable names.
7. The run_analisys.R function Merges the training and the test sets to create one data set
8. The run_analisys.R function creates a second, independent tidy data set with the average of each variable for each activity and each subject

## Considerations
Tne run_analisys.R function will load the libraries: dplyr, data.table, tidyr and reshape2

Downliad the run_analisys.R function to your Working Directory and load it into R
