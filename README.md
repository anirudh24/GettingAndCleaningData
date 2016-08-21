Getting and Cleaning Data - Project
===================================

Introduction
------------
This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization.
What follows first are my notes on the original data.

About the raw data
------------------
The features are in x_test.txt.
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

About the script and the tidy dataset
-------------------------------------
Created a script called run_analysis.R which will merge the test and training sets together.
Prerequisites for this script:
1. the UCI HAR Dataset must be extracted and..
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.
The script will create a tidy data set containing the means of all the columns per test subject and per activity.
This tidy dataset will be written to a tab-delimited file called tidyData.txt, which can also be found in this repository.

About the Code Book
-------------------
The CodeBook.md file has the data set information.
