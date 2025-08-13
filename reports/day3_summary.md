Day 3

This session focused on improving MLP generalization and training stability by introducing dropout regularization and comparing optimizers. Performance evaluation was based on Mean Squared Error (MSE) loss trends.



What was done:

Added dropout to the MLP model (Dropout(0.3)).

Trained two model variants:

MLP + Dropout + SGD

MLP + Dropout + Adam

Logged training losses for both setups.

Visualized loss curves for comparison.



Topics covered:

Overfitting vs. underfitting in neural networks.

Dropout regularization as a method to reduce overfitting.

Comparison of optimization algorithms: SGD vs. Adam.

MSE as a regression performance metric.



Observations:

SGD: High variance in loss, less stable convergence.

Adam: Steady and consistent decline in loss across epochs.

Dropout improved robustness, potentially mitigating overfitting.



Conclusions:

Adam optimizer converged faster and more stably for this dataset.

Dropout is beneficial for deeper models to improve generalization.

