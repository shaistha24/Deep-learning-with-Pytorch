## Generative adversarial network (GAN)

### Projects Included: 

**CycleGAN**

*Here CycleGAN is designed for image-to-image translation and it learns from unpaired training data.*

Define and train a CycleGAN to read in an image from a set 𝑋 and transform it so that it looks as if it belongs in set 𝑌.
Specifically, look at a set of images of Yosemite national park taken either during the summer or winter. The seasons are our two domains!
The objective will be to train generators that learn to transform an image from domain 𝑋 into an image that looks like it came from domain 𝑌
(and vice versa). 

Some examples of image data in both sets are pictured below.
![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/GAN/cyclegan.png)


**DCGAN**

Build a GAN using convolutional layers in the generator and discriminator. This is called a Deep Convolutional GAN, or DCGAN for short. The DCGAN architecture was first explored in 2016 and has seen impressive results in generating new images.Training DCGAN on the Street View House Numbers (SVHN) dataset. These are color images of house numbers collected from Google street view. SVHN images are in color and much more variable than MNIST. 

![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/GAN/dcgan.png)

So, our goal is to create a DCGAN that can ***generate new, realistic-looking images of house numbers.***


**MNIST_GAN**

Generative adversarial network (GAN) trained on the MNIST dataset. The idea behind GANs is that you have two networks, a generator 𝐺and a discriminator 𝐷, competing against each other. The generator makes "fake" data to pass to the discriminator. The discriminator also sees real training data and predicts if the data it's received is real or fake. The generator is trained to fool the discriminator, it wants to output data that looks as close as possible to real, training data. The discriminator is a classifier that is trained to figure out which data is real and which is fake. What ends up happening is that the generator learns to make data that is indistinguishable from real data to the discriminator.

Goal is to *** generate new handwritten digits!***
![](https://github.com/shaistha24/Deep-learning-with-Pytorch/blob/master/GAN/mnist%20gan.png)
