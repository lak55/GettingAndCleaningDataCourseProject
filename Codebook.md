VARIABLES

1. dataActivityTest, dataActivityTrain, dataSubjectTest, dataSubjectTrain, dataFeatureTest and dataFeatureTrain contain the data from the downloaded files.

2. dataSubject, dataActivity and dataFeatures merged the previous datasets formed Data for further analysis.

3. dataFeaturesNames contains the correct names for the Data dataset, which are applied to the column names stored in subdataFeaturesNames, a numeric vector used to extract the desired data.

4. facorize Variale activity in the data frame Data using descriptive activity names through the activityLabels variable.

5. Data2 merges dataSubject, dataActivity and dataFeatures in a big dataset.

6. Finally, Data2 contains the relevant averages which will be later stored in a tidydata.txt file. Aggregate() from the plyr package is used to apply mean().
