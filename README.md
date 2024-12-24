# Named-Entity-Recognition-with-BiRNN-CNNs
 A pytorch implementation of Bidirectional-LSTM_CNNs for Named-Entity-Recoganition

# Result 

| Model       | Dev Set Precision | Dev Set Recall | Dev Set F1 | Test Set Precision | Test Set Recall | Test Set F1 |
|-------------|-------------------|----------------|-------------|--------------------|-----------------|--------------|
| GRU         | 0.87              | 0.69           | 0.74        | 0.83               | 0.69            | 0.74         |
| LSTM        | 0.87              | 0.81           | 0.82        | 0.82               | 0.77            | 0.79         |
| BGRU        | 0.88              | 0.84           | 0.86        | 0.82               | 0.82            | 0.82         |
| BLSTM       | 0.91              | 0.83           | 0.87        | 0.86               | 0.81            | 0.84         |
| BGRU-CNN    | 0.92              | 0.89           | 0.91        | 0.86               | 0.88            | 0.87         |
| BLSTM-CNN   | **0.93**        | **0.92**       | **0.93**    | **0.87**           | **0.89**        | **0.88**     |

# Dataset
###  conll-2003 
