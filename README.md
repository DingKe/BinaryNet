An implemtation of binaryNet for Keras.

The binarized Dense and Conv2D are two keras layers, thus can be integrated into keras framework out of box.

To run the demo:
python mnist_mlp.py

The code is according to the [theano version](https://github.com/MatthieuCourbariaux/BinaryNet).
The only feature (I think) not supported here, is scaling learning rate w.r.t. weight' shape. 
(The only obstacle is the lack of this involved [patch keras](https://github.com/fchollet/keras/pull/3004).)

Reference paper: [BinaryNet: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1](http://arxiv.org/abs/1602.02830)
