Practical Machine Learning Exercise_Predict.Rmd
Version 1.0
=========

Please look at the html file associated with the Exercise_Predict.Rmd

This repository contains a Rmd file, final data set, code book, and README for the Practical Machine Learning course project through Coursera and Johns Hopkins University.


The run_analysis.R script downloads and unzips (if it doesn't already exist in your working directory) a data set collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The run_analysis.R script creates a tidy, well labeled data set consisting of all thirty subjects, the six types of activities that were tracked by the accelerometers, and only the variables that contains mean or standard deviation observations.  Lastly, the run_analysis.R script calculates the average for each variable based for each subject for each activity.

For each record it is provided:
======================================

- Its subject label. 
- Its activity label. 
- A 79-feature vector with average mean and standard deviation variables.

The dataset includes the following files:
=========================================

- 'README.md'

- 'run_analysis.R': script for processing the accelerometer data into a clean data set.

- 'tidy_data.txt': The final data set produced by the run_analysis.R script.

- 'code_book.txt': Shows information about the variables used in the run_analysis.R script.

Notes: 
======
- The run_analysis.R script takes a few minutes to run because it was written with effectiveness and not efficiency in mind.

For more information about this dataset contact: activityrecognition@smartlab.ws
