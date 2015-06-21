# GettingCleaningData-CourseProject

Overview
The purpose of the Course Project was to demonstrate my ability to collect, manipulate, and ultimely transform a large amount of data into a clean and ultimely "tidy" data set.

Data Collection
The data files for the Project were made available from the UC Irvine Machine Learning Repository, based on a study of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The resulting data sets collectively formed the Human Activity Recognition database; the findings of the 


Transformation



Outcomes
The repository contains these files:

README.md
codebook.md
run_analysis.R
tidy_data.txt






There are five major processes to getting and cleaning data in the run_analysis.R file:

1. Reading in multiple data files
2. Combining data files
3. Creating subsets for only features that are a measurement of mean or SD (standard deviation)
4. Reading in activity labels that are applied to the subsets 
5. Reshaping of data into what is considered a tidy data set
6. Generating the tidy data set output.
7. 

The actual script was written as a function, see the run_analysis.R for details, but the sequence of properties within the function was as follows:


1. Reading in IDs for the 'train' and 'test' data sets - read.table
2. Combining 'train' and 'test' data sets into one data frame - rbind
3. Reading in the list of features, i.e. the labels
4. 



References

Anguita, D., Ghio, A., Oneto,L., Parra, X., and Reyes-Ortiz, J.L. (2013) A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. Retrieved from https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es2013-84.pdf
