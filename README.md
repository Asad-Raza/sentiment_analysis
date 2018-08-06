# sentiment_analysis
sentiment analysis using keras lstm on imdb movie reviews dataset giving accuracy of 86%.
the accuracy could be increased to more than 90% using glove embeddings and changing parameters of lstm model.
cuurent parameters can be seen in the jupyter notebook
the changed parameters:
Input length =1000
LSTM size =200
Dropout = 0.25
Activation = ReLU
Batch size = 64
Embedding size = 300
Hidden layer size = 128
Recurrent Dropout = 0.25
Optimizer = Nadam
Output = Sigmoid
