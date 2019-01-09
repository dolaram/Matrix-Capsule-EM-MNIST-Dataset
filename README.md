# Matrix-Capsule-EM-MNIST-Dataset
A Tensorflow implementation of CapsNet based on paper [Matrix Capsules with EM Routing](https://openreview.net/pdf?id=HJWLfGWRb)

A capsule is a group of neurons whose outputs represent different properties of the same entity. Each layer in a capsule network contains many capsules. We describe a version of capsules in which each capsule has a logistic unit to represent the presence of an entity and a 4x4 matrix which could learn to represent the relationship between that entity and the viewer (the pose). A capsule in one layer votes for the pose matrix of many different capsules in the layer above by multiplying its own pose matrix by trainable viewpoint-invariant transformation matrices that could learn to represent part-whole relationships. Each of these votes is weighted by an assignment coefficient. These coefficients are iteratively updated for each image using the Expectation-Maximization algorithm such that the output of each capsule is routed to a capsule in the layer above that receives a cluster of similar votes. The transformation matrices are trained discriminatively by backpropagating through the unrolled iterations of EM between each pair of adjacent capsule layers.

# Capsule Network for Deep Reinfocement learning
https://github.com/dolaram/Deep-Reinforcement-Learning-using-Capsule-Network

# References: -
This code is simplified version of code in https://github.com/www0wwwjs1/Matrix-Capsules-EM-Tensorflow.
The code is modifeid so that it can be used for Deep Reinfocement learning.

