# ProjectCourse
CourseCode
It loads the train and test data sets and appends the two datasets into one data frame. This is done using rbind.
It extracts just the mean and standard deviation from the features data set. This is done using grep.
After cleaning the column names, these are applied to the x data frame.
After loading activities data set, it converts it to lower case using tolower and removes underscore using gsub. activity and subject column names are named for y and subj data sets, respectively.
The three data sets, x, y and subj, are merged. 
The mean of activities and subjects are created into a separate tidy data set which is exported into the Result folder as txt file; this is named average.txt.
