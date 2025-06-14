# Deep Learning Notes
# ANN Project Flow
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
Note:
-->If it's a regression problem use linear in the last layer.
-->If it's classification problem use sigmoid or soft max
## Model Evaluation
-->To validate your model give the input test data and capture all the outputs.
-->Compare the outputs given by the model with the actual outputs in test using a loss function and check the performance of thr model.
-->LossFunctions for regression: r2_score,
-->LossFunctions for classification:
## Key Points
-->Fit is the process where the model gets all its trainable parameters trained and set to go.<br>
