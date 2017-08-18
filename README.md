# AdaptiveLearning
Automatically stop training earlier layers as training progresses in neural networks

Came up with a formula using number of hidden layers and training iterations to calculate threshold for each hidden layer such that if the norm of gradient coming to a layer is less than the threshold, stop training that layer and backpropagating error gradient any further.

Observation -
This acts as good generalisation and also increases computation efficiency.
