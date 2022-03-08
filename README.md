# IncomePrediction-USCensusData
In this project I am using US Adult Census data relating income to social factors such as Age, Education, race etc. The Us Adult income dataset was extracted by Barry Becker from the 1994 US Census Database. The data set consists of anonymous information such as occupation, age, native country, race, capital gain, capital loss, education, work class and more. Each row is labelled as either having a salary greater than ">50K" or "<=50K". This Data set is split into two CSV files, named adult-training and adult-test. The dataset is made up of categorical and continuous features.   The goal here is to train a binary classifier on the training dataset to predict the column income bracket which has two possible values ">50K" and "<=50K" and evaluate the accuracy of the classifier with the test dataset. The following classifiers are evaluated: Logistic regression, neural networks, random forest, KNN and Adaboost classifier.
