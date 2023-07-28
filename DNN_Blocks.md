**Deep Learning Parameters**

*Activation Functions*

-   To decide whether to fire the neuron or not. (Thresholding)

*Loss Functions*

-   Quantifies the error between output of the algorithm and given target value.
-   Regression: MSE, Absolute error, Mean bias error
-   Classification: BCE & Categorical Cross-Entropy

*Optimizers*

-   Updates the model in response to the output of the loss function.
-   Assist in minimizing the loss function. (Steps = learning rate, momentum = avoid false minima)
-   Adam (Adaptive Moment Estimation):
    -   Computationally efficient
    -   Little memory requirements
    -   Well suited for problems that are large in terms of data and/or parameters.
    -   Appropriate for problems with very noisy/or sparse gradients.
    -   Hyper-parameters have intuitive interpretation and typically require little to no tuning
    -   Gradient descent uses a constant learning rate (alpha) whereas Adam computes adaptive learning rates.

*Performance Metrics*

-   Updates the model in response to the output of the loss function.
-   Regression Metrics
    -   MSE: Mean squared error
    -   MAE: Mean absolute error
    -   MAPE: Mean absolute percentage error
    -   COSINE: Cosine proximity
    -   MSLE: Mean squared logarithmic error
    -   LOGCASH: Log Cosh Error
-   Classification Metrics
    -   Binary Accuracy
    -   Categorical Accuracy
    -   Sparse Categorical Accuracy
    -   Top k Categorical Accuracy
    -   Sparse Top k Categorical Accuracy
    -   Accuracy (commonly used built-in function)

*Batch Size*

-   It defines the number of samples that will be propagated through the network before updating the model parameters.
-   Batch of samples go through one full-forward and backward propagation.
