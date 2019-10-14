# Recurrent neural network (RNN)

**Simple RNN**

Train a simple RNN to do time-series prediction. Given some set of input data, it should be able to generate a prediction for the next time step! 

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/RNN/simple%20rnn.png)

**Sentiment Analysis with an RNN**

Implement a recurrent neural network that performs sentiment analysis. 
Using an RNN rather than a strictly feedforward network is more accurate since we can include information about the sequence of words. 
Here we'll use a dataset of movie reviews, accompanied by sentiment labels: positive or negative.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/RNN/sentirnn.png)

**Character-Level LSTM using RNN in PyTorch**

Constructing a character-level LSTM with PyTorch. The network will train character by character on some text, then generate new text character by character. As an example, I will train on Anna Karenina. This model will be able to generate new text based on the text from the book!
This network is based off of Andrej Karpathy's post on RNNs and implementation in Torch. Below is the general architecture of the character-wise RNN.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/RNN/crnn.png)
 
