# Getting-and-Cleaning-Data-course-project
# 
This repo contains analysis of a dataset that contains accelerometer data. Each of 30 volunteers engaged in six activities, and a smartphone attached to their waist collected 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 

The analysis cleans and combines all the data provided, and outputs a second dataset with the mean of certain variables, by subject and activity. 
#
This repo contains the following files:
* 'README.md'
* 'Codebook.md'
* 'run_analysis.R': downloads data, cleans, and combines to result in the tidy data described above.
* 'tidy data.txt': sample output from run_analysis.R
#
The run_analysis code does the following to create the tidy dataset:
* Download and unzip the necessary file
* Combine the data files into one big table data frame
* Assign column headers, each with a unique name
* Extract only measurements on the mean and standard deviation of each variable
* Assign descriptive names to the activities
* Create a second data set that contains the mean of each variable

