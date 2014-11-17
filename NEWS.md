# News for Mocha Development

## v0.0.2 (TODO)

* Infrastructure
  * Ability to import caffe trained model?
  * Properly release all the allocated resources upon backend shutdown
* Network
  * Sigmoid activation function
<<<<<<< HEAD
  * Local Response Normalization Layer
=======
  * Power, Split, Element-wise layers
  * Local Response Normalization layer
  * Channel Pooling layer
>>>>>>> 0de1d781f228eb725cae83c415f0f188efe66e1d
* Documentation
  * Complete MNIST demo
  * Detailed document on each component

## v0.0.1 2014.11.13

* Backend
  * Pure Julia CPU
  * Julia + C++ Extension CPU
  * CUDA + cuDNN GPU
* Infrastructure
  * Evaluate on validation set during training
  * Automaticly saving and recovering from snapshots
* Network
  * Convolution layer, mean and max pooling layer, fully connected layer, softmax loss layer
  * ReLU activation function
  * L2 Regularization
* Solver
  * SGD with momentum
* Documentation
  * Demo code of LeNet on MNIST
  * Tutorial document on the MNIST demo (half finished)