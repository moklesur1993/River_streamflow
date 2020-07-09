# River_streamflow
Forecasting river_streamflow with long-short term memory neural network


LSTM is a type of recurrent neural network (RNN) architecture capable of learning long-term dependencies. LSTM is a well-suited tool to approximate a highly nonlinear approximation. LSTM uses computation graphs to approximate functions. Further information on LSTM computational units can be found here. The LSTM in this project is implemented in Keras. The steps applied are:

1. Prepare LSTM data: LSTM in Keras requires time series to be transformed into supervised learning, into input and output data. The data also need to be normalized within the scale of the activation function used by the network.
2. Develop LSTM model
3. Network parameters need to be specified: 
    Batch size
		Number of neurons
		Number hidden layer
		Optimizer
		Loss function
		Number of iteration (epoch)
4. Validate forecast: A testing data set will be used to evaluate network performance.
5. Parameter tuning: Model parameters will be tuned to optimize performance by training LSTM network under a different configuration of neurons, bach size, and epoch
