# Stonks: Stock Market Prediction with Sentiment Analysis
Welcome to the Stonks📈 project! This repository contains my final year project, a comprehensive stock market prediction model that incorporates sentiment analysis to enhance accuracy✏️📏. By analyzing market sentiment from news articles, social media, and financial reports, this model aims to provide more reliable stock price predictions.
## 🗂️ Repository Structure:
1. **CompleteBackend**: The full project with all the necessary files and code for the stock market prediction model. This folder contains 5 files.
   1. 1_DataAcquisitionAndPreprocessing.ipynb: This file is used to acquire all the data required for training the model. This includes things like downloading financial stock data from Yahoo Finance and scraping news articles related to the stock in question from Google News. I have also scaled the data before ultimately saving it in an Excel sheet.
   2. 2_DataPreprocessingAndModelBuilding.ipynb: Here I further preprocessed the data using the 'Sliding Window' approach to create overlapping sequences which are used to train the model. I also created a stacked LSTM model, trained it and then saved it.
   3. 3_PredictionsAndInverseScaling.ipynb: Here I loaded the trained model and used it to make predictions using a test dataset I also created in this file.
   4. df_for_training.csv: Contains the scaled data used for training the model
   5. multivariate_lstm_model3.h5: The trained model which can be used to make predictions
2. **TestFolder**: Contains all the files created and used during the testing phase of the model.
