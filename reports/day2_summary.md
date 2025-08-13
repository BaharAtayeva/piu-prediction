Day 2

This session focused on implementing a simple multilayer perceptron (MLP) for regression using PyTorch. The aim was to extend beyond linear models and experiment with nonlinear feature transformations via hidden layers.



What was done

Created synthetic regression data using sklearn.datasets.make\_regression.

Split data into training and test sets.

Converted data into PyTorch tensors for model compatibility.

Implemented an MLP model with one hidden layer using nn.Sequential.

Applied ReLU activation function.

Used MSELoss as the loss function.

Optimized the model with SGD.

Trained for 100 epochs, monitoring training loss.

Plotted MSE loss curve to visualize convergence.



-Technical Details:

Input features: 10

Hidden units: 64

Activation: ReLU

Output layer: 1 neuron (regression)

Optimizer: SGD

Epochs: 100

Learning rate: 0.01



Next steps: explore regularization techniques (L2 weight decay, dropout) and alternative optimizers (e.g., Adam).

