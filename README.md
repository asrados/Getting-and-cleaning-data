# Introduction

This is the final course project for the Getting and Cleaning Data via Coursera course. The R script, run_analysis.R, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Read the data
3. Load the activity and feature information
4. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
5. Loads the activity and subject data for each dataset, and merges those columns with the dataset
6. Merges the two datasets
7. Converts the activity and subject columns into factors
8. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

About the Code Book
-------------------
The CodeBook.md file explains the transformations performed and the resulting data and variables.

The end result is shown in the tidy.txt file.
