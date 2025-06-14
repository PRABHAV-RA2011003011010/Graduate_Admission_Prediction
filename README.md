# Deep Learning Notes
# Project Flow
## Data Preprocessing
-->Check for null values<br>
-->Check for duplicated<br>
## EDA
-->Check for outliers(using methods like box plot)<br>
## Data preparation
-->apply train_test_split on input and output columns<br>
-->apply label encoder on the output columns if it is a classification problem<br>
-->apply normalization or standardization to scale the input data only<br>
-->the scaler should be fit only on train data, after fitting the data on the train data use this scaler to scale the test data also.<br>
## Neural Network Preparation
-->import necessary DL modules and create an NN architecture.<br>
-->create NN layers using Dense, add loss function and optimizer.<br>
-->Once architecture is ready fit the test data(both input and output) to the architecture and let it get trained.<br>
## Model Evaluation
-->
## Key Points
-->Fit is the process where the model gets all its trainable parameters trained and set to go.<br>
