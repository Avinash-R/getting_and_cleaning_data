
  features-->import features.txt
  activityType-->import activity_label.txt
  subjectTrain-->import subject_train.txt
  xTrain-->import x-train.txt
  yTrain-->  import y_train.txt
  
  trainingData-->combining variables ytrain, subjectTrain, and xTrain by using cbind
  subjectTest-->import subject_test.txt
  xTest-->import x_test.txt
  yTest-->import y_test.txt
  testData-->combining variables yTest, subjectTest, and xTest by using cbind
  finalData-->combining variables TrainingData and testData by using rbind
  colNames-->retrieves the column names in finalData
  finalDataNoActivityTest-->select final data into new variable without activityType element
  tidyData-->aggregating and merging the variables tidyData and activityType (sorting by 'activityId')