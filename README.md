# Getting and Cleaning Data
## Transformation Details
The following steps are performed in order to tranform the data and obtain a new data set:

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive activity names.
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## How to get the script running on your local PC?
1. Create a temporary directory somewhere on your local drive and name it *temp_dir*.
2. Download the raw data set from [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip), unzip and move the extracted directory *UCI HAR Dataset* to the directory *temp_dir*.
3. Download *run_analysis.R* and move it to *temp_dir*.
4. Set *temp_dir* as working directory.
5. Run *run_analysis.R*, it should generate the new dataset *tiny_data.txt* in the working directory.

## Dependencies