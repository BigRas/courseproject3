## Code Book

### Files in Dataset
1.    activity_labels.txt
2.    features.txt
3.    features_info.txt
4.    README.txt
5.    Test 
      1. subject_test.txt
      2. X_test.txt
      3. Y_test.txt
 6.   train
      1. subject_tarin.txt
      2. X_train.txt
      3. Y_train.txt

### Source of Data
The below link is the source of data for the project.
      https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip!
      
Dataset consists of two data sets called "test" and "train". And each one has "subject", "activity", and "features".
To have one dataset, all the datasets were merged.
The process of merging datasets is listed below:
1. Merging test subject and train subject
2. Merging data of test and data of train
3. Reading the Feature.txt file and extract measurements which have the mean and standard deviation and merge it with dataset of second stage

### Descriptive Names
In the dataset follwoing names have been changed.
*     "std"       was replaed with        "SD",
*     "mean"      was replaed with        "MEAN"
*     "t"        was replaed with        "Time"
*     "Acc"       was replaed with        "Accelerometer"
*     "Mag"       was replaed with        "Magnititude"
*     "f"         was replaed with        "Frequency"
*     "BodyBody"  was replaed with        "Body"
*     "Gyro"      was replaed with        "Gyroscope"


### output 
out put of the code is Tidydata.txt
