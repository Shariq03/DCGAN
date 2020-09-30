# Deep Convolutional GAN

This was delivered as a final course project for Computer Vision - 2018 at IIIT SriCity. This is an implementation of the <a href="https://arxiv.org/abs/1511.06434">DCGAN</a> paper. 

* The training images have been scaled to a range of [-1, 1]. 
* The activation function used is LeakyRELU(for both the generator and discriminator) with 0.2 as the alpha(slope) value except for the last layer of the generator which uses **tanh** as the activation function.
* There are no Fully connected layers used.
* For the generator, Upsampling followed by a convolutional layer is used to increase the resolution of the image.
* Optimizer - Adams Optimizer.
* A batch size of 128 is used to the train the generator and the discriminator.



# Requirements

* Keras
* Tensorflow
* Numpy
* Tqdm
* Matplotlib

