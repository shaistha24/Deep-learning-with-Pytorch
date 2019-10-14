# Introduction to Pytorch

Covers course related notebooks and projects for Pytorch introduction. Start from creating a tensor followed by the neural network.

I have also written a series on Medium on ***Introduction to Tensors using Pytorch*** which can be accessed from here https://medium.com/secure-and-private-ai-writing-challenge/introduction-to-tensors-1-de7dded35fea

**Projects included:**

**Classifying Fashion-MNIST**

Build and train a neural network using the Fashion-MNIST dataset, a drop-in replacement for the MNIST dataset. MNIST is actually quite trivial with neural networks where you can easily achieve better than 97% accuracy. Fashion-MNIST is a set of 28x28 greyscale images of clothes. It's more complex than MNIST, so it's a better representation of the actual performance of your network, and a better representation of datasets you'll use in the real world.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/Intro%20to%20Pytorch/fmnist.png)

**Style Transfer with Deep Neural Networks**

Recreate a style transfer method that is outlined in the paper, Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch.
In this paper, style transfer uses the features found in the 19-layer VGG Network, which is comprised of a series of convolutional and pooling layers, and a few fully-connected layers. In the image below, the convolutional layers are named by stack and their order in the stack. Conv_1_1 is the first convolutional layer that an image is passed through, in the first stack. Conv_2_1 is the first convolutional layer in the second stack. The deepest convolutional layer in the network is conv_5_4.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/Intro%20to%20Pytorch/st-ex.png)

Style transfer relies on separating the content and style of an image. Given one content image and one style image, we aim to create a new, target image which should contain our desired content and style components:

- objects and their arrangement are similar to that of the content image

- style, colors, and textures are similar to that of the style image

Example:  the content image is of a cat, and the style image is of Hokusai's Great Wave. The generated target image still contains the cat but is stylized with the waves, blue and beige colors, and block print textures of the style image!

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/Intro%20to%20Pytorch/style%20transfer.png)




