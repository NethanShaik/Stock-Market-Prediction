# Stock-Market-Prediction

In this project, the task is to develop a Stock Price Prediction for the desired ticker. For this
problem, I have used the LSTM algorithm to develop and predict the stock price of a company.
For this project, I will be using the Apple Stock market with historical data of 5 years.


**Long Short Term Memory (LSTM)**

![image](https://github.com/NethanShaik/Stock-Market-Prediction/assets/66028026/cc1e5f72-ac33-4472-a290-c2d4495188e1)



LSTM is a type of recurring neural network which deals with the vanishing gradient problem that is
usually occurred in typical recurring neural network models. It provides a short term memory that
is usually held for some timesteps. 

The LSTM uses three gates that perform the following operations:
1. Forget Gate: This decides which information is to be kept and discarded. These values are
passed to the sigmoid function, which provides only output values of 0 meaning the old
information can be discarded to make way for possible new important information and 1
meaning that the previous information is kept.
2. Input Gate: This decides how important the present input is to solve a given problem. The
new input is multiplied by the hidden state and the weight matrix of the last run. The important
information is inserted into the cell state which is the current state of the long-term memory
and will be used in the next run.
3. Output Gate: In this gate, the output is then calculated in the hidden state and in order to do
this, the sigmoid function decides what information can be passed through the output gate
and after that the cell state will be multiplied after it is activated with tanh function.

Output

<img width="286" alt="image" src="https://github.com/NethanShaik/Stock-Market-Prediction/assets/66028026/ac4b5b88-77a1-4746-8334-7ef49b7d3cb4">

![image](https://github.com/NethanShaik/Stock-Market-Prediction/assets/66028026/14d414a5-ee66-4f1d-9922-4155ce3212e3)

