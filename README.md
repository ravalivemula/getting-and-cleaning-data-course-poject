# getting-and-cleaning-data-course-poject
The steps involved in the transformation process are:
•	Merge the training and test data sets to create a new single dataset.
•	Then we have to extract the data for which the mean and standard deviation are available.
•	Giving descriptive names to the activities involved to the dataset
•	Labelling the datasets with descriptive variable names.
•	Finally create a separate tidy dataset which creates the average of each variable, for all the activities performed on the dataset.

Steps involved in the overall process:
•	Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
•	Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd()function in RStudio.
•	Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
