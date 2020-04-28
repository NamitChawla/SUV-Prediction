# SUV-Prediction
Here's a step-wise guide to working with SUV dataset:
1) First, we need to import the required libraries. We can import either all the libraries at once or we can import them when they are needed.
### READING DATA
1) Reading the CSV file and displaying some of the data using head() function, to check how the data is structured in the CSV file.
### FEATURE ENGINEERING
1) Now, we must look for null values in the dataset, if any, then we must either replace them with dummy values or based on any mathematical statistics namely- mean, mode, median etc.
2) As per dataset, It is a necessary part to know the dependent and independent features in the given problem, to build a more efficient system.
### DATA PREPROCESSING
1) As part of data preprocessing, first we perform standardization of the dataset because it is import for many machine learning estimators as they could behave not up to the mark if the individual features do not look more or less likely as a normally distributed data.
2) The standardization is performed on both training and testing data.
### FIT MODEL
1) After following the whole machine learning cycle, now we are fully prepared to fit the model. 
### PREDICTIONS
1) After model.fit() is performed we are all set to predict results and measure our model's accuracy. 
