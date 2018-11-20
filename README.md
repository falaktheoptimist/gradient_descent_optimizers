### Learn optimizers by coding

Implementation of various gradient descent based optimizers in native python. Using the example of linear regression and its loss function, we implement various optimizers in raw python to get a thorough understanding of how they work and the differences between the optimizers. 

Optimizers implemented include:

* Gradient Descent
* Mini batch gradient descent
* Momentum
* Nesterov
* Adagrad
* Adadelta
* RMSProp
* Adam
* Adamax
* Nadam

Equations and descriptions of optimizers is also included in the notebook. 

Based on the [paper](https://arxiv.org/pdf/1609.04747.pdf)/ [blog post](http://ruder.io/optimizing-gradient-descent/) by [Sebastian Ruder](http://ruder.io/).


### Overview
Any machine learning algortihm at its core minimizes certain loss function. This minimization is an optimisation over the parameters of the concerned ML model. Thus, it requires computation of gradient and movement of parameters in the direction opposite to the gradient direction till it reaches the minima. This movement can occur in a variety of fashions depending on the update step following gradient computation. The different optimizers are basically different algorithms of this update procedure.

### License

MIT License
