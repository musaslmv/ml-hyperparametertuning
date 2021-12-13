# ml-hyperparametertuning
ML 2021 group project - team P37 /n
Hyperparameter tuning effects on validation dataset in terms of overfitting

"Finding the best combination of hyperparameters is called hyperparameter optimization; it is almost impossible to beat state of the art methods without performing hyperparameter optimization. But there are some subtle dangers. Using one algorithm "out-of-the-box" and laboriously tuning hyperparameters for another example leads to an unfair comparison: in general, hyperparameter optimization squeezes out better performance. A better algorithm will in general outperform a worse algorithm, but sometimes, you can find the perfect combination of hyperparameters, which will allow the best-case version of the lesser algorithm to beat an average version of the better algorithm. Choosing the best hyperparameters is like playing with the dials of one amp until you find the perfect sound; It's not really fair to compare the sound of a perfectly-adjusted amplifier with one you use default settings on.

And most vexingly, hyperparameter optimization can lead to overfitting: if a researcher runs 400 experiments on the same train-test splits, then performance on the test data is being incorporated into the training data by choice of hyperparameters. This is true even if regularization is being used! With each time an algorithm is evaluated on the test data, that test data becomes less useful as an "unsullied" evaluator of performance. By the 400th or 4000th evaluation, the test data holds very little mystery and is no longer functioning as a test dataset; it has become a secondary training set." - https://dswalter.github.io/overfitting-regularization-hyperparameters.html

Group project is basically trying to explain the phenomenon in practice. 

