# MagicTG-ML
These are my machine learning explorations of Magic: The Gathering cards.

The first notebook I've added here is "Can you you predict Magic card Prices with ML."
In this project, I developed a function to pull Magic card price history from a the website MTGgoldfish and save it as a json file. You can use this function yourself for any card, you only need the URL of the card from MTGgoldfish. I explore this data in a pedagogical way: first naively applying ML to the data with good results, then revealing that my card's data is actualy random and unpredicatble, and finally treating the data in the appropriate way. I use several models to demonstrate how you can be tricked into thinking you can predict a random walk type time series: linear, NN, DNN, LSTM, DNN-LSTM. 
