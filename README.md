# Getting-and-Cleaning-Data-Assignment
By Minoli Ekanayake
The libraries used in this operation are dplyr
The supporting metadata in this data are the name of the features and the name of the activities. They are loaded into variables featureNames and activityLabels
The training and test data sets are loaded
The columns in the features data set can be named from the metadata in featureNames
The data in features,activity and subject are merged and the complete data is now stored in completeData
Only the measurements on the mean and standard deviation for each observation are etracted
Descriptive activity names are used to name the activities in the data set
By examining extractedData, we can say that the following acronyms can be replaced:
  Acc can be replaced with Accelerometer
  Gyro can be replaced with Gyroscope
  BodyBody can be replaced with Body
  Mag can be replaced with Magnitude
  Character f can be replaced with Frequency
  Character t can be replaced with Time
'Subject' is set as a factor variable
Create tidyData as a data set with average for each activity and subject. 
Order the enties in tidyData and write it into data file Tidy.txt containing the processed data.
