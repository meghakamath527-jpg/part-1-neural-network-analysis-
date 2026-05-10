## Task 6: Final Reflection
# 1. Role of Weights and Biases
Weights determine the importance of each input feature.
Bias helps shift the activation function so the model can fit data better.
During training, weights and biases are continuously updated using backpropagation.
# 2. Why Activation Function is Required
Activation functions introduce non-linearity.
Without activation functions, the neural network behaves like a simple linear model.
ReLU helps the model learn complex patterns efficiently.
## 3. Effect of Learning Rate
# If Learning Rate is Too High
* Model may overshoot the optimal solution.
* Training becomes unstable.
* Loss may fluctuate.
# If Learning Rate is Too Low
* Training becomes very slow.
* Model may take too long to converge.
* May get stuck before reaching optimal accuracy.
4. Underfitting vs Overfitting
# Underfitting

Occurs when:

Training accuracy is low.
Model is too simple.
Model fails to learn patterns.
# Overfitting

Occurs when:

Training accuracy is very high.
Validation accuracy is much lower.
Model memorizes training data instead of generalizing.
# Observation for This Model
If training and validation accuracy are close, the model generalizes well.
If validation loss increases while training loss decreases, overfitting may be occurring.


## Neural Network Learning Process Summary
# Forward Pass
Inputs move through layers.
Weighted sums are calculated.
Activation functions generate outputs.
# Loss Calculation
Predicted output is compared with actual target.
Binary crossentropy measures prediction error.
#  Backpropagation
Gradients are calculated.
Errors are propagated backward.
# Parameter Updates
Optimizer updates weights and biases.
Goal is to minimize loss.


## Conclusion

In this assignment, a feed-forward neural network was developed for customer churn prediction. The model successfully learned patterns from customer behavior data using forward propagation and backpropagation.

Different hyperparameters were tested to study their effect on performance. The experiment demonstrated the importance of activation functions, optimizers, learning rate selection, and model architecture in neural network training.
