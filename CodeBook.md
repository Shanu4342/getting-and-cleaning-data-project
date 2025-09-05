# CodeBook

This CodeBook describes the variables, data, and transformations used to clean and create the tidy dataset.

## Data Source
- Original dataset: Human Activity Recognition Using Smartphones Dataset
- Collected using Samsung Galaxy S smartphone accelerometer and gyroscope

## Transformations
1. Merged training and test sets.
2. Extracted measurements on the mean and standard deviation.
3. Replaced activity codes with descriptive names.
4. Cleaned variable names for clarity.
5. Created tidy dataset with the average of each variable for each activity and subject.

## Variables
- **subject**: ID of the volunteer (1–30)
- **activity**: Activity performed (e.g., WALKING, SITTING, LAYING)
- **TimeBodyAccelerometerMeanX/Y/Z**
- **TimeBodyAccelerometerStdX/Y/Z**
- **TimeGravityAccelerometerMeanX/Y/Z**
- **FrequencyBodyGyroscopeMeanX/Y/Z**
- *(and many more mean/std features from accelerometer and gyroscope signals)*
