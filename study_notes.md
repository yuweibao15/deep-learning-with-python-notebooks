# Store often used keras Activation function

1. Relu
   Applies the rectified linear unit activation function
   $$max(x,0)$$

2. Softmax
   Softmax converts a vector of values to a probability distribution

   The elements of the output vector are in range [0, 1] and sum to 1

3. Sigmoid
   $$sigmoid(x) = 1 / (1 + exp(-x))$$
   Sigmoid returns values between 0 and 1

## How to build a neural network
**The standard workflow: `compile()`, `fit()`, `evaluate()`, `predict()`**
1. Prepare data (reshape, astype)
2. Build model (use `keras` specifying layers and activation function)
3. Compile model (define optimizer, loss, and metrics)
4. Fit model (specify #epochs)
5. Use model to make predictions
6. Evaluate model using new data (accuracy)

What is tensor?

It's a multi-dimensional array. eg. rank 1 tensor is a vector; rank 2 tensor is a matrix 

## Notes
1. It's important to not have sufficiently large intermediate layers
2. It's important to have an appropriate learning rate in model complication optimizer.