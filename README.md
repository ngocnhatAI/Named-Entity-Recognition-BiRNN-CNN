# Named-Entity-Recognition-with-BiRNN-CNNs
 A pytorch implementation of Bidirectional-LSTM_CNNs for Named-Entity-Recoganition

# Result 
| Model       | Dev Set Precision | Dev Set Recall | Dev Set F1 | Test Set Precision | Test Set Recall | Test Set F1 |
|-------------|-------------------|----------------|-------------|--------------------|-----------------|--------------|
| GRU         | 0.87              | 0.69           | 0.74        | 0.83               | 0.69            | 0.74         |
| LSTM        | 0.87              | 0.81           | 0.84        | 0.82               | 0.77            | 0.79         |
| BGRU        | 0.88              | 0.84           | 0.86        | 0.82               | 0.79            | 0.80         |
| BLSTM       | 0.91              | 0.83           | 0.87        | 0.86               | 0.81            | 0.83         |
| BGRU-CNN    | 0.92              | 0.89           | 0.90        | 0.86               | 0.80            | 0.83         |

# Dataset
###  conll-2003 
