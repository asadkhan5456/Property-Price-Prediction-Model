# Property Prediction Model

In this project we are going to build a machine learning model which will predict the property price based on the features in the dataset.

Terminology used to build the project:

1. Data Collection: In this stage we acquired the data. We have used the dataset from Kaggle.com after which we understand the data. As the data has 9 columns and total of 13320 rows. The main feature of the data is the price column which we want to predict through our model.
2. Data Preprocessing : In this we load the data into pandas dataframe by first importing all the required libraries for further Data Analysis and EDA.
3. Data Analysis : After loading the data we understand the various feature of the data and find out relationship between them through statistical measure.
4. Exploratory Data Analysis (EDA) : Here we start with Data cleaning by firstly checking for any missing value or duplicate value in the data and removing it after that we perform feature engineering methods such as one-hot encoding to remove outliers.
5. Model Development: Once the data was cleaned and outliers were handled the data was ready for further operation we then split the data into training and testing data, where we feed the training data to Machine learning model and train it and then test the model with the test data.
6. GridSearch CV : We feed our training data to different Machine learning model and find out which model has the best accuracy. And then we test the model.

Library used:
1. Pandas and Numpy [Data cleaning and EDA]
2. Matplotlib [Data Visualization]
3. Sklearn [Machine learning model development]



