### Dataset
https://www.kaggle.com/dgawlik/nyse

The project uses the above dataset to visualize the information and predict future stock prices based on past daily stock price history. Short description of the files and datasets: 

1_data_analysis.ipynb : Visuals for the datasets can be found here. The number of rows, column headers and the top row data entries for each dataset.

1_data_visualization.ipynb : graphs for price histories of a few companies along with volume history of those companies. 

3_model_tests.ipynb : Predicts 'future' stock prices based on 'past' price history using LSTM model test for Exxon Mobil Corporation as a preliminary stage. 'Future' stock prices are the test datum while the training data is the 'past' price history. 

4_results.ipynb : In this file, LSTM is used to predict prices of 25 stocks. The lowest accuracy for this prediction is 95.7%, which is far more accurate than our anticipated 85% accuracy. 
