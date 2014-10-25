Getting and Cleaning Data: Course Project
=========================================

Introduction
------------
This repository contains the course project submission for the Coursera course "Getting and Cleaning data"

The analysis script and output
-------------------------------------
The script name is run_analysis.R and it will merge the test and training sets together.
Prerequisites for this script:

1. the UCI HAR Dataset must be Downloaded from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip .
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

The script then creates a tidy data set containing the means of all the columns per test subject and per activity.
This tidy dataset will be written to a tab-delimited file called tidy.txt.

The Code Book
-------------------
The CodeBook.md file explains the variables used and transformations performed.
