# CodeBook

This CodeBook presents the methodology applied to cleaning and tidying large data sets used in a study of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors (see . 

Data Sources
The data sets from the study collectively formed the Human Activity Recognition database, available here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.
- these were used as the basis for the Course Project.


Variables



Name | Description
----- | -----
Body Acc |
Gravity Acc |
Body Acc Jerk |
Body Angular Speed |
Body Angular Acc |
Body Acc Magnitude |
Gravity Acc Mag |
Body Acc Jerk Mag |
Body Angular Speed Mag |
Body Angular Acc Mag | 

Although the original study examined 561 features, the measures for computing feature vectors in the Course Project were limited to Mean Value (mean) and Standard Deviation (std).


Based on the requirements for the Course Project, there were 67 "grouped" Variables by sensor:

#### Sensor Groups
timeBodyAccelorometer
timeGravityAcceolometer
timeBodyAccelerometerJerk
timeBodyGyroscope
timeBodyGyroscopeJerk
timeBodyAccelerometerMagnitude
frequencyBodyAccelerometerJerkMagnitude
frequencyBodyGyroscopeMagnitude
frequencyBodyGyroscopeJerkMagnitude

#### Total number of variables
- activity (with 6 levels: 
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


