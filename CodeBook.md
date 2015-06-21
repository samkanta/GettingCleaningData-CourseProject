# CodeBook

This CodeBook presents the methodology applied to cleaning and tidying large data sets used in a study of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors (see Anguita, Ghio, Oneto, Parra, & Reyes-Ortiz, 2013). 

Data Sources
The data sets from the study collectively formed the Human Activity Recognition database, available here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.
- these were used as the basis for the Course Project.

Data Transformation
The raw data sets were processed with the run_analysis.R script. Within the script, the following...





Variables
Although the original study examined 561 features, the measures for computing feature vectors in the Course Project were limited to Mean Value (mean) and Standard Deviation (std).


Based on the requirements for the Course Project, there were 67 "grouped" Variables by sensor:


Sensor Name | Measures
----- | -----
Body Acc | timeBodyAccelorometer 
Gravity Acc | timeGravityAcceolometer
Body Acc Jerk | timeBodyAccelerometerJerk
Body Angular Speed | timeBodyGyroscope
Body Angular Acc | timeBodyGyroscopeJerk
Body Acc Magnitude | timeBodyAccelerometerMagnitude
Gravity Acc Mag | frequencyBodyAccelerometerJerkMagnitude
Body Acc Jerk Mag | frequencyBodyGyroscopeMagnitude
Body Angular Speed Mag | frequencyBodyGyroscopeJerkMagnitude
Body Angular Acc Mag | frequencyBodyAccelerometerMagnitude



Measurement Groups 

#### Total number of variables
- activity (with 6 levels: *standing, sitting, laying
down, walking, walking downstairs and upstairs*
- timeBodyAccelerometer-mean()-X
- timeBodyAccelerometer-mean()-Y
- timeBodyAccelerometer-mean()-Z
- timeBodyAccelerometer-std()-X
- timeBodyAccelerometer-std()-Y
- timeBodyAccelerometer-std()-Z
- timeGravityAccelerometer-mean()-X
- timeGravityAccelerometer-mean()-Y
- timeGravityAccelerometer-mean()-Z
- timeGravityAccelerometer-std()-X
- timeGravityAccelerometer-std()-Y
- timeGravityAccelerometer-std()-Z
- timeBodyAccelerometerJerk-mean()-X
- timeBodyAccelerometerJerk-mean()-Y
- timeBodyAccelerometerJerk-mean()-Z
- timeBodyAccelerometerJerk-std()-X
- timeBodyAccelerometerJerk-std()-Y
- timeBodyAccelerometerJerk-std()-Z
- timeBodyGyroscope-mean()-X
- timeBodyGyroscope-mean()-Y
- timeBodyGyroscope-mean()-Z
- timeBodyGyroscope-std()-X
- timeBodyGyroscope-std()-Y
- timeBodyGyroscope-std()-Z
- timeBodyGyroscopeJerk-mean()-X
- timeBodyGyroscopeJerk-mean()-Y
- timeBodyGyroscopeJerk-mean()-Z
- timeBodyGyroscopeJerk-std()-X
- timeBodyGyroscopeJerk-std()-Y
- timeBodyGyroscopeJerk-std()-Z
- timeBodyAccelerometerMagnitude-mean()
- timeBodyAccelerometerMagnitude-std()
- timeGravityAccelerometerMagnitude-mean()
- timeGravityAccelerometerMagnitude-std()
- timeBodyAccelerometerJerkMagnitude-mean()
- timeBodyAccelerometerJerkMagnitude-std()
- timeBodyGyroscopeMagnitude-mean()
- timeBodyGyroscopeMagnitude-std()
- timeBodyGyroscopeJerkMagnitude-mean()
- timeBodyGyroscopeJerkMagnitude-std()
- frequencyBodyAccelerometer-mean()-X
- frequencyBodyAccelerometer-mean()-Y
- frequencyBodyAccelerometer-mean()-Z
- frequencyBodyAccelerometer-std()-X
- frequencyBodyAccelerometer-std()-Y
- frequencyBodyAccelerometer-std()-Z
- frequencyBodyAccelerometerJerk-mean()-X
- frequencyBodyAccelerometerJerk-mean()-Y
- frequencyBodyAccelerometerJerk-mean()-Z
- frequencyBodyAccelerometerJerk-std()-X
- frequencyBodyAccelerometerJerk-std()-Y
- frequencyBodyAccelerometerJerk-std()-Z
- frequencyBodyGyroscope-mean()-X
- frequencyBodyGyroscope-mean()-Y
- frequencyBodyGyroscope-mean()-Z
- frequencyBodyGyroscope-std()-X
- frequencyBodyGyroscope-std()-Y
- frequencyBodyGyroscope-std()-Z
- frequencyBodyAccelerometerMagnitude-mean()
- frequencyBodyAccelerometerMagnitude-std()
- frequencyBodyAccelerometerJerkMagnitude-mean()
- frequencyBodyAccelerometerJerkMagnitude-std()
- frequencyBodyGyroscopeMagnitude-mean()
- frequencyBodyGyroscopeMagnitude-std()
- frequencyBodyGyroscopeJerkMagnitude-mean()
- frequencyBodyGyroscopeJerkMagnitude-std()




References

Anguita, D., Ghio, A., Oneto,L., Parra, X., and Reyes-Ortiz, J.L. (2013) A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. Retrieved from https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es2013-84.pdf
