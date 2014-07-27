Getting and Cleaning Data Course Project.
=========================================

                                                                                                                                                                                                                                                

##### This file shows how **run_analysis.r** script works.


1. Here the data is downloaded from the link provided [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip), extracted from its archive and saved it and rename the folder with "data".

2. Second, use source("run_analysis.r") command in RStudio.

3. Folder "data" and the run_analysis.R script are both in the current working directory.

4. In the current working directory we find two output files:
    1. mergeddata.txt (7.9 Mb): it contains a data frame called cleanedData with 10299x68 dimension.
    2. datawithmeans.txt (220 Kb): it contains a data frame called result with 180x68 dimension.
    
    
5. Lastly, use data <- read.table("datawithmeans.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features.

