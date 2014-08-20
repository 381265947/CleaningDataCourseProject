CleaningDataCourseProject
=========================

Course Project for the "Getting and Cleaning Data" Coursera Class 

run the script run_analysis.R 

it expects the "UCI HAR Dataset" folder in the working directory.

the script works as follows:

* it loads and combines the test and training data 

* it keeps only the "mean" and "std" columns

* it appends the "subject" and "activity" columns

* it reshapes the data so there is only one row per "subject" and "activity" pair, averaging the other columns

* it creates a tidy "tidydata.txt" file

"codebook.txt" contains column names and explanations for the tidy data set.
