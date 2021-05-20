# VUI-Speech-Recognition
Speech recognition using different DNNs

In this project i have tried Spectrogram as an audio feature representation with 161 features (however the reviewer suggested to use MFCC(Mel-Frequency Cepstral Coefficients) as the Data isn't very big and MFCC will produce only 13 features and avoid the overfitting in this case)

After that i tried to train different Deep Neural Networks for Acoustic Modeling and compared their losses.

1- Basic Rnn(GRU) model 
2- RNN(GRU) + TimeDistributed Dense and Batch Normalization
3- CNN + RNN(GRU) + TimeDistributed Dense and Batch Normalization
4- Deeper Network of RNN(GRU) + TimeDistributed Dense and Batch Normalization
5- Bidirectional RNN(GRU) + TimeDistributed Dense and Batch Normalization
6- CNN + 2 layers of RNN(GRU) + TimeDistributed Dense and Batch Normalization and Dropout layers

The last layer had the best performance with the lowest loss 
