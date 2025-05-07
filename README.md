# Basic CNN for MNIST
This is a minimalistic convolutional neural network (CNN) for handwritten digit classification on the MNIST dataset. Despite its extremely simple architecture — consisting of just two convolutional layers followed by max pooling, a single hidden fully connected layer, and dropout — the model achieves an test accuracy of 99.02% after just 5 epochs of training.

The network is intentionally basic, with significant room for optimization and extension. It uses ReLU activations, dropout regularization, and the Adam optimizer with a learning rate of 0.001. No advanced techniques such as batch normalization, learning rate scheduling, data augmentation, or deeper architectures are used — making this a great starting point for experimentation and improvement.
