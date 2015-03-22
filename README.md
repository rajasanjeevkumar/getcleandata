# getcleandata
There are a total of 42 commands in run_analysis.R
1) The first 9 commands reads 9 text files related to TRAINING data. All the commands related to train dataset ends with text 'train'
2)Binding these values to a data table and this data table contains 9 columns
3)The next 9 commands reads 9 text files related to TEST data. All the commands ends with text 'test'
4)Binding these values to a new data table having 9 columns
5)The next 2 commands assigns explanatory column names for these 9 columns
6)The next 4 commands are used to load user's data of both TRAINING and TEST data.
7)Reassigns column name as 'User'
8)The next 4 commands are related to 6 activities
9)Renames columns as Activity
10) The next two commands help in mutating from activity numbers to activity text values
11)Reads features.txt and assigns column values to the two training and test datasets
12) The last 3 commands merges TEST and TRAINING data into one dataset.
