# gestrure-recog-ml

# Model
File contains 3 Neural Network model.
1. Conv3D + MaxPooling3D + Dense layer
2. VGG 16 (Transfer learning) + TimeDistributed Layer + LSTM + Dense
3. VGG 16 (Transfer learning) + TimeDistributed Layer + GRU + Dense

# Data Generator :
Data generator is fetching a batch of folders where each folder have 30 images, with label associated with it.

# Data
Data size is around 1.6 GB, and shared as public google drive link.

# Optimizer 
Chose SGD with nesterov, also tried with adam but validation accuracy wasn't that great.

# Validation Accuracy
First model have accuracy around 70% while rest of the two model are able to produce results at >80% accuracy
