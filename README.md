# Delta-learning-rule

The delta rule in an artificial neural network is a specific kind of backpropagation that assists in refining the machine learning/artificial intelligence network, making associations among input and outputs with different layers of artificial neurons. The Delta rule is also called the Delta learning rule.

Generally, backpropagation has to do with recalculating input weights for artificial neurons utilizing a gradient technique. Delta learning does this by using the difference between a target activation and an obtained activation. By using a linear activation function, network connections are balanced. Another approach to explain the Delta rule is that it uses an error function to perform gradient descent learning.

## Mathematical equation:
The given equation gives the mathematical equation for delta learning rule:

∆w = µ.x.z

∆w = µ(t-y)x

Here,

∆w = weight change.

µ = the constant and positive learning rate.

X = the input value from pre-synaptic neuron.

z= (t-y) is the difference between the desired input t and the actual output y. The above mentioned mathematical rule cab be used only for a single output unit.

The different weights can be determined with respect to these two cases.

Case 1 - When t ≠ k, then

w(new) = w(old) + ∆w

Case 2 - When t = k, then

##### No change in weight

For a given input vector, we need to compare the output vector, and the final output vector would be the correct answer. If the difference is zero, then no learning takes place, so we need to adjust the weight to reduce the difference. If the set of input patterns is taken from an independent set, then it uses learn arbitrary connections using the delta learning rule.
