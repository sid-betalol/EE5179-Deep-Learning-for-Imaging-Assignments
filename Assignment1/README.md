# Assignment-1: Implementing Backpropagation from scratch using NumPy

- All experiments conducted on the MNIST Dataset and MLP architecture
- Created template classes for activation functions, loss functions, optimizers with methods for calculating and backpropagating updates, with and without weight decay.
- Activation Functions: Linear, Sigmoid, Tanh, ReLU, LeakyReLU
- Loss Functions: Mean Squared Error, Cross Entropy
- Optimizers: SGD, Momentum, RMSProp, Adam
- Implemented a layer class for Xavier weight intialization, forward pass, calculating, backpropgating, and making updates
- Designed a NN class to put stack the layers together with methods for training, evaluating, and plotting losses and confusion matrix
- Conducted a comparitive analysis of the 4 optimizers with Cross Entropy loss
- Contrasted the performance of the top optimizer with MSE Loss and Cross Entropy loss as the loss criterion
- Analysed the performance of the top model with different values of weight decay
- Compared the performance of the model implemented froms scratch using NumPy and the same model with PyTorch and showed competitive results
