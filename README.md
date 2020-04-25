# Machine-Translation-with-Keras
This is an implementation of a series of RNNs culminating in a bidirectional RNN model for machine translation written in Keras. It builds off of the basic Keras sequential model with: LSTM, dropout, and word embeddings. In this particular model we use the Adam optimizer, categorical cross-entropy and a softmax activation.


It is built in approximately the following manner:
Import
Tokenize
Pad
Preprocess
At this point I implemented a few different model types:

A simple RNN
An Embedded model
A Bidirectional RNN
Finally, I built multilevel Bidirectional RNN implemented with dropout and softmax activation.
