# Diabete prediction

In this study, perceptron model was implemented from scratch to predict weather sample individuals have diabetes or not by 8 physical health indicators.

### primitive perceptron model
The first model is called the primitive model, It shows the very first idea of how perceptron works. See `perceptron.ipynb`.


### softmax model 
The Second model is called SoftMax model, it used SoftMax method to predict the probability of one sample have diabetes or not. And used cross entropy to calculate the loss. Gradient descent was implemented from scratch to do optimization. See `softmax.ipynb`.

Several experiments were done, which includes using different weights and bias initialization; using different loss function; running different epochs; and using different learning rate.

Scikit-learn build-in perceptron model was implemented as a benchmark, it gives a train accuracy as 0.7 and test accuracy as 0.687. The best train and test accuracy of prim- itive model are: 0.682 and 0.664; The best train and test accuracy of SoftMax model are: 0.786 and 0.765, which beats the benchmark.

__detailed discussion can be found in `Diabete_perceptron.pdf`__
