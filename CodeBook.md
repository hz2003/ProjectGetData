# CodeBook

This is a code book that describes the variables, the data, and the transformations to clean up the data.

# The Data

The dataset includes the following files:

- README.txt

- features.txt

- features_info.txt

- activity_labels.txt

- test/X_test.txt

- test/y_test.txt

- test/subject_test.txt

- train/X_train.txt

- train/y_train.txt

- train/subject_train.txt

# Transformation Details

1. Retrieves the test data set and the training data set
2. Change column names according to features
3. Extracts the measurements on the mean and standard deviation from features
4. Appropriately labels the data set with descriptive activity names
5. Binds the test and training data
6. Creates tidy data set with the average of each variable for each activity and each subject.

