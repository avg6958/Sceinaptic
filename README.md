# Sceinaptic
Data Exploration
# Scienaptic
Data Exploration - scienaptic

This is a data Exploration activity mainly for handling statistical data. This code divides the fields in input data into different categories - Categorical, Discrete, continuous and Text.
Based on the category of the field, we perfom different set of aggregatoins, like count of nulls, count of non-nulls, occurrence count,  word count if Text, MAX and MIN if Continuous, etc.
The category is decided by a threshhold which should be computed dynamically for each column depending upon input data size.


[ReadCSV is the main Scala class and build.sbt is config]
