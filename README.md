# Getting-and-Cleaning-Data-Course-Project
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
# Source data set
The source data set that this project was based on was obtained from the Human Activity Recognition Using Smartphones Data Set. Training and test data were first merged together to create one data set, then the measurements on the mean and standard deviation were extracted for each measurement (79 variables extracted from the original 561), and then the measurements were averaged for each subject and activity, resulting in the final data set.
# Creating the data set
The R script run_analysis.R can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps (see the Code book for details, as well as the comments in the script itself):

	•	Download and unzip source data if it doesn't exist.
	•	Read data.
	•	Merge the training and the test sets to create one data set.
	•	Extract only the measurements on the mean and standard deviation for each measurement.
	•	Use descriptive activity names to name the activities in the data set.
	•	Appropriately label the data set with descriptive variable names.
	•	Create a second, independent tidy set with the average of each variable for each activity and each subject.
	•	Write the data set to the tidy_data.txt file.
