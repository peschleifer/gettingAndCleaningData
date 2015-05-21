---
title: "codebook"
author: "peschleifer"
date: "Thursday, May 21, 2015"
output: html_document
---

## Accelerometer Analaysis Summary Data
The file is formatted to be read with read.table with header=TRUE. Refer to the README file for details on how the data is generated and how to read the data file into R.

#### subjectId
Specifies the subject for this measurement. An integer. No further information about the sublect is available

#### activity
The activity the subject was performing during this measurement  
Laying  
Sitting  
Standing  
Walking  
Walking downstairs  
Walking upstairs

#### measurement
The name of the measurement recorded. More information about these in in the feature_info.txt file which will be in the data directory after the script is run.  
angle.tBodyAccJerkMean..gravityMean.  
angle.tBodyAccMean.gravity.  
angle.tBodyGyroJerkMean.gravityMean.  
angle.tBodyGyroMean.gravityMean.  
angle.X.gravityMean.  
angle.Y.gravityMean.  
angle.Z.gravityMean.  
fBodyAcc.meanFreq...X  
fBodyAcc.meanFreq...Y  
fBodyAcc.meanFreq...Z  
fBodyAcc.X  
fBodyAcc.Y  
fBodyAcc.Z  
fBodyAccJerk.meanFreq...X  
fBodyAccJerk.meanFreq...Y  
fBodyAccJerk.meanFreq...Z  
fBodyAccJerk.X  
fBodyAccJerk.Y  
fBodyAccJerk.Z  
fBodyAccMag  
fBodyAccMag.meanFreq..  
fBodyBodyAccJerkMag  
fBodyBodyAccJerkMag.meanFreq..  
fBodyBodyGyroJerkMag  
fBodyBodyGyroJerkMag.meanFreq..  
fBodyBodyGyroMag  
fBodyBodyGyroMag.meanFreq..  
fBodyGyro.meanFreq...X  
fBodyGyro.meanFreq...Y  
fBodyGyro.meanFreq...Z  
fBodyGyro.X  
fBodyGyro.Y  
fBodyGyro.Z  
tBodyAcc.X  
tBodyAcc.Y  
tBodyAcc.Z  
tBodyAccJerk.X  
tBodyAccJerk.Y  
tBodyAccJerk.Z  
tBodyAccJerkMag  
tBodyAccMag  
tBodyGyro.X  
tBodyGyro.Y  
tBodyGyro.Z  
tBodyGyroJerk.X  
tBodyGyroJerk.Y  
tBodyGyroJerk.Z  
tBodyGyroJerkMag  
tBodyGyroMag  
tGravityAcc.X  
tGravityAcc.Y  
tGravityAcc.Z  
tGravityAccMag  

#### mean
The average of the means recorded for this measurement. The raw data is normalized and bounded within [-1,1].

#### std
The avarage of the standard deviations recorded for this measurement. The raw data is normalized and bounded within [-1,1].
