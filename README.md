# GettingCleaningData-CourseProject

## Overview
The purpose of the Course Project was to demonstrate my ability to collect, manipulate, and ultimely transform a large amount of data into a clean and ultimely "tidy" data set.

## Repo Contents

File | Description
:------ | ----------
README.md | This document, explains the contents of the Repo and their relationship to each other.
codebook.md | Describes the variables, data and process undertaken to clean and tidy data sets.  
run_analysis.R | The R Script that, when run, executes a multi-process function for the getting and cleaning of data.
tidy_data.txt | The output of the R Script, meeting the criteria of "tidy" data.

## Data Source
The data files for the Project were made available from the UC Irvine Machine Learning Repository, 


## The Data Analysis [run_analysis.R]

There are five (5) major processes to getting and cleaning data in the **run_analysis.R** file:

1. Reading in multiple data files
2. Combining data files
3. Creating subsets for only features that are a measurement of mean or SD (standard deviation)
4. Reading in activity labels that are applied to the subsets 
5. Reshaping of data into what is considered a tidy data set
6. Generating the tidy data set output.
7. 

The actual script was written as a *function*, see the run_analysis.R for details, but the sequence of arguments within the function were:

1. Reading in IDs for the 'train' and 'test' data sets - read.table
2. Combining 'train' and 'test' data sets into one data frame - rbind
3. Reading in the list of features, i.e. the labels
4. Subset the mean and std results - grep
5. 
6. 
7. Generate the output of the tidy data into a text file  - write.table

## Output [tidy_data.txt] 
The output from the run_analysis.R script was a data file containing the final tidy data set. The three conditions for 'tidy' data, according to Wickham (2014):
 1. Each type of observational unit forms a table
 2. Each variable forms a column
 3. Each observation (case) forms a row
 

## Reference
Wickham, H. (2014). Tidy Data. *Journal of Statistical Software, 59 (10)*, 1-23. Retrieved from http://www.jstatsoft.org/v59/i10/paper
