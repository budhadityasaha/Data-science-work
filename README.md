## Project: Eye for Blind
#### Description: 
To create a deep learning model which can explain the content of an image in the form of speech through Caption generation with attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library.

#### Responsibilities
Data Understanding: Load the data and understand the representation
Data preprocessing: process both images & captions to the desired format.
Train/Test Split: Combine both images & captions to create the train & test dataset.
Model-Building: This is the stage where you will create your image captioning model by building Encoder , Attention & Decoder model
Model Evaluation: Evaluate the models using greedy search

## Project: Gesture recognition
#### Description: 
This project was all about developing a deep learning model for smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images) for various gestures and their labels. 

For analysing videos using neural networks, two types of architectures are used –
 1) 3D CNN &  
 2) 2D CNN with RNN.
 
#### Responsibilities
•	Build a custom data generator that can yield batch data and corresponding labels after pre-processing the images (centre crop, resize, normalization).<br>
•	Create a 3d convolutional network and train the model and make sure model able to produce good accuracy.<br>
•	Create a 2d convolutional network with LSTM/ GRU and make sure model able to produce good accuracy.<br>

## Project: Create a seq2seq model that can translate Bengali sentence to English
#### Description: 
The seq2seq models is normally composed of an encoder-decoder architecture, where the encoder processes the input sequence and encodes/compresses/summarizes the information into a context vector (also called as the “thought vector”) of a fixed length. The decoder is then initialized with this context vector, using which it starts generating the transformed output. The seq2seq models is normally composed of an encoder-decoder architecture, where the encoder processes the input sequence and encodes/compresses/summarizes the information into a context vector (also called as the “thought vector”) of a fixed length. The decoder is then initialized with this context vector, using which it starts generating the transformed output.

#### Responsibilities
•	Datacleaning and preprocessing the Bengali and English text <br>
•	Model-Building: This is the stage where you will create your image captioning model by building Encoder , Attention & Decoder model
•	Model Evaluation: Evaluate the models using greedy search

## Project: Generate text based on a character-level RNN model
#### Description: 
Using a given file having Shakespeare's text, build a character level RNN model that can generate text similar to given text
#### Responsibilities
•	The file contains Shakespeare'text which is having (having more than 5 million chars). Encode the text for modelling.
•	Create batch to feed the data for a fixed length after converting the text vector into a stream of character indices.
•	Build RNN model that can generate text based on previos character

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

