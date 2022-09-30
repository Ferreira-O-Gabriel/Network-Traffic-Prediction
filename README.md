# Network-Traffic-Prediction

This repository is part of the survey paper "Forecasting Network Traffic: A Survey and Tutorial with Open-Source Comparative Evaluation", that is 
concerned with mobile Network Traffic Prediction. In such a work, many different approaches applied to prediction models on the last 20 years 
are explained from a mathematical perspective, and simulations with a real world scenario data set are performed with six different approaches:
RNN, LSTM, GRU, CNN, SARIMA, and decomposed SARIMA. We provide a small version of the data set and the codes developed, so other researchers can 
compare their approaches with the ones we provided or even use them as a foundation for more advanced solutions.

The codes use 55 days of traffic load activity from the city of Milan to predict the time-series regarding the following 7 days. 
We provide a small pre-processed version of the data set and the entire one is publicly available in the Harvard Dataverse.

The codes are written in Python 3 and originally edited with Jupyter Notebook.
Install the required bibs and place the data set files in the same folder where you will run the codes.
