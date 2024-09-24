**Comparing different Recurrent Neural Networks performance on Memorial University of Newfoundland (MUN) electric dataset** 

In this study, different Recurrent Neural Network (RNN) based time-series forecasting algorithms are applied to the electric load data obtained from the Memorial University of Newfoundland. These algorithms include Long Short Term Memory (LSTM), Gated Recurrent Network (GRU), Bi-GRU and Bi-LSTM. The data is trained on the previous week and its accuracy for the next day is measured using hourly forecasts. The accuracy of these algorithms is compared for day-ahead forecasting potential. Bi-GRU based RNN shows best performance among the tested algorithms with the highest R2 score and lowest Mean Absolute Error (MAE) and Mean Squared Error (MSE). 

**Dataset Used**

The study combines two sources of data. 

i) Monthly Meteroloical Data is pulled from weather.gc.ca 

ii) Load Time series is obtained from Memorial University of Newfoundland.

Both these datasets are combined and we obtain the file named Data.xlsx.

The basic network architecture is given below: 

![image](https://github.com/user-attachments/assets/253044cb-77d0-453f-9338-b1b53255618b)
