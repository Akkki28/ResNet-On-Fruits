# ResNet-On-Fruits
A classification model capable of classifying various fruits by Training a ResNet model on the Fruits360 dataset.

# The ResNet Architecture
![](https://miro.medium.com/v2/resize:fit:1024/1*BnoNVpj7uCNMOFOj1DQBQA.png)

ResNet, or Residual Network, is a deep convolutional neural network architecture characterized by the use of residual blocks. Each residual block includes identity shortcut connections that skip one or more layers, directly adding the input of a block to its output. This structure allows the network to learn residual functions instead of unreferenced functions, which helps mitigate the vanishing gradient problem in very deep networks. The architecture typically consists of stacks of these residual blocks, with each block containing multiple convolutional layers, batch normalization, and ReLU activation
