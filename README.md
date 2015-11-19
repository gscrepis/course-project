Getting and Cleaning Data - Course Project
==========================================

This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output is called `tidy_data.txt`, and uploaded in the course project's form.


## Steps to work on this course project

1. Download the data source, unzip the file and put into a folder on your local drive. You'll have a ```UCI HAR Dataset``` folder.

2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```.

3. Run ```source("run_analysis.R")```, then it will generate a new file ```tidy_data.txt``` in your working directory.
