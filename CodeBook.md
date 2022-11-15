Getting and Cleaning Data Course Project Code Book

Data was Transformed by applying:
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names.
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Identififiers
The first two columns - Subject and Activity - are Identifiers.
Subject: the ID of the Subject
Activity: the Name of the Activity performed by the subject when measurements were taken.

Measurements
As mentioned above,the variables remaining are just the calculatd means and standard deviations of these sets of data: (Even if I do not give a detailed description of what each data value means, you can see what it means by comparing it with the original data column.)
TimeBodyaccelerometer.mean...X
TimeBodyaccelerometer.mean...Y
TimeBodyaccelerometer.mean...Z
TimeGravityaccelerometer.mean...X
TimeGravityaccelerometer.mean...Y
TimeGravityaccelerometer.mean...Z
TimeBodyaccelerometerJerk.mean...X
TimeBodyaccelerometerJerk.mean...Y
TimeBodyaccelerometerJerk.mean...Z
TimeBodyGyroscope.mean...X
TimeBodyGyroscope.mean...Y
TimeBodyGyroscope.mean...Z
TimeBodyGyroscopeJerk.mean...X
TimeBodyGyroscopeJerk.mean...Y
TimeBodyGyroscopeJerk.mean...Z
TimeBodyaccelerometerMagnitude.mean..
TimeGravityaccelerometerMagnitude.mean..
TimeBodyaccelerometerJerkMagnitude.mean..
TimeBodyGyroscopeMagnitude.mean..
TimeBodyGyroscopeJerkMagnitude.mean..
FrequencyBodyaccelerometer.mean...X
FrequencyBodyaccelerometer.mean...Y
FrequencyBodyaccelerometer.mean...Z
FrequencyBodyaccelerometer.meanFreq...X
FrequencyBodyaccelerometer.meanFreq...Y
FrequencyBodyaccelerometer.meanFreq...Z
FrequencyBodyaccelerometerJerk.mean...X
FrequencyBodyaccelerometerJerk.mean...Y
FrequencyBodyaccelerometerJerk.mean...Z
FrequencyBodyaccelerometerJerk.meanFreq...X
FrequencyBodyaccelerometerJerk.meanFreq...Y
FrequencyBodyaccelerometerJerk.meanFreq...Z
FrequencyBodyGyroscope.mean...X
FrequencyBodyGyroscope.mean...Y
FrequencyBodyGyroscope.mean...Z
FrequencyBodyGyroscope.meanFreq...X
FrequencyBodyGyroscope.meanFreq...Y
FrequencyBodyGyroscope.meanFreq...Z
FrequencyBodyaccelerometerMagnitude.mean..
FrequencyBodyaccelerometerMagnitude.meanFreq..
FrequencyBodyaccelerometerJerkMagnitude.mean..
FrequencyBodyaccelerometerJerkMagnitude.meanFreq
FrequencyBodyGyroscopeMagnitude.mean..
FrequencyBodyGyroscopeMagnitude.meanFreq..
FrequencyBodyGyroscopeJerkMagnitude.mean..
FrequencyBodyGyroscopeJerkMagnitude.meanFreq..
Angle.TimeBodyaccelerometerMean.gravity.
Angle.TimeBodyaccelerometerJerkMean..gravityMean.
Angle.TimeBodyGyroscopeMean.gravityMean.
Angle.TimeBodyGyroscopeJerkMean.gravityMean.
Angle.X.gravityMean.
Angle.Y.gravityMean.
Angle.Z.gravityMean.
TimeBodyaccelerometer.std...X
TimeBodyaccelerometer.std...Y
TimeBodyaccelerometer.std...Z
TimeGravityaccelerometer.std...X
TimeGravityaccelerometer.std...Y
TimeGravityaccelerometer.std...Z
TimeBodyaccelerometerJerk.std...X
TimeBodyaccelerometerJerk.std...Y
TimeBodyaccelerometerJerk.std...Z
TimeBodyGyroscope.std...X
TimeBodyGyroscope.std...Y
TimeBodyGyroscope.std...Z
TimeBodyGyroscopeJerk.std...X
TimeBodyGyroscopeJerk.std...Y
TimeBodyGyroscopeJerk.std...Z
TimeBodyaccelerometerMagnitude.std..
TimeGravityaccelerometerMagnitude.std..
TimeBodyaccelerometerJerkMagnitude.std..
TimeBodyGyroscopeMagnitude.std..
TimeBodyGyroscopeJerkMagnitude.std..
FrequencyBodyaccelerometer.std...X
FrequencyBodyaccelerometer.std...Y
FrequencyBodyaccelerometer.std...Z
FrequencyBodyaccelerometerJerk.std...X
FrequencyBodyaccelerometerJerk.std...Y
FrequencyBodyaccelerometerJerk.std...Z
FrequencyBodyGyroscope.std...X
FrequencyBodyGyroscope.std...Y
FrequencyBodyGyroscope.std...Z
FrequencyBodyaccelerometerMagnitude.std..
FrequencyBodyaccelerometerJerkMagnitude.std..
FrequencyBodyGyroscopeMagnitude.std..
FrequencyBodyGyroscopeJerkMagnitude.std..

Activity Labels
1.WALKING
2.WALKING_UPSTAIRS
3.WALKING_DOWNSTAIRS
4.SITTING
5.STANDING
6.LAYING
