# Simple Addition using TensorFlow (with Keras)
This is a simple notebook that details the steps in creating a simple addition function (add two numbers 0 - 100) using neural nets.

One of the more distinct approach I took was to encode the operands using one-hot encoding of the ones, tens and hundreds value.

Although this may seem as an overkill, it did however speed up the training since the network needs to now only deal with 0s and 1s.

This code is written using TensorFlow 1.3, Keras 2.0.8 and Python 3.6