This script will process the Samsung HAR data to arrive at a tidy data set summarizing the mean value of each combination of subject and activity (30 subjects x 6 activities = 180 total permutations) across the 86 variables in the dataset relating to mean or std deviation

The original data set from which the 86 variables derive is 561 variables long; the remainder of these variables do not relate to means or std dev of HAR measurements

Please note that the user will have to set their own local working directory path between the quotes in the home_directory variable for the script to work; this also assumes that the raw data is in this home directory in the same subfolder structure as initially presented. This relative folder structure can be derived, if necessary, from the read.table statements early in the code.
