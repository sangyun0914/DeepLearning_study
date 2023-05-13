# Multilayer Perceptrons
:label:`chap_perceptrons`

In this chapter, we will introduce your first truly *deep* network.
The simplest deep networks are called *multilayer perceptrons*,
and they consist of multiple layers of neurons
each fully connected to those in the layer below
(from which they receive input)
and those above (which they, in turn, influence).
Although automatic differentiation
significantly simplifies the implementation of deep learning algorithms,
we will dive deep into how these gradients
are calculated in deep networks.
Then we will
be ready to
discuss issues relating to numerical stability and parameter initialization
that are key to successfully training deep networks.
When we train such high-capacity models we run the risk of overfitting. Thus, we will
revisit regularization and generalization
for deep networks.
Throughout, we aim
to give you a firm grasp not just of the concepts but also of the practice of using deep networks.
At the end of this chapter, we apply what we have introduced so far to a real case: house price
prediction. We punt matters relating to the computational performance, scalability, and efficiency
of our models to subsequent chapters.


## Table of Contents
 - [mlp](mlp.ipynb)
 - [mlp-implementation](mlp-implementation.ipynb)
 - [numerical-stability-and-init](numerical-stability-and-init.ipynb)
 - [dropout](dropout.ipynb)
 - [kaggle-house-price](kaggle-house-price.ipynb)
