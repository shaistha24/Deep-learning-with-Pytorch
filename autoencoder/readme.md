# Autoencoder

**Simple Autoencoder**

Building a simple autoencoder to compress the MNIST dataset. With autoencoders, we pass input data through an encoder that makes a compressed representation of the input. Then, this representation is passed through a decoder to reconstruct the input data. Generally the encoder and decoder will be built with neural networks, then trained on example data.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/autoencoder/simple%20autoencoder.png)

***Compressed Representation***

A compressed representation can be great for saving and sharing any kind of data in a way that is more efficient than storing raw data. In practice, the compressed representation often holds key information about an input image and we can use it for denoising images or oher kinds of reconstruction and transformation!

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/autoencoder/simple%20autoencoder2.png)


**Denoising Autoencoder**

Sticking with the MNIST dataset, and adding noise to our data and see if we can define and train an autoencoder to de-noise the images.Autoencoders like the ones you've built so far aren't too useful in practive. However, they can be used to denoise images quite successfully just by training the network on noisy images. We can create the noisy images ourselves by adding Gaussian noise to the training images, then clipping the values to be between 0 and 1.***Build the network for the denoising autoencoder.***

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/autoencoder/denoising%20autoencoder.png)


**Convolutional Autoencoder**

Sticking with the MNIST dataset, let's improve our autoencoder's performance using convolutional layers. We'll build a convolutional autoencoder to compress the MNIST dataset. 

The encoder portion will be made of convolutional and pooling layers and the decoder will be made of transpose convolutional layers that learn to "upsample" a compressed representation.

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/autoencoder/c%20autoencoder.png)
