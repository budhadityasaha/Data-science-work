## Project: Gesture recognition
#### Description: 
This project was all about building a deep learning model which can recognise five different gestures performed by the user which will can help users control the TV without using a remote. The dataset had around 650 videos (each having 30 frames) for various gestures and their labels.
#### Responsibilities
•	Build a custom data generator that can yield batch data and corresponding labels after pre-processing the images (centre crop, resize, normalization).<br>
•	Create a 3d convolutional network and train the model and make sure model able to produce good accuracy.<br>
•	Create a 2d convolutional network with LSTM/ GRU and make sure model able to produce good accuracy.<br>

## Project: Predicting Dow Jones using News Headlines using 1D CNN-RNN
#### Description: 
Assuming that news headlines that run on a particular day affect the opening stock price of an index the very next morning; build a model that can predict how much stock unit price will rise or fall based on a present day news headlines
#### Responsibilities
•	Given data contains news headlines for last few years on daily basis and another dataset has the stock price for that day <br>
•	Preprocess/datacleaning to make the data easer for embedding and modelling - 1) remove stopwords 2) Remove unwanted characters 3) decontract words <br>
•	Build a 1d CNN-RNN model that can model the relationship between the news and the stock market price of an index

## Project: Predict Telecom Churn
#### Description: 
In this project, based on customer-level data of a leading telecom firm, predictive models were built to identify customers at high risk of churn and identify the main indicators of churn. <br>
#### Responsibilities
•	The dataset had originally 95k records and 226 attributes. High value customers were extracted (around 30k) based on usage and revenue for the analysis. <br>
•	Based on network usage and other parameters for the high value customers, churn records were identified and used that as the target.<br>
•	Perform Exploratory Data Analysis (convert columns to appropriate formats, handle missing values, etc.), derive new features which could be important indicators of churn. <br>
•	Build predictive model which can be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc. It will be used to identify important variables that are strong predictors of churn. <br>
•	Also, since the rate of churn is typically low (about 5-10%, this is called class-imbalance) - used techniques like SMOTE to handle class imbalance. <br>
•	Since there are huge number of features, apply dimensionality reduction technique like PCA.<br>
•	Build variety of other models (ensemble models); do hyperpameter tuning for each of them, evaluate models using appropriate evaluation metrices.<br>

## Project: Predict housing prices in California 
#### Description
Based on data containing information from the 1990 California census, need to build an regression model (Ridge/ Lasso/ Elastic Net) to predict prices of house. This model will then be used by the management to understand how the house price is dependent on various features. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.<br>
#### Responsibilities
•	The dataset has 80 variables related to a house. All data quality checks are performed, and all data quality issues are addressed in the right way (missing value imputation, removing duplicate data and other kinds of data redundancies, etc.). Data quality issues are clearly explained in comments. <br>
•	Do feature engineering to come up with new features that can be used to predict price.<br>
•	Check multicollinearity and take necessary action. Check relationship with target variables and take appropriate step to make sure they are normally distributed.<br>
•	Build regression model (Ridge/ Lasso/ Elastic Net) using regularization to predict prices of house. <br>

